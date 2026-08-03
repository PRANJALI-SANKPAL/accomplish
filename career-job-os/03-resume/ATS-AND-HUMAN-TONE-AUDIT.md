# ATS + Human Tone Audit — Master Resume v1.0

**Date:** 2026-08-03  
**Files audited:** `MASTER-RESUME-BACKEND-v1.md`, `MASTER-RESUME-FULLSTACK-v1.md`, `LINKEDIN-COPY-v1.md`  
**Method:** Manual ATS checklist (India product/fintech 2026 patterns) + recruiter skim test + comparison vs archived Adobe / GROWW / JPMC versions.  
**Not** a paid ATS scanner score (those vary by vendor). Treat scores as calibrated estimates.

---

## Scoreboard (v1.0 before human-touch pass)

| Lens | Backend v1 | Full Stack v1 | LinkedIn About |
|---|---|---|---|
| **ATS parse / keyword fit** | **84 / 100** | **82 / 100** | N/A (not ATS) |
| **Human recruiter skim (6 sec)** | **72 / 100** | **70 / 100** | **78 / 100** |
| **Sounds like a real person** | **68 / 100** | **66 / 100** | **80 / 100** |
| **Generic / template risk** | Medium | Medium–High | Low–Medium |
| **Trust / honesty** | **92 / 100** | **90 / 100** | **92 / 100** |
| **Shortlist readiness (honest)** | **B** | **B−** | **B+** |

**Bottom line:** ATS is **good enough**. Human tone is **safe but dry** — credible, not memorable. They do **not** sound like the old over-tailored AI resumes (good), but they **do** sound a bit template-generic (fixable without inventing skills).

---

## 1) ATS — what the score means

### What ATS likes in your v1 (keep)

| Check | Backend | Full Stack |
|---|---|---|
| Standard section headers (Summary, Skills, Experience, Education) | Pass | Pass |
| Plain text–friendly (no tables/columns in source) | Pass | Pass |
| Job titles + company + dates on one line | Pass | Pass |
| Core keywords: Java, Spring Boot, Python, REST, Kafka, Docker, AWS, PostgreSQL/MySQL | Pass | Pass |
| ClickHouse + measurable result (rare + scannable) | Pass | Pass |
| Certifications listed | Pass | Pass |
| Contact + LinkedIn/GitHub | Pass | Pass |
| No graphics / icons required | Pass | Pass |

### ATS gaps (minor)

| Gap | Impact | Fix |
|---|---|---|
| Few exact phrases like `Spring Data JPA`, `microservices`, `CI/CD` inside bullets (mostly in skills) | Small | Sprinkle once in experience (truth-safe) |
| Full Stack Open Source = naked URLs only | Human + ATS title miss | Add MR titles (like Backend) |
| No `JUnit` / testing keywords | Small for some banks | Add only if true in Truth later |
| Aerospace degree may confuse keyword bots looking for “CS” | Low | Leave — humans often like it; don’t fake CS |

### Estimated keyword match vs common India SDE JDs

| JD family | Backend ATS fit | Notes |
|---|---|---|
| Java Spring Boot 2–4 YOE fintech | **High (85–90)** | Your strongest lane |
| Full stack Java + React | **High (80–85)** with FS resume | Use FS PDF |
| Kafka / event-driven | **Medium–High** | Present but thin story |
| Pure frontend | Low | Don’t use Backend PDF |
| Go / networking / fraud specialist | Fail by design | Correct — skip those JDs |

**Verdict:** You do **not** need keyword stuffing. ATS will not be your main failure mode if PDFs stay one-column and match LinkedIn.

---

## 2) Human tone — does it sound generic?

### What a recruiter hears in 6 seconds (v1.0)

> “Backend engineer, Java/Spring/Python, fintech, ClickHouse win, some Kafka, GitLab MRs. Clean. A bit bland.”

### Generic signals present (yes)

1. **Tool-list bullets** — “using Java (Spring Boot) and Python…” repeats stack instead of problem.
2. **Verb monoculture** — Built / Designed / Delivered / Led over and over.
3. **Summary = skills restated** — reads like LinkedIn keyword soup, not a person.
4. **Selected Systems duplicates Experience** — feels like filler for length.
5. **“production debugging, Agile delivery”** — empty corporate phrases.
6. **Full Stack Open Source** — URLs without names = cold / bot-like.

### What does NOT sound generic (keep / lean into)

| Element | Why it feels human |
|---|---|
| MySQL → ClickHouse with ~60% / ~40% | Specific, owned, memorable |
| Futuroot named product | Real workplace, not “a fintech client” |
| KM-Intelligence + Malaysia client | Concrete client context |
| Demand Planning Platform (banking) | Named system |
| Named GitLab MR titles (Backend) | Proof you touched a real codebase |
| Aerospace → software path | Distinctive (don’t hide) |

### Comparison to your old tailored resumes

| Version | Human spark | Trust | Net |
|---|---|---|---|
| GROWW (old) | High energy (“ownership”, “startup velocity”) | **Low** — inflated metrics/SLAs | Reject risk |
| Adobe (old) | Medium — more Core Java story | Medium — some fluff (multithreading in every bullet) | Better base |
| JPMC (old) | Medium — “Member Money Movement”, design review | Medium — AI-tools line + scale claims | Mixed |
| **Master v1.0** | **Lower spark** | **Highest trust** | Right strategy; needs voice |

**You traded fake personality for honesty.** Correct. Next step is **real personality from real work**, not AI swagger.

---

## 3) “Human touch” checklist

| Question | v1.0 answer |
|---|---|
| Could this resume belong to 1,000 other Java engineers after removing your name? | **Partly yes** — except ClickHouse + Futuroot + GitLab MRs |
| Does it show *how you think* (diagnose → decide → ship)? | **Only on ClickHouse** |
| Does it over-tailor per company? | **No** (good — that was the old failure) |
| Does LinkedIn sound more human than the PDF? | **Yes** — About is warmer than resume Summary |
| Would a hiring manager remember you tomorrow? | **Maybe** for ClickHouse; **unlikely** for rest |

---

## 4) What to change (without inventing)

Safe upgrades (applied in human-touch pass → treat as v1.1 content):

1. Rewrite Summary as 3 short sentences: who → signature win → prior lane.
2. Open ClickHouse bullet with **diagnosed / led** (problem → action → result).
3. Name products once per section; cut duplicate Selected Systems fluff or make each line *one* unique proof.
4. Give Full Stack the same MR titles as Backend.
5. Soften corporate filler; keep mentoring without fake headcount.
6. Keep dual PDF strategy — do **not** return to per-company identity rewrites.

Do **not** add back: 99.9% uptime, millions of transactions, sub-ms, Go expert, fraud expert, “architecture discussions” cosplay, mentee counts unless re-confirmed.

---

## 5) Scores after human-touch pass (v1.1)

| Lens | Backend v1.1 | Full Stack v1.1 |
|---|---|---|
| ATS parse / keyword fit | **85 / 100** | **84 / 100** |
| Human recruiter skim | **82 / 100** | **81 / 100** |
| Sounds like a real person | **80 / 100** | **79 / 100** |
| Generic / template risk | Low–Medium | Low–Medium |
| Trust / honesty | **92 / 100** | **91 / 100** |

Files: `MASTER-RESUME-BACKEND-v1.1.md`, `MASTER-RESUME-FULLSTACK-v1.1.md`

---

## 6) How to use with applications

- **Default PDF:** Backend human-touch version  
- **FE-heavy JD:** Full Stack human-touch version  
- **Emphasis only:** bold/reorder existing true bullets — never new identity  
- **ATS tip:** export Overleaf as text-selectable PDF; avoid multi-column templates  

Related: `AUDIT-VERDICT.md` (old set failed trust). This file audits the **new masters only**.
