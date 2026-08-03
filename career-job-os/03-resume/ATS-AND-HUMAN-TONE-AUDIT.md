# ATS + Human Tone Audit - Master Resume v2.0

**Date:** 2026-08-03  
**Apply files:** `MASTER-RESUME-BACKEND-v2.md`, `MASTER-RESUME-FULLSTACK-v2.md`, `LINKEDIN-COPY-v2.md`  
**Companion:** `RECRUITER-AND-AI-TELLS.md`  
**Method:** Recruiter-scan research (2025-2026 AI-tell patterns) + ATS checklist + Master Truth lock.  
Scores are calibrated estimates (vendor ATS tools disagree); checklist target is 95+.

---

## Scoreboard

| Lens | Backend v2 | Full Stack v2 | LinkedIn About v2 |
|---|---|---|---|
| ATS parse / keyword fit | **96 / 100** | **95 / 100** | N/A |
| Human recruiter skim | **88 / 100** | **87 / 100** | **90 / 100** |
| Sounds like a real person | **90 / 100** | **88 / 100** | **91 / 100** |
| AI-generated tell risk | **Low** | **Low** | **Low** |
| Generic template risk | **Low** | **Low** | **Low** |
| Trust / honesty | **93 / 100** | **92 / 100** | **93 / 100** |

### Why ATS is scored 95+

| Check | Status |
|---|---|
| Standard section headers | Pass |
| Single-column plain text | Pass |
| Keywords in Skills and Experience | Pass (Java, Spring Boot, Spring Data JPA, Python, REST APIs, Microservices, MySQL, PostgreSQL, ClickHouse, Redis, Kafka, RabbitMQ, AWS, Docker, Kubernetes, CI/CD, Git, Maven, Django, GraphQL, MongoDB; FS adds React, Redux, Angular, Highcharts) |
| Clear dates and titles | Pass |
| Contact + LinkedIn + GitHub | Pass |
| Measurable result present | Pass (60 / 40 percent) |
| No tables, icons, columns, white text | Pass |
| ASCII only (no special characters) | Pass |

Remaining 4-5 points reserved for unknown vendor quirks (degree not CS, optional JUnit not claimed).

---

## Story structure used

Each strong bullet follows: **context or problem -> action -> result or tool**.

Example (ClickHouse):
> Analytical queries on MySQL were too slow for the team. I led the migration to ClickHouse and completed the cutover. Query latency dropped about 60 percent and infrastructure cost dropped about 40 percent.

This is what recruiters remember. Tool lists alone are not.

---

## AI tells removed vs earlier drafts

| Removed | Why |
|---|---|
| Em dashes, arrows, tildes, bullet dots | Special characters banned; also AI formatting tells |
| spearheaded / leveraged / robust / seamless | Classic LLM verb/vocab cluster |
| Identical 5-bullet rhythm every role | Robotic symmetry |
| Skills restated as empty Summary | Sounds like a template |
| Naked GitLab URLs without titles (old FS) | Cold / bot-like |
| Company-wise identity rewrites | Deferred; destroys trust |

---

## Progression from v1.0 -> v1.1 -> v2.0

| Version | ATS | Human | Main change |
|---|---|---|---|
| v1.0 | ~84 | ~70 | Honest but dry |
| v1.1 | ~85 | ~80 | Warmer; still some special chars |
| **v2.0** | **95+** | **~88** | Story bullets, ASCII, AI-tell scrub, denser keywords |

---

## Still not doing (on purpose)

- Company-wise tailored resumes (later, emphasis-only)
- Fake metrics or Go/fraud identity
- Keyword stuffing white text
- Claiming JUnit/Jest unless Master Truth adds them

---

## Export rules (Overleaf)

1. Paste from v2 markdown body only (skip the instruction blockquote if it confuses layout)
2. One column, standard fonts
3. Hyphen `-` for bullets
4. Hyperlink LinkedIn, GitHub, GitLab MR labels to canonical URLs
5. Filename: `Pranjali-Sankpal-Resume-Backend.pdf` or `...-FullStack.pdf`
6. Before apply: diff against LinkedIn v2 and Master Truth
