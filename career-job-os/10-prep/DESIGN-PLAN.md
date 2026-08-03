# LLD + HLD lite plan (2.5–3 YOE)

## LLD (higher priority than deep HLD at this level)

Learn:
- SOLID
- Strategy, Factory, Observer, Singleton (where appropriate), Builder
- Clean class modeling, concurrency basics

Practice designs:
- Parking Lot
- Rate Limiter
- Task Scheduler / Job Queue
- Splitwise-lite / Expense share
- URL Shortener (LLD view)
- Notification service

Method: requirements → entities → APIs/classes → concurrency → tradeoffs. Speak aloud.

## HLD (lite)

Concepts:
- Load balancing, caching, Redis patterns
- SQL vs NoSQL, indexing, replication, sharding basics
- Kafka use cases, idempotency, retries
- CAP, consistency, availability tradeoffs
- API gateway, authn/authz basics

Design drills:
- URL shortener
- News feed lite
- Payment/ledger lite (useful for fintech JD)
- Analytics ingestion → ClickHouse-style path (use your experience)

## Schedule

- Weeks 1–4: DSA primary, 1 LLD/weekend
- Weeks 5–8: 2 LLD + 1 HLD concept/week
- Weeks 9–12: mocks integrating design
