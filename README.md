<h1>Student Finance Tracker</h1>

The Student Finance Tracker is a responsive, browser-based app that helps students track daily expenses. You can add transactions, sort and search them using regex, view statistics, set a spending cap, and import/export data in JSON format. The app is built with HTML, CSS, and Vanilla JavaScript, and all data is saved locally using localStorage.

First is the Setup Guide:

1.Clone the repository.
2.Open the project folder.
3.Open index.html in any modern browser.
4.No installation or backend setup is required.
5.Features

After getting to the website add a transaction as it will be mentioned below:

1.Add Transactions: Input description, amount, category, and date with validation.
2.Live Regex Search: Filter transactions in real time; matching text is highlighted.
3.Sorting: Click table headers to sort by date, description, amount, or category.
4.Dashboard & Stats: View total transactions, total spending, and spending trends.
5.Monthly Spending Cap: Set a cap and receive warnings if exceeded.
6.JSON Import/Export: Save and restore transaction data safely.
7.Responsive Design: Mobile-first layout adapts to phones, tablets, and desktops.

Regex Catalog

1.Description: No leading/trailing spaces.
2.Amount: Valid currency format with up to 2 decimals.
3.Date: Must be in YYYY-MM-DD format.
4.Category: Letters only (allows spaces or hyphens).
5.Advanced: Duplicate word detection to catch repeated words.

Keyboard Map

1.Tab / Shift+Tab: Navigate between inputs and buttons.
2.Enter: Submit forms or activate buttons.
3.Arrow keys: Navigate table if needed.
4.Skip-to-content link allows jumping straight to main content.

Accessibility Notes

1.Semantic HTML elements and proper headings.
2.Labels are correctly bound to inputs.
3.Focus is always visible for keyboard users.
4.ARIA live regions announce updates politely or assertively (cap warnings).
5.Adequate color contrast and screen-reader-friendly highlighting.

Testing Instructions

1.Add Transactions: Confirm they appear in the table and persist after refresh.
2.Regex Search: Try patterns to filter results; ensure highlights show correctly.
3.Sorting: Click table headers and verify ascending/descending order.
4.Spending Cap: Set a cap below total and check for proper warning.
5.JSON Import/Export: Export data, delete records, then import to restore.
6.Keyboard Navigation: Navigate fully without a mouse.
7.tests.html: Open in browser and check console for passing assertions.

My website link is http://127.0.0.1:5500/student_finance_tracker_uhuguette_summative/index.html
