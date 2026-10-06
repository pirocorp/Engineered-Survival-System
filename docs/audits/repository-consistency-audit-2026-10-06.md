# Repository consistency audit — progress log

Started: 2026-10-06
Branch: `audit/internal-consistency-2026-10-06`
Base: `main`

## Scope

- [x] Inventory every repository file.
- [ ] Validate every internal Markdown/file/image link against repository paths.
- [ ] Validate asset manifests against actual image filenames and episode references.
- [ ] Review every text file for internal consistency.
- [ ] Review consistency across episode notes, evidence files, evidence ledger, open questions, README and CURRENT_STATE.
- [ ] Correct confirmed consistency defects.
- [ ] Re-run repository-wide link/reference checks after edits.
- [ ] Produce final audit summary and pull request.

## Inventory

- 439 files total
- 172 Markdown files
- 1 TXT file
- 264 image files
- 2 extensionless text files (CODEOWNERS, LICENSE)

## Working rules

1. Preserve factual uncertainty: do not turn hypotheses into facts merely to make prose look consistent.
2. Prefer the most specific evidence record when two summaries disagree.
3. Fix broken/mis-pointed internal links without renaming image assets unless necessary.
4. Record any ambiguous conflict that cannot safely be resolved from the repository alone.
5. Re-check all modified files and all inbound references before opening the PR.

## Current status

Inventory complete. Link/reference validation is next.
