# OCG LAB — Public Website

The public website of OCG LAB: marketing pages, product microsites, and the
public OS mirror served by GitHub Pages.

This repository was separated from the private engineering repository
(`TheOCGroup/ocg-lab-site`) on 2026-10-30 so the engineering codebase could
go private without disrupting public access. It contains only approved
public website assets — no source code, tests, credentials, or operational
records.

**Keeping it current:** run `scripts/sync-website-repo.mjs` from a checkout
of `ocg-lab-site` (see `SYNC.md`) — it mirrors the approved public surface
from `main` into a checkout of this repository for review and commit.
