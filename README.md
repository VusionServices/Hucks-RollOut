# Hucks Rollout Control Tower

Stable dashboard entry point for the Hucks rollout.

## Current architecture

ClickUp rollout tasks -> scheduled refresh -> GitHub `index.html` -> GitHub Pages.

The dashboard is intentionally conservative: it only displays fields currently exposed through the connected ClickUp actions and does not invent missing custom-field values.

## GitHub Pages

Enable **Settings -> Pages** and publish from the `main` branch root. The expected site URL is:

`https://vusionservices.github.io/Hucks-RollOut/`

## ClickUp source

Workspace: `14341097`

Rollout list: `Hucks Stores 135 Rollout`

Folder: `2026 Installation Project Tracker`

The ClickUp Brain design calls for the Hucks Control Tower structure to remain locked while refreshing only the underlying data arrays and date.