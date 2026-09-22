# Daoyuan Jin's homepage

Static HTML and CSS, hosted at https://dyjin2.github.io/. No build tools, packages, or JavaScript are required.

## Update the site

- Edit `index.html` for biography, news, publications, education, talks, awards, and Misc. Search for `EDIT MISC` to find the personal interests paragraph. Selected Research is preserved inside an HTML comment and does not render; remove its surrounding comment to restore it.
- Edit `style.css` for appearance and mobile layout.
- Replace `assets/boston_crop.jpg` to update the portrait.
- Replace `assets/Daoyuan_Jin_CV.pdf` to update the CV. Remove private contact information, including phone numbers, from the PDF itself and its links before uploading.
- Update the footer's month and year after content changes.

The source CV is dated September 2025; candidacy was updated from the owner's August 11, 2026 announcement. Talks and personal interests were supplied by the owner in September 2026. Advisor and lab links and the three awards come from the archived homepage (the uploaded CV does not list awards). The two 2026 publications were found on the owner's Google Scholar profile and verified against ASABE publisher records, including author lists and DOI links.

## Hosting

GitHub repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`. Keep `.nojekyll` so GitHub serves the files directly. Keep the repository name `dyjin2.github.io` to retain the existing URL.

## Backup

`archive-old-site` preserves the original site. The previous `master` branch is also retained. To restore the old site, point Pages at `archive-old-site` and the root folder.
