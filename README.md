# Test_Drafted_Github_Actions

Demo repo for C2: GitHub Actions automation of the AI Vista release lifecycle
(release check → intake → PR checks → approval → deploy → record/notify → drift check).

Uses dummy values (`DEMO_MODE=true`). Will move to the AIUNITPE organisation later.

| Path | Purpose |
|---|---|
| `.github/workflows/` | Workflow files |
| `.github/CODEOWNERS` | Who must review changes |
| `scripts/` | Helper scripts (e.g. release comparison) |
| `l1.lock` | Pinned AI Vista release currently installed |
