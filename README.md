# Divya Bhandari — academic website (crimson edition)

Static HTML/CSS/JavaScript site for https://www.divyabhandari.com hosted by GitHub Pages.

## Update an existing GitHub Pages site

Repository: https://github.com/bhandari-divya/bhandari-divya.github.io

Replace the **entire contents** of the repository with this package (preserving `CNAME`, `.nojekyll`, pages and `assets/` folders). Make a commit to `main`. Do **not** upload the ZIP itself. GitHub Pages is already configured. Do not change Porkbun DNS.

Simplest reliable bulk upload: clone the repository with GitHub Desktop, copy the extracted files into the cloned local folder, then commit and push. A browser upload is also possible but existing files might need explicit replacement.

## Your exact photo filenames (case sensitive!)

Upload your OWN photo files into `assets/images/` using these exact names; they are NOT in this package. Until uploaded, the site shows a neutral placeholder instead of a broken image.

- `Headshot1.png` — homepage hero portrait
- `Headshot2.JPG` — homepage about portrait
- `TeachingShot1.jpeg` — teaching gallery
- `TeachingShot2.jpeg` — teaching gallery
- `ResearchShot1.jpeg` — featured research
- `ResearchShot2.jpeg` — research page
- `ResearchShot3.jpeg` — optional future image (not yet displayed)
- `Award1.jpeg` — optional future image (not yet displayed)

Names above match the file screenshot provided. **Do not merely rename file extensions**: use the original image files with their actual formats and exact capitalization. If you change a filename, update the `<img src="...">` in the relevant HTML file.

## Site files

- `index.html`, `research.html`, `publications.html`, `teaching.html`, `experience.html`, `cv.html`, `contact.html`
- `assets/css/style.css` (crimson styles, desktop/mobile)
- `assets/js/site.js` (navigation, scroll animations, searchable/filterable publications)
- `assets/images/photo-placeholder.svg` (temporary graceful fallback)
- `CNAME` and `.nojekyll` (keep these!)

## Academic CV

The public CV page is a concise academic-profile overview. It **does not** publish the NIW-oriented CV or display internal upload instructions. When a separate academic CV PDF is ready, a PDF download button can be added.

## Checklist

Check each page after deployment, verify current appointments and citation details, confirm contact forwarding, and upload photos only with permission from identifiable people. Google Scholar, ORCID and LinkedIn links are already included.


## Revision v3
- Removed developer/photo-replacement captions from visitor-facing teaching gallery.
- Added portrait frames, inner white borders, and refined image spacing.
- Image file extensions remain exact and case sensitive: Headshot1.png, Headshot2.JPG, TeachingShot1.jpeg, TeachingShot2.jpeg, ResearchShot1.jpeg, ResearchShot2.jpeg.
- You do not need to reconfigure DNS, HTTPS, or GitHub Pages. Replace the website files and commit.
