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

Updated 19 September 2026 from https://scholar.google.com/citations?user=ecUaIG4AAAAJ&hl=en. 13 Scholar entries are included (the doctoral thesis is excluded), ordered newest first, with links to their individual records. Separate records and preprint versions are deliberately preserved. The list is a static snapshot; future additions require an edit. Author spellings follow Scholar.

The publication list is grouped into 7 journal papers, 3 conference contributions, and 3 preprint records. The alternate three-author Scholar entry links to the same bioRxiv manuscript and is retained under preprints. The eye-centred coordinate-frame abstract and author names were verified against Frontiers: https://doi.org/10.3389/conf.fnhum.2015.217.00317.
