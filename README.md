# Daoyuan Jin's homepage

Static HTML and CSS, hosted at https://dyjin2.github.io/. No build tools, packages, or JavaScript are required.

## Update the site

- Edit `index.html` for biography, news, research, publications, education, talks, and Misc. Search for `EDIT MISC` to find the personal placeholder.
- Edit `style.css` for appearance and mobile layout.
- Replace `assets/boston_crop.jpg` to update the portrait.
- Replace `assets/Daoyuan_Jin_CV.pdf` to update the CV. Remove private contact information, including phone numbers, from the PDF itself and its links before uploading.
- Update the footer's month and year after content changes.

The source CV is dated September 2025; candidacy was updated from the owner's August 11, 2026 announcement. Talks are a placeholder because the CV supplies none. Advisor and lab links come from the previous homepage. Publication links were checked against paper records.

## Hosting

GitHub repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`. Keep `.nojekyll` so GitHub serves the files directly. Keep the repository name `dyjin2.github.io` to retain the existing URL.

## Backup

`archive-old-site` preserves the original site at commit `bba468c21b609c68d382ff1a63e1febd6669005d`. The previous `master` branch is also retained. To restore the old site, point Pages at `archive-old-site` and the root folder.

The new layout was independently implemented, inspired by the simple academic homepage at https://youngxinyu1802.github.io/.
