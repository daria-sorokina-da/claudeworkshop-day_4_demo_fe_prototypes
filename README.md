# Enchanted Stables Prototypes Gallery

A shared repository of clickable HTML prototypes for the Enchanted Stables staff portal. Each prototype is a self-contained, interactive mockup built with Claude that can be opened directly in any browser — no build step required.

## What's here

Each folder contains a complete, runnable prototype for a feature or page.

_No prototypes have been added yet — see [Creating a new prototype](#creating-a-new-prototype) below._

## How to use a prototype

1. **Navigate to a folder** — e.g. `schedule/`
2. **Open `index.html` in your browser** — double-click the file or right-click → Open with Browser
3. **Click through the flow** — interact with the UI as you would the real app
4. **Share feedback** — comment on the PR or linked ticket with what you'd change

## Creating a new prototype

When you build a prototype with Claude:

1. Create a new folder named after the feature (e.g. `bulk-actions/`, `registration-flow/`)
2. Save the prototype as `index.html` inside that folder
3. Commit and push:
   ```bash
   git add my-feature/
   git commit -m "Add my-feature prototype"
   git push
   ```
4. Share the GitHub link with your team: `https://github.com/<your-fork>/claudeworkshop-day_4_demo_fe_prototypes/blob/main/my-feature/index.html`

Teammates can click **Raw** to open the prototype directly in the browser.

## Design principles

- **Self-contained** — each prototype is a single HTML file with inline CSS and vanilla JavaScript. No dependencies, no build step.
- **Matches the real app** — prototypes mirror the actual design system (colours, spacing, typography, component patterns) from the Enchanted Stables portal.
- **Realistic data** — mock data uses the real field names and shapes (`spotsTotal`, `spotsRegistered`, staff roles, etc.) so the prototype is a faithful preview.
- **Stateful interactions** — local state tracks user actions (selections, form inputs, panel states) — you can click through multi-step flows.

## License

See [LICENSE.md](LICENSE.md). This work is licensed under CC BY 4.0.
