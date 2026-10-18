# Profile Studio — GitHub Profile Frontend

A responsive, animated GitHub profile dashboard with interactive navigation, searchable/sortable repositories, activity timeline, theme switcher, contribution heatmap, and live public GitHub API integration.

## Run it
1. Unzip the folder.
2. Open `index.html` in a modern browser. For best results, use a simple local server or VS Code Live Server.
3. Click **Customize** and enter your GitHub username to load your public profile and repositories.

No API token is required for public data. GitHub may rate-limit unauthenticated API requests. If live data cannot load, the included demo profile remains available.

## Customize
- `app.js`: default demo repositories, timeline, profile loading.
- `styles.css`: colors, spacing, responsive layout, animation.
- `index.html`: content and page structure.

## Notes
This is a frontend-only website. It does not create or modify a GitHub account or repository. The demo contribution heatmap is illustrative; GitHub's contribution graph requires authenticated/official data not provided by this public profile endpoint.
