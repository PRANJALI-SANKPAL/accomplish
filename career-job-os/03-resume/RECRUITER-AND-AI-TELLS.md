# Recruiter lens + AI-tell avoidance (apply to every resume edit)

## What recruiters actually scan (first 6-10 seconds)

1. Title fit (Backend / Full Stack / Software Engineer) and YOE band
2. One concrete win they can remember (your ClickHouse migration)
3. Recent company + product names (Percipere / Futuroot, Valiance)
4. Stack match to the JD (Java, Spring Boot, Python, not invented Go/fraud)
5. Clean dates, location, contact, LinkedIn/GitHub match
6. Proof links if present (GitLab MRs)

If those pass, they read bullets for: problem, what you did, result, tools used.

## AI-generated resume tells to avoid (2025-2026)

Do not use these patterns in public resumes or LinkedIn:

| Tell | Examples to ban |
|---|---|
| AI verb pile | spearheaded, leveraged, orchestrated, utilized, pioneered |
| AI vocab | robust, seamless, pivotal, intricate, delve, realm, synergistic, cutting-edge, results-driven |
| Em dash epidemic | long em dashes everywhere (also banned by ASCII rule here) |
| Perfect bullet symmetry | every role has exactly 5 bullets of identical rhythm |
| Round fake metrics | 30%, 50%, 99.9% with no story |
| JD parrot | pasting JD phrases into every bullet |
| Empty soft lines | passionate engineer, continuous learner, wearing many hats |
| Cross-doc mismatch | resume says X, LinkedIn says Y |

## What we do instead

- First person in Summary only if it sounds natural; bullets can mix I / plain past tense
- Named products and clients (Futuroot, Demand Planning, KM-Intelligence, Malaysia client)
- Uneven bullet lengths (humans are not templates)
- Simple verbs: build, write, fix, move, lead, ship, help, add, tune, review
- Real metrics only from Master Truth (about 60 percent / about 40 percent)
- ASCII only: letters, numbers, spaces, and . , ; : / ( ) - + @ |

## ATS 95+ checklist (run before export)

- [ ] Standard headers: Summary, Technical Skills, Experience, Education, Certifications
- [ ] Single column, selectable text PDF (Overleaf), no tables/icons/graphics
- [ ] Keywords present in Skills AND naturally in Experience: Java, Spring Boot, Spring Data JPA, Python, REST APIs, Microservices, MySQL, PostgreSQL, ClickHouse, Redis, Kafka, RabbitMQ, AWS, Docker, Kubernetes, CI/CD, Git, Maven, Django, GraphQL, MongoDB (and React/Angular/Highcharts on Full Stack)
- [ ] Dates as Mon YYYY - Mon YYYY or Present
- [ ] Job titles readable by parsers on their own line/block
- [ ] No special characters (no bullet dots, em dashes, arrows, tildes)
- [ ] No white-text / hidden keyword stuffing
- [ ] Matches LinkedIn facts and Master Truth

## Company-wise tailoring

Not in this pass. Later: emphasis-only reorder of true bullets (prompt 02), never a new identity.
