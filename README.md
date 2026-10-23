# AnalystKayode — GitHub Pages Website

A redesigned static website based on the published content at analystkayode.com (reviewed October 2026).

## Pages
- Home (`index.html`)
- About: biography, education, memberships, certifications, CV link
- Research: research areas and projects
- Publications: three articles and peer review service
- Portfolio: eight project report filenames, tools, methods
- News: media coverage, conferences, workshops
- Awards: four awards
- Photos: placeholder until original photos are supplied
- Contact

## Publish
1. Create a public repository `kayusman.github.io` on GitHub.
2. Upload all files from this ZIP **at repository root**.
3. Go to Settings → Pages → Deploy from branch → main → / (root).
4. Test `https://kayusman.github.io` before changing Namecheap DNS.
5. In Settings → Pages, configure custom domain `www.analystkayode.com`. The included CNAME file specifies it.
6. Only after testing, update Namecheap A records for `@` to GitHub Pages addresses and `www` CNAME to `kayusman.github.io`; preserve mail/TXT records.
7. Enable HTTPS when available.

## Important migration notes
- PDFs and photographs were embedded in Google Sites and **are not included**. Links to original pages are preserved. Download your original files and add them to `assets/` before removing Google Sites.
- Hero portrait is a placeholder; replace with your actual photo.
- Verify publication metadata (especially the 2021 citation) against the DOI before publication.
- Google Sites URLs such as `/home`, `/about`, `/publications` may be indexed. This static version uses `.html` URLs. Arrange redirects where possible and submit the new sitemap in Search Console.
- Do **not** point the domain to GitHub until missing PDF/photo assets are migrated.
- Primary contact is analystkayode@gmail.com.
