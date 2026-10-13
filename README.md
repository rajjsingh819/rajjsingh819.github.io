# Raj Singh Portfolio

A static portfolio website: plain HTML, CSS and JavaScript. No build step.

## Put it online with GitHub Pages
1. On GitHub, create a new repository (for example `portfolio`).
2. Upload everything in this folder: `index.html`, the `assets` folder and this README.
3. Go to Settings > Pages. Under "Build and deployment", choose "Deploy from a branch", select the `main` branch and the `/ (root)` folder, then Save.
4. After a minute, your site is live at `https://rajjsingh819.github.io/<repository-name>/`.

## What to edit (all inside index.html)
- Skill percentages: search for `class="bar"` and change the number in `style="width:..%"`, `aria-valuenow` and the text.
- Projects: each project is an `<article class="row proj">`. The long overviews are in the `PROJ` list near the bottom, and the GitHub links are in `LINKS`.
- Contact form: the Formspree link is in `FORM_ENDPOINT` near the bottom.
- GitHub feed: `USER` and `FEATURED` at the start of the last script. Repos listed in `FEATURED` are not repeated in "Latest on GitHub".
- Colors and fonts: the variables at the top of the `<style>` block.
- Certificates: images are in `assets/certs`, and their titles are in the `NAMES` list.
- Resume: replace `assets/Raj-Singh-Resume.pdf` and `assets/resume.jpg`.

## Notes
- The "Latest on GitHub" block and the contact form send requests to github.com and formspree.io, so they only work when the site is hosted, not when you open index.html from a folder.
- Confirm the Formspree email (they send one the first time) or messages will not arrive.
