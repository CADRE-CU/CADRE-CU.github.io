# CADRE website

Static site for the Center for Assessment, Design, Research and Evaluation (CADRE), School of Education, University of Colorado Boulder.

Plain HTML and CSS, no build step. Edit a page, commit, push; GitHub Pages publishes it.

- `index.html` — homepage
- `classroom-assessment.html`, `accountability.html` (Educational Accountability), `educational-measurement.html`, `higher-education.html`, `program-evaluation.html` — the five focus-area pages
- `technical-advice.html` — sixth focus area, hidden since October 2026 (not linked; its homepage card is commented out in `index.html`)
- `crg.html` — Content-Referenced Growth project page
- `how-to-edit.html` — editing guide for CADRE staff (unlinked; https://cadre-cu.github.io/how-to-edit.html)
- `styles.css` — shared stylesheet (bump the `?v=` query on the `<link>` tags after editing it so browsers fetch the new version)
- `images/`, `media/` — optimized images and the CRG video

To preview locally, run any static server from this folder that supports HTTP range requests (needed for video seeking), for example `npx http-server -p 8765`.
