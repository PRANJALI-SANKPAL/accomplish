# How to run a session (human or agent)

## 30-second start

Copy this into a new agent chat:

```text
Read career-job-os/00-read-first/AGENT-CONTRACT.md
Read career-job-os/02-truth/MASTER-TRUTH.md
Read career-job-os/02-truth/FORBIDDEN-CLAIMS.md
Then open the matching prompt in career-job-os/06-prompts/ for my task:
TASK: <paste task name, e.g. TAILOR-RESUME-EMPHASIS-ONLY>
INPUT: <paste JD or details>
```

## Session types

| Goal | Prompt file |
|---|---|
| Score a JD fit | `06-prompts/01-SCORE-JD-FIT.md` |
| Tailor resume (safe) | `06-prompts/02-TAILOR-RESUME-EMPHASIS-ONLY.md` |
| Rewrite LinkedIn | `06-prompts/03-ALIGN-LINKEDIN.md` |
| Referral message | `06-prompts/04-WRITE-REFERRAL-ASK.md` |
| Log application | `06-prompts/05-LOG-APPLICATION.md` |
| Weekly review | `06-prompts/06-WEEKLY-REVIEW.md` |
| Company playbook | `06-prompts/07-APPLY-COMPANY-PLAYBOOK.md` |
| DSA day plan | `06-prompts/08-DSA-DAY-PLAN.md` |
| STAR story | `06-prompts/09-BUILD-STAR-STORY.md` |
| Interview debrief | `06-prompts/10-INTERVIEW-DEBRIEF.md` |
| Offer compare | `06-prompts/11-OFFER-COMPARE.md` |
| Fix rejected resume | `06-prompts/12-DIAGNOSE-REJECTION.md` |
| Update master truth | `06-prompts/13-UPDATE-MASTER-TRUTH.md` |
| Generate daily checklist | `06-prompts/14-DAILY-OPS.md` |
| Ban bad AI rewrite | `06-prompts/15-AUDIT-AI-RESUME.md` |
| Naukri/Instahyre copy | `06-prompts/16-PROFILE-COPY-NAUKRI-INSTAHYRE.md` |
| Salary scripts | `06-prompts/17-SALARY-SCRIPTS.md` |
| OA sprint | `06-prompts/18-OA-PREP-SPRINT.md` |
| Expand targets | `06-prompts/19-EXPAND-TARGET-LIST.md` |
| Archive old resumes | `06-prompts/20-ARCHIVE-OLD-RESUMES.md` |

## End of every session

1. Update `08-trackers/` if anything was applied/sent.
2. Append one line to `12-updates/CHANGELOG.md`.
3. If Master Truth changed, bump version in `02-truth/MASTER-TRUTH.md`.
