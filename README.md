# CADRE website

Static site for the Center for Assessment, Design, Research and Evaluation (CADRE), School of Education, University of Colorado Boulder.

Plain HTML and CSS, no build step. Edit a page, commit, push; GitHub Pages publishes it.

- `index.html` — homepage
- `classroom-assessment.html`, `educational-measurement.html`, `accountability.html`, `higher-education.html`, `program-evaluation.html`, `technical-advice.html` — focus-area pages
- `crg.html` — Content-Referenced Growth project page
- `styles.css` — shared stylesheet (bump the `?v=` query on the `<link>` tags after editing it so browsers fetch the new version)
- `images/`, `media/` — optimized images and the CRG video

To preview locally, run any static server from this folder that supports HTTP range requests (needed for video seeking), for example `npx http-server -p 8765`.
