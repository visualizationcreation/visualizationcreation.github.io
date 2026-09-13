# Orbiversity domain connection

Live entry: https://orbiversity.com/

This GitHub Pages user-site repository holds the shared custom domain for the account. Pages publishes `main`, root, with `CNAME` set to `orbiversity.com`. Keep HTTPS enforced. Hostinger manages domain registration and DNS.

The homepage forwards to `/orb-archive/`, preserving query parameters and section anchors. The original `orb-archive` repository continues to serve the complete archive and Studio. Each already-published project inherits a path such as `https://orbiversity.com/olympic-national-park/`; continue editing the original project repository. Do not add Orbiversity as a custom domain to those individual repositories.

Projects with an explicit custom domain retain it: CNSDR continues at https://creativensdr.com/. The Orb Navigator application and saved-orb storage remain on Netlify. Private repositories and unpublished projects were not enabled by this change.

`404.html` forwards the previous root `/studio.html`, `/about.html`, `/start.html`, and `/index.html` links to their archive paths, preserving queries and anchors. Other missing paths show archive and Studio links.

DNS at Hostinger: four A records for `@` to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; CNAME `www` to `visualizationcreation.github.io`; TTL 300. The www host redirects to the root domain.

Verified September 12, 2026: shared domain, HTTPS, archive entry, and 18 existing public project paths. No ORB content or media was copied or removed.
