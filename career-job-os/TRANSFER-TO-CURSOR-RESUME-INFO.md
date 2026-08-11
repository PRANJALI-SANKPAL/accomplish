# TRANSFER TO Cursor-resume-info (do this on your machine)

## Status from the cloud agent (2026-08-11)

**I cannot create or push to `Cursor-resume-info` from this environment.**

| Check | Result |
|---|---|
| Target repo exists? | No (or not visible to this token) |
| `gh repo create` | Failed: `Resource not accessible by integration` |
| Allowed repos for this agent | Only `PRANJALI-SANKPAL/accomplish` |
| Data lost? | **No** — full package is ready below |

Your Career Job OS is **not** lost. It lives in:
1. This export package (recommended for the new private repo)
2. GitHub branch on the fork: `cursor/resume-ats-human-audit-ccae` under `career-job-os/` (temporary; move off the open-source fork)

---

## What is in the export

- Full `career-job-os/` tree (106 files): truth, resumes v2.1, Overleaf tex, PDFs, prompts, trackers, source archives of all 10 old resumes, apply playbooks, etc.
- `CHAT-CONTINUITY.md` — paste into a new Cursor chat so the next agent continues without re-research
- This file — transfer steps

Artifacts (download from the cloud agent run if needed):
- `Cursor-resume-info-FULL.tar.gz`
- `Cursor-resume-info-FULL.zip`

---

## You do this (5–10 minutes)

### 1) Create the private repo on GitHub

In browser (logged in as **PRANJALI-SANKPAL**):

1. https://github.com/new
2. Owner: `PRANJALI-SANKPAL`
3. Name: `Cursor-resume-info`
4. **Private**
5. Do **not** add README/license if you will push the export as root
6. Create repository

### 2) Push the export as the repo contents

```bash
# download/unzip Cursor-resume-info-FULL.zip then:
cd repo-root   # folder that contains 00-read-first, 02-truth, 03-resume, ...
git init
git add .
git commit -m "Initial import: Career Job OS (from Accomplish fork export)"
git branch -M main
git remote add origin https://github.com/PRANJALI-SANKPAL/Cursor-resume-info.git
git push -u origin main
```

Or from the fork branch without the zip:

```bash
git clone https://github.com/PRANJALI-SANKPAL/accomplish.git
cd accomplish
git checkout cursor/resume-ats-human-audit-ccae
mkdir -p /tmp/Cursor-resume-info && cp -a career-job-os/. /tmp/Cursor-resume-info/
cd /tmp/Cursor-resume-info
git init && git add . && git commit -m "Initial import: Career Job OS"
git branch -M main
git remote add origin https://github.com/PRANJALI-SANKPAL/Cursor-resume-info.git
git push -u origin main
```

### 3) After the new repo has the files

1. Open a **new Cursor chat** attached to `Cursor-resume-info`
2. Paste `CHAT-CONTINUITY.md` (or say: read CHAT-CONTINUITY.md and AGENT-CONTRACT.md)
3. Optionally delete `career-job-os/` from the Accomplish fork so personal data is not on the public fork

### 4) Optional: remove from Accomplish fork

Only after you confirm the private repo has everything:

```bash
# on a cleanup branch of the fork — delete career-job-os/
# do NOT open this as a PR to upstream Accomplish
```

---

## Why the agent cannot finish the push

Cloud agent GitHub App token is scoped to `PRANJALI-SANKPAL/accomplish` only. It cannot create repos or push to unrelated remotes. A new chat with the private repo linked (or your local git credentials) can continue there.
