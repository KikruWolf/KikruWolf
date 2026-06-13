<h1 align="center">Hans Wolf</h1>
<p align="center">
  Software Developer · University of Malta · BSc Software Development (Hons)
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/hans-wolf-34781524a/">LinkedIn</a> ·
  <a href="mailto:hans.wolf.23@um.edu.mt">Email</a>
</p>

---

## About

Final-year software development student at the University of Malta with a background in management — running a hotel front desk at Duty Manager level taught me how to coordinate teams under pressure, handle the unpredictable, and get things done without losing quality. I bring that operational mindset into how I build software.

My technical interests split across two paths: **cybersecurity** as a career direction, and **quantum computing** as an academic one. I want to go deep in both.

---

## Thesis — Memetic Genetic Compiler for Approximate Quantum State Preparation

My final year project explores using a **memetic genetic algorithm** to compile approximate quantum circuits for state preparation on near-term hardware. The work covers:

- Circuit synthesis via evolutionary search with local optimisation
- Benchmarking against exact synthesis (Qiskit SBM) and LRSP across GHZ, W, Gaussian, and Haar-random state families
- Evaluation on IBM Fez (156-qubit heavy-hex architecture) under realistic noise conditions
- A hybrid fitness function balancing noiseless fidelity and noisy hardware performance

The codebase is public but was submitted under time constraints. Cleaning it up and extending the experiments is on my roadmap — I intend to revisit it once the summer build pipeline below gives me the engineering depth to do it properly.

→ [`Memetic-Quantum-Compiler-For-Approximate-State-Preparation`](https://github.com/KikruWolf/Memetic-Quantum-Compiler-For-Approximate-State-Preparation) *(cleanup planned post-pipeline)*

---

## Projects

| Project | Description | Stack |
|---|---|---|
| **GAPT — Fast Indexing Lookup Trie** | Sub-second full-text search on large corpora with paging, memory-aware layout, and a streaming API layer | Python, FastAPI |

---

## Summer 2026 Build Pipeline

Five projects in progress, sequenced by return on effort. Each one covers Python depth, HTTP fundamentals, FastAPI or Django, DevOps, and a security angle simultaneously — building toward a backend or junior security engineering role.

| # | Project | Track |
|---|---|---|
| 1 | **Authenticated API Gateway** | FastAPI · Redis · JWT · Auth abuse detection |
| 2 | **Vulnerable Django App & Security Audit** | Django · OWASP Top 10 · Formal audit report · Deployment |
| 3 | **Log Ingestion & Anomaly Detection Pipeline** | Python · Postgres · Rule-based detection · Alerting |
| 4 | **Zero-Trust Secrets Manager** | FastAPI · Fernet encryption · Postgres triggers · Threat model |
| 5 | **DAST Web Application Scanner** | Python CLI · HTTP · TLS inspection · CI integration |

**1 — Authenticated API Gateway**
A FastAPI service handling user auth, JWT issuance and rotation, per-user Redis rate limiting, and a custom abuse detection layer that flags brute force and credential stuffing patterns at the middleware level.

**2 — Vulnerable Django App & Security Audit**
A Django app deliberately built with OWASP Top 10 vulnerabilities — SQLi, IDOR, missing CSRF, hardcoded secrets — then formally audited and fixed. The deliverable is a structured vulnerability report alongside the clean deployment on a real VPS with Nginx and TLS.

**3 — Log Ingestion & Anomaly Detection Pipeline**
A Python pipeline that ingests real security log data (CICIDS dataset or Zeek logs), normalises it into Postgres, and runs configurable rule-based detection. Alerts fire via webhook. Detection rules live in YAML — adding a new rule means editing config, not code.

**4 — Zero-Trust Secrets Manager**
An encrypted-at-rest secrets store with service identity auth, secret rotation, and an append-only audit log enforced at the Postgres trigger level. Includes a written threat model documenting trust boundaries and attack surfaces.

**5 — DAST Web Application Scanner**
A Python CLI that runs automated security checks against targets I own — HTTP security headers, open redirect detection, SQLi parameter fuzzing, cookie flag analysis, TLS inspection. Packaged as an installable tool and wired into CI: the build fails if a High severity finding is detected.

Projects 1 and 5 are connected — the scanner runs against the gateway as a CI step, closing the loop between building secure services and verifying them programmatically.

---

## Stack

```
Languages   Python · C# · Java · JavaScript · SQL
Backend     FastAPI · Django · ASP.NET Core MVC · REST APIs
Mobile      Android (MVVM) · Room / SQLite
Databases   PostgreSQL · SQLite · SQL Server
DevOps      Docker · Docker Compose · GitHub Actions · Linux deployment
Practices   OOP · Git · Agile · TDD
Interests   Cybersecurity · Quantum Computing · Compilers
```

---

## Currently

- Finished BSc — Viva complete
- Building the Summer 2026 pipeline (above)
- Starting MSc in Information Systems at UM — October 2026
- Grinding LeetCode (NeetCode Blind 75 path)

---

<p align="center">
  <a href="https://www.linkedin.com/in/hans-wolf-34781524a/">LinkedIn</a>
</p>
