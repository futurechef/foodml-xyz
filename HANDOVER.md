# Handover — foodml-xyz

<!-- QUICK-STATUS:START -->
## ⚡ Quick Status
- **Last session:** 2026-10-10
- **Branch / state:** `claude/new-web-app-xeuoi6` → PR into `main`. GitHub Pages builds `main` (CNAME foodml.xyz), but foodml.xyz DNS currently points at Porkbun static hosting (`pixie-sh`, frozen 2026-07-17) — merging alone may not update the live site. Fix: Porkbun DNS A → 185.199.108–111.153, CNAME www → futurechef.github.io, then Pages → Enforce HTTPS.
- **What changed this session:** "Things I build" section (#projects): ForkRecipe, alcheMISE, Platedraw cards with images in `img/`, plus a strip for the open dataset, ForkCard (on the bench, no public URL) and the Coding Cuisine blog. Canonical + og:image.
- **Next actions:** user switches foodml.xyz DNS to GitHub Pages, then merges this PR; foodml.ai → Porkbun URL Forwarding 301 to https://foodml.xyz (decided 2026-10-10: forward for now; .xyz stays primary).
- **Blockers / open questions:** both are user-side Porkbun changes.
<!-- QUICK-STATUS:END -->

## Reference
FoodML static site — landing page (`index.html`) + `wireframes.html`.
