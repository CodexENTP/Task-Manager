# Codex Analytics — Clipboard V1

A client-side to-do list / task manager designed for GitHub Pages. Clipboard is a simplified interpretation of the supplied Airtable prototype and is designed to work with the Codex Grant Calendar Tool.

## V1 features
- Task List with status, priority, category, due date, estimated time, related event, and notes
- Daily List view
- Deadline view based on imported Grant Calendar events
- Calendar → Clipboard guided task discovery
- Category-aware question sets for grant deadlines, site visits, meetings/trainings, closures, and custom events
- **Pass** on every question and **Skip to End** at any point
- Suggested task review/edit before adding to the list
- Save/Open project as JSON
- Local browser persistence
- Imports the Calendar Tool `Events` worksheet from `.xlsx` or a Calendar project `.json`
- Uses the supplied Codex Analytics logo on a white interface; the logo is kept within its native display size and given additional header clearance so it does not touch the divider below it.

## GitHub Pages
Upload these files to the repository root:
- `index.html`
- `styles.css`
- `app.js`
- `codex-analytics-logo.png`

Then enable GitHub Pages for the repository root/main branch.

## Test
Use `Codex_Grant_Calendar_V1_Test_Import.xlsx` from the Calendar Tool project. Go to **From Calendar → Import Calendar File**, select an event, and walk through the questions.

## Note
XLSX import uses SheetJS from a CDN. The app otherwise stores project data locally in the browser and does not require a backend.
