# Eugene Poh — academic website

A responsive, static academic portfolio for GitHub Pages. No build step or package installation is needed.

## Publish

In GitHub, open Settings → Pages. Select **Deploy from a branch**, then **main** and **/ (root)**, and save. The site will appear at https://eugenepoh.github.io/.

## Edit

- `index.html`: biography, research, publications and contact links.
- `styles.css`: colours, typography and responsive layout.
- `.nojekyll`: serves the files directly.

Preview locally with `python3 -m http.server 8000` and visit http://localhost:8000.

The portrait is served from the existing public UQ profile. Content is based on https://www.eugenepoh.com/ and https://about.uq.edu.au/experts/46667, with publication metadata verified against the UQ publication list. The profile currently has inconsistent position labels, so the site states the institutional affiliation without asserting a job title.

## Custom domain

Only change the domain after reviewing the new site. Set `www.eugenepoh.com` in GitHub Pages custom-domain settings and configure the domain's DNS according to GitHub's documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site. Keep the existing domain configuration until ready to switch.

## Publication list

Journal papers and preprints are grouped separately, newest first in each section, without displayed category counts. Conference contributions and the doctoral thesis are excluded.

Sources: https://scholar.google.com/citations?user=ecUaIG4AAAAJ&hl=en (checked 19 September 2026). Separate Scholar records and preprint versions are retained, including the alternate three-author entry linking to the same bioRxiv manuscript. This is a static snapshot; future additions require an edit.
