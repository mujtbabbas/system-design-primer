# Changelog

All notable changes to this standalone edition of system-design-primer are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates (the repo has no package manifests, so no language ecosystem applies).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — this repository's first workflow, since upstream ships none) for the guide and translations; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence note recorded: `LICENSE.txt` is Donne Martin's personal licence preamble plus the Creative Commons Attribution 4.0 International License (CC BY 4.0). Preserved exactly as-is.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) at upstream commit `ae9bbd7b02d90b9866215de185217d33f39ab733` (upstream HEAD dated 2026-03-19).
- Fork history severed; all files and the licence (`LICENSE.txt`, CC BY 4.0) preserved as-is, including all 79 binary images/diagrams/flash-card files.
