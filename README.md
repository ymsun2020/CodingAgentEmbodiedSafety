# ArmedAgent — When Coding Agents Get Arms

Research project page for **Safety Risks Across the Digital-Physical Boundary**.

Includes the paper abstract, Figure 1, and five real-robot experiment figures. The arXiv link is a placeholder for a future update; no paper PDF is included.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this directory and visit http://localhost:8000.

## Enable GitHub Pages

1. Open this repository’s **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/ (root)**, then click **Save**.
4. Check **Actions** for the Pages deployment result.

Expected site URL: https://ymsun2020.github.io/CodingAgentEmbodiedSafety/

## Files

- `index.html`: project introduction, abstract, and overview.
- `styles.css`: responsive layout.
- `script.js`: experiment gallery and image enlargement.
- `assets/`: six figure images.
- `.nojekyll`: serves the static site without Jekyll processing.

No build step or external dependencies are required.

## Add the arXiv link

In `index.html`, replace the `arxiv-placeholder` span with an anchor linking to the paper’s arXiv abstract page once available. PDF files are excluded by `.gitignore`.
