# Synchronization

The website surface in this repository mirrors the approved public files on
`main` of `TheOCGroup/ocg-lab-site` (marketing pages, microsites, and the
built `os/` mirror — never `os/source`, tests, or internal records).

To refresh: from a checkout of `ocg-lab-site`, run

    node scripts/sync-website-repo.mjs /path/to/ocg-lab-website-checkout

then review the diff in this repository and commit. Automated cross-repo
pushes require a dedicated credential (deploy key or fine-grained token
scoped to this repository only) — a founder credential decision, not
configured by default.
