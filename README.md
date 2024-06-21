Lean repository index
=====================

This repository fills <https://release.lean-lang.org/> with JSON files listing
the lean releases.

It is updated upon new Lean releases (stable, beta, nightly; but not PR
releases) using a GitHub Actions `workflow_dispatch` event. If it stopped working maybe the PAT expired? Then create a new one and set a secret on the lean4 repo.

URLs:

* <https://release.lean-lang.org/> lists all releases, grouped by release channel.
* <https://release.lean-lang.org/stable.json> lists all stable releases.
* <https://release.lean-lang.org/beta.jon> lists all beta releases.
* <https://release.lean-lang.org/nightly.jon> lists all nightly releases.

Since there are many nightly releases (about one every night), the
`stable.json` is noticably smaller and should be used if it suffices.
