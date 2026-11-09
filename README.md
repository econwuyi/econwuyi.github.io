# Yi Wu — academic website

A lightweight, static academic website for GitHub Pages. No build tools required.

## Publish
1. Create a **public** repository named `econwuyi.github.io` under the `econwuyi` account.
2. Upload the **contents of this folder** to the repository root (not the `.zip` archive itself): `index.html`, `research.html`, `cv.html`, `style.css`, `favicon.svg`, `.nojekyll`, and the `files/` folder.
3. Go to **Settings → Pages → Build and deployment**, set Source to **Deploy from a branch**, Branch `main`, Folder `/(root)`, then Save.
4. Visit https://econwuyi.github.io after GitHub completes deployment.

## Important before finalizing
- The collapsible **Research summary** text is a short editorial summary, **not an official manuscript abstract**. Replace it with the author-approved abstracts from the three papers.
- The marital-matching paper has no public draft link yet. Add one only if you want that manuscript to be publicly downloadable.
- The bundled PDF is the CV uploaded as `申请CV.pdf`. Update `files/Yi_Wu_CV.pdf` whenever your CV changes, and check your GPA and submission statuses for accuracy.
- The DOI links point to the published article and preprint pages. They may lead to publisher pages rather than direct PDF downloads.
- When buying a domain, edit the `canonical` URL in `index.html` and configure the domain under GitHub Pages settings and your registrar's DNS.

## Design
Plain HTML/CSS, responsive layout, no tracking or external scripts. Accessible navigation and PDF download link.
