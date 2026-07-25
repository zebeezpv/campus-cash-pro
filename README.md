# Campus Cash

Campus Cash is a simple student budget web app built for mobile and desktop.

## Features

- Track income and expenses in South African rand
- Filter transactions by month
- Set monthly category budgets
- See spending warnings and category totals
- Export transactions to CSV
- Backup and restore app data using JSON
- Works offline after first load
- Saves data locally in the browser

## Run it

Open `index.html` in a browser.

For the installable/offline version, serve the folder with a small local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

On a phone, use the browser's **Add to Home Screen** option.

## Privacy

The app does not upload financial data. Everything stays in local browser storage unless the user exports a backup.
