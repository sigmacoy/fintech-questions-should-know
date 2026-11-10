# Fintech Questions Every Software Engineer Should Know

> Production-first questions, mental models, and architectural patterns for Fintech, Payments, and Core Banking Backend Engineers.

Fintech engineering is defined by **exactness, zero data loss, concurrency safety, and auditability**. In general web development, an eventual consistency delay or dropped request is a minor bug; in financial software, it is an accounting discrepancy, a compliance breach, or lost capital.

This repository covers the foundational systems concepts, payment rails, distributed transaction guarantees, and accounting mechanics required to build production financial infrastructure.

---

## Table of Contents

- [01. Money Representation & Accounting Ledgers](docs/01-money-representation-and-accounting-ledgers.md) — Integer math, precision, double-entry bookkeeping, immutability, balance types.
- [02. Payment Rails, Clearing & Settlement](docs/02-payment-rails-clearing-and-settlement.md) — Auth vs. capture vs. settle, ACH, FedNow/SEPA/SWIFT, card network lifecycles.
- [03. Distributed Transactions & Idempotency](docs/03-distributed-transactions-and-idempotency.md) — Two-phase commit vs. sagas, idempotency keys, race conditions, replay attacks.
- [04. Reconciliation & Auditability](docs/04-reconciliation-and-auditability.md) — 2-way and 3-way matching, break queues, journal generation, ledger integrity.
- [05. Compliance, Auth & Banking APIs](docs/05-compliance-auth-and-banking-apis.md) — ISO 20022, Open Banking (FAPI/OAuth2), PCI-DSS tokenization, KYC/AML data isolation.
- [06. Fraud, Risk & Rate Limiting](docs/06-fraud-risk-and-rate-limiting.md) — Velocity checks, token bucket algorithms, chargeback mechanics, risk scoring pipelines.

---

## Related Repositories

- [applied-ai-questions-should-know](https://github.com/sigmacoy/applied-ai-questions-should-know) — Production AI, embeddings, RAG, and inference systems.
- [hardware-questions-for-cs](https://github.com/sigmacoy/hardware-questions-for-cs) — Silicon architecture, cache lines, memory hierarchies, and mechanical sympathy.
- [cs-questions-should-know](https://github.com/sigmacoy/cs-questions-should-know) — Algorithms, operating systems, and distributed computing fundamentals.