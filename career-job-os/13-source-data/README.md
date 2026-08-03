# SOURCE DATA PRESERVATION RULES

## Absolute rule for all agents/humans

**Never delete, overwrite, or “clean up” files under `13-source-data/`.**

- `13-source-data/` = **archive of everything the user provided** (and later extracts).
- `02-truth/MASTER-TRUTH.md` = **what is allowed to claim on public resumes/LinkedIn**.
- These are different layers. Conservatism in Master Truth must **not** erase raw history.

## Allowed operations on source data

| Action | Allowed? |
|---|---|
| Add new files / new versions dated | YES |
| Append to inventories / changelogs | YES |
| Mark claims as `CONFIRMED` / `DENIED` / `UNVERIFIED` | YES |
| Edit original resume archives in place | **NO** |
| Delete original resumes because they were “bad” | **NO** |
| Summarize by discarding unique claims | **NO** — extract into inventory instead |

## If Master Truth conflicts with an original resume

1. Keep the original resume file untouched.
2. Record the claim in `extracted-claims/ALL-CLAIMS-INVENTORY.md`.
3. Ask user to CONFIRM / DENY / EDIT.
4. Only then update Master Truth — **still keep the inventory row forever**.

## Low-context agent instruction

When context is small:
1. Do not assume missing source files are irrelevant.
2. Before discarding any skill/metric/project from user text, append it to the claims inventory.
3. Prefer “archive + flag” over “delete to simplify.”
