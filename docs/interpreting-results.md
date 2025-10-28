# Interpreting Results

The **Audit Results** section summarizes how your uploaded PLC programs performed against selected standards. It includes both high-level KPIs and detailed, filterable results.

## 1. Overview Metrics

Each completed audit displays three key metrics at the top of the results view:

* **Programs** — Total number of PLC programs included in the audit.
* **Pass Rate** — Percentage of checks that passed successfully.
* **Total Checks** — Number of standard checks performed across all programs.

These metrics help you assess compliance coverage and improvement over time.

## 2. Detailed Results Table

The **Detailed Results** table lists every check result for the selected audit.

### Default Table View

By default, the table is **grouped by Program → Status → Check**, and each grouped section displays the **number of rows** it contains.
You can **expand** or **collapse** these groups to view detailed results.

Only the **Item** column is visible by default — other columns (such as *File*, *Standard*, *Date*, or *Audit ID*) are hidden initially for a cleaner view.

> **Tip:** Use the **Column Selector** on the toolbar to show or hide additional columns at any time.

### Available Columns

Each row includes the following fields:

* **Program** – The PLC program being analyzed.
* **File** – The uploaded source file.
* **Standard** – The compliance or coding standard applied.
* **Check** – The specific rule or test evaluated.
* **Status** – The result of the check:

  * ✅ **Passed** – The item meets the rule.
  * ⚠️ **Warning** – Minor deviation or informational note.
  * ❌ **Failed** – The item violates the rule.
* **Item** – The tag, instruction, or element that triggered the result.
* **Date** – When the check was recorded.

### Customizing the View

You can:

* **Filter** or **sort** results by any column.
* **Reorder**, **resize**, or **hide/show** columns via the toolbar.
* **Group** or **ungroup** results to view by program, standard, or status.

## 3. Reviewing Past Audits

Use the dropdown above the results to switch between completed audits.
Each selection reloads the dataset and recalculates KPIs automatically.

> **Tip:** The “Latest Audit Results” option shows the most recent audit data by default.

## 4. Exporting and Sharing

Results can be exported for further analysis or reporting:

* **Export PDF** — Generates a formatted summary with KPIs and branding.
* **Export CSV** — Downloads raw results for spreadsheet analysis.
