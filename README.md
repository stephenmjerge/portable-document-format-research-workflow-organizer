# Workflow Organizer

Glue repo containing automations, checklists, and shared assets that keep the other labs in sync. Expect:

- Scripts that update dashboards and aggregate LAUNCHPAD metrics.
- Templates for documenting experiments and decisions.
- Cross-repo helpers (e.g., shared GitHub Actions, data schemas).

Use `ROADMAP.md` for sequencing and keep the LAUNCHPAD folder handy for day-to-day execution.

## Checklists

`checklists/cross-repo-update.md` documents the weekly sweep that keeps
LAUNCHPAD, PortfolioHub, and each repo's README/ROADMAP aligned before pushing to
GitHub. Use it whenever you prep a public release.

## Scripts

Run `scripts/run_cross_repo_checklist.py` to perform a dry-run of the checklist
and confirm all planning docs exist before committing changes.

