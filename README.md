# Connecticut Voices for Children — Benefits Tracker

Final branded dashboard: toplines above the trend (left) and map (right), condensed SNAP recommendations above About the data. Mobile panels stack in reading order.

## Hosting
Upload all files in this folder to your web host, or push them to a GitHub repository and set Pages to GitHub Actions. The included workflow publishes the dashboard. For WordPress, embed the hosted index.html in a full-width iframe with an accessible title and scrolling enabled.

## Data
This remains a saved snapshot, not an automatically refreshed feed. See sources/manifest.json for current coverage and source provenance. See METHODOLOGY.md and allocation-audit.json.

## Branding
Official logo retrieved from https://ctvoices.org/wp-content/uploads/2026/05/CT-Voices_Just_Logo-1024x653.png on October 11, 2026. Bundled as ctvoices-logo.png. Logo and organizational identity belong to Connecticut Voices for Children.

## Updating the source
See [UPDATE-DATA.md](UPDATE-DATA.md). Replace sources/dss-town-toa.xlsx and push to main to rebuild during deployment. The Excel file is now the authoritative town-level input. The source publication timestamp is unknown unless supplied in sources/config.json.
