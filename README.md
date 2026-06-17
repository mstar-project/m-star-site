# m-star-site

Auto-generated mirror of the M\* website, served at **https://m-star.org/**.

**Do not edit this repo by hand.** It is rebuilt by the *Mirror site to m-star.org*
workflow from two upstream sources:

- **Blog** — [`mstar-project/mstar-project.github.io`](https://github.com/mstar-project/mstar-project.github.io) (`main`) → served at the root (`/`)
- **Docs** — [`mstar-project/mstar`](https://github.com/mstar-project/mstar) (`gh-pages`) → served under `/mstar/`

Edit content in those repos. The mirror refreshes hourly; for an immediate sync,
run the workflow manually (**Actions → Mirror site to m-star.org → Run workflow**).

The same content is served at https://mstar.stanford.edu/ directly from the upstream
repos. This repo exists only to serve the second domain (`m-star.org`); its `CNAME`
is therefore `m-star.org` and is preserved across mirror runs.
