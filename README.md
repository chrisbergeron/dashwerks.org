---
id: db63a8dc-368b-48e0-91ba-3b11d632a3f1
slug: dashwerks-org-repo-cleanup
entity: holdingco
---

# dashwerks.org

Archive site for **Dashwerks, Inc.** — the (now defunct) company behind
[DashPC](https://dashpc.org), the world's first automotive infotainment
system, and related projects (DSSC startup/shutdown controller, Dashboard
Linux, and other builds).

## Hosting

Static site served by **GitHub Pages** from the `master` branch of this
repo, with the custom domain configured via the `CNAME` file. DNS for
`dashwerks.org` is hosted at DigitalOcean:

- apex `A` records → GitHub Pages IPs (185.199.108–111.153)
- `www` `CNAME` → `chrisbergeron.github.io`

## History

The site was generated with Hexo + the Metronic theme in 2020; only the
compiled output lives here. In 2026 the repo was cleaned up (junk files,
theme placeholder content, and dead links removed) and moved onto GitHub
Pages after the previous origin server stopped serving it.
