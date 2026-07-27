# Campus Cash Pro v2

Updated features:

- Dashboard month selector with previous and next arrows
- Regular income can be edited separately for every month
- Extra income is calculated from income transactions
- Expenses and remaining balance change with the selected month
- PIN screen fully hides the app until the correct PIN is entered
- Transaction search, editing, bulk deletion, custom categories, budgets, savings goals, receipts, backups and offline support

Data remains stored locally in the browser. Use JSON backups regularly.


## Version 4
- Dashboard transaction form starts collapsed.
- Category dropdowns refresh after every category add, edit or delete.
- Category emoji is selected automatically.
- Transactions use the currently selected dashboard month.
- Expenses update all totals, budgets, charts and insights for the matching category.


## Version 5 fixes

- The category dropdown starts with “Select a category”.
- All custom categories remain available after adding a transaction.
- The form clears the selected category, emoji, amount, description and receipt after every save.
- The previous category is no longer carried into the next transaction.
- Adding a new custom category refreshes the list without locking the form to that category.


## Version 6

- Savings goals now start collapsed and expand when tapped.
- Payday planner now starts collapsed and expands when tapped.
- Smart insights remain visible even while the payday planner is collapsed.
- The behaviour matches the Add Transaction section.


## Version 7

- Added an eye button beside Edit on Regular Income.
- Tap it to blur or reveal the income amount.
- The selected privacy setting is remembered.
- Disabled pinch zoom, page scaling and double-tap zoom for a more app-like layout.


## Version 8 — Bank statement import
- Added CSV statement upload and preview.
- Matches descriptions to existing categories.
- Can create missing categories automatically.
- Imported entries update all relevant totals, budgets, charts and insights.
- Avoids obvious duplicate imports.
- PDF and image statements are not parsed in this offline version.


## Version 9 - PDF bank statements

- Supports both PDF and CSV statement uploads.
- Includes a parser for text-based Capitec account statements.
- Reads multi-page transaction tables.
- Reads Date, Description, Category, Money In, Money Out and Fee columns.
- Bank fees on individual transactions are included in the imported expense amount.
- Uses the bank category column to suggest app categories.
- Matches diabetes-related transactions to an existing Diabetic category when available.
- Ignores pending card transactions until they are posted.
- Scanned-image PDFs still require OCR and are not supported reliably.
- PDF.js is loaded when a PDF is selected, so PDF import requires an internet connection.


## Version 10 — Bank income goes to Regular Income

- Money In rows from PDF and CSV statements now increase Regular Income for the correct month.
- Bank-statement income no longer appears under Extra Income.
- Money left and daily allowance recalculate using the updated Regular Income.
- The app remembers imported bank-income rows to prevent adding them twice.
- A one-time migration moves older imported “Payment Received” and “Interest Received” entries from Extra Income into Regular Income.
- Imported expenses continue to update transactions, categories, budgets, charts and insights.
