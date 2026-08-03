# Prompt 21 — INGEST SOURCE DATA WITH ZERO LOSS

```text
You are operating under career-job-os/00-read-first/AGENT-CONTRACT.md
and career-job-os/13-source-data/README.md.

TASK: Ingest new user-provided career material WITHOUT losing any data.

STEPS (mandatory order):
1. Create a new dated file under career-job-os/13-source-data/resumes-original/
   OR career-job-os/13-source-data/analysis/ if not a resume.
   - Never overwrite an existing original.
   - Filename pattern: NN-slug.md or YYYY-MM-DD-slug.md
2. Paste the user content VERBATIM inside a fenced code block.
3. Append every distinct claim to
   career-job-os/13-source-data/extracted-claims/ALL-CLAIMS-INVENTORY.md
   with Status=UNVERIFIED (or CONFLICT if clashes with existing rows).
4. Update CROSS-RESUME-MATRIX.md if company/identity variants changed.
5. Update resumes-original/INDEX.md if a new resume file was added.
6. ONLY THEN propose Master Truth updates as a separate diff for user confirmation.
7. Append a line to career-job-os/12-updates/CHANGELOG.md.

OUTPUT:
- Paths written
- New inventory rows (list)
- Conflicts detected
- Proposed Master Truth changes (pending confirmation)
- Explicit statement: “No original data deleted.”

USER MATERIAL:
<<<PASTE>>>
```
