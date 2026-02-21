# NICE Copilot 365 KPI Workbook (Static HTML)

This repo contains a single **static** page (`index.html`) that renders the Excel workbook as an interactive table.

## Publish on GitHub Pages
1. Create a new GitHub repository (or use an existing one).
2. Upload `index.html` to the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / root
5. Save.

Your site will be available at:
`https://<username>.github.io/<repo>/`

## How it works
- Tabs switch between sheets.
- Search filters rows by any column.
- Click headers to sort.
- Export the filtered view as CSV.

> Note: This is client-side only (no server).
