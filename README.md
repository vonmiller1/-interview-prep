<div align="center">

# Java Backend Interview Prep

**Structured study notes and a 30-day roadmap for Java backend developer interviews.**

<img src="./assets/java-backend-roadmap.png" alt="Java Backend Interview Prep Roadmap">

</div>

## Overview

This repository is a **documentation-only** learning path for backend interviews. It collects markdown guides on Core Java, data structures, Spring Boot, REST, SQL, microservices, Hibernate/JPA, Redis, Docker, and system design. Content is organized by topic folders with deep-dive notes, interview questions, and scenario walkthroughs—intended for self-study rather than as a runnable application.

There is no build step: clone the repo and read the guides locally or on GitHub. Hands-on practice (small Java/Spring projects, LeetCode-style problems) is recommended alongside the notes but is not bundled here.

## Features

- **30-day roadmap** ([ROADMAP.md](ROADMAP.md)) with daily links and practice outcomes
- **Core Java** — OOP, collections, concurrency, JVM, generics, streams, interview Q&A
- **DSA** — arrays, hashing, trees, graphs, dynamic programming, and common patterns
- **Spring Boot** — IoC, REST, JPA, security, testing, production readiness
- **REST APIs** — HTTP semantics, validation, pagination, security, OpenAPI-style documentation
- **SQL** — queries, joins, transactions, indexes, performance, Spring/JPA integration
- **Microservices** — boundaries, discovery, resilience, Kafka, observability, deployment
- **Hibernate/JPA** — mapping, fetching, N+1, transactions, troubleshooting
- **Redis** — structures, caching, locks, pub/sub, clustering
- **Docker** — images, Compose, Spring Boot containerization, security
- **System design** — scalability, CAP, messaging, case studies

## Tech stack

| Layer | Technology |
| --- | --- |
| Content | Markdown (`.md`) |
| Version control | Git |
| Hosting | GitHub (static files) |
| Optional practice | JDK 17+ (LTS), Maven or Gradle, Spring Boot 3.x, Docker, PostgreSQL/MySQL, Redis |

Concepts in the guides reference common backend stacks (Spring Boot, JPA, JWT, Kafka, etc.); versions are described in the relevant topic files, not pinned in a single build file.

## Prerequisites

- **Required:** Git and a Markdown viewer (IDE, VS Code, or GitHub web UI)
- **Recommended for labs:** JDK 17 or later, Docker Desktop (or Docker Engine), and a local SQL database when following SQL/Spring examples in the guides
- **No** Node, Python, or Maven install is required **to read** this repository

## Getting started

```bash
git clone https://github.com/vonmiller1/-interview-prep.git
cd -interview-prep
```

1. Open [ROADMAP.md](ROADMAP.md) if you want a day-by-day plan.
2. Otherwise pick a track from [Study guides](#study-guides) below.
3. For each topic, use the study loop in [A practical study loop](#a-practical-study-loop).

There are **no environment variables or secrets** required to use this repo. Example connection strings in the guides are illustrative only—never commit real credentials.

## Running locally

This project is not an application. “Running locally” means opening markdown files:

- **VS Code / Cursor:** open the repo folder and use Markdown preview.
- **GitHub:** browse files at `https://github.com/vonmiller1/-interview-prep`.

Optional: serve static files with any static server (e.g. `python -m http.server`) if you prefer a local browser view; default port depends on the tool you choose.

## Testing

There is **no automated test suite** in this repository. When preparing for interviews, run your own Java/Spring tests in separate practice projects. Topic files under `03-spring-boot/` describe how testing is typically done in Spring Boot applications.

## Project structure

```text
-interview-prep/
├── README.md                 # This file
├── ROADMAP.md                # 30-day study checklist
├── assets/                   # Diagrams (e.g. roadmap image)
├── 01-core-java/             # Java language and JVM topics
├── 02-dsa/                   # Data structures and algorithms
├── 03-spring-boot/           # Spring Boot guides and interview Q&A
├── 04-rest-api/              # REST and HTTP
├── 05-sql/                   # SQL and database topics
├── 06-microservices/         # Microservices architecture
├── 07-hibernate/             # JPA/Hibernate
├── 08-Redis/                 # Redis usage patterns
├── 09-Docker/                # Containerization
└── 10-system-design/         # System design fundamentals and cases
```

## Configuration

Not applicable for the documentation itself. Guides mention typical Spring `application.yml` / profile names and Docker Compose service names where relevant; copy those patterns into your own practice projects rather than expecting config files in this repo.

## Deployment

The canonical deployment is **GitHub**: push to `main` and read on the web. You may fork the repo or enable GitHub Pages for a static site; no Dockerfile or CI workflow is included in this repository.

## Study guides

| Area | Entry guide |
| --- | --- |
| [Core Java](01-core-java/java-basics.md) | OOP, strings, collections, exceptions, generics, streams, concurrency, JVM |
| [Data structures and algorithms](02-dsa/01-arrays.md) | Arrays, hashing, trees, graphs, dynamic programming |
| [Spring Boot](03-spring-boot/01-spring-boot-fundamentals.md) | DI, REST, JPA, security, testing, production |
| [REST APIs](04-rest-api/01-rest-api-fundamentals.md) | HTTP, design, validation, security, pagination |
| [SQL](05-sql/01-sql-fundamentals-and-database-basics.md) | Queries, joins, transactions, indexes, performance |
| [Microservices](06-microservices/01-microservices-fundamentals.md) | Services, communication, resilience, messaging |
| [Hibernate and JPA](07-hibernate/01-hibernate-jpa-fundamentals.md) | Mapping, fetching, transactions |
| [Redis](08-Redis/01-redis-fundamentals.md) | Structures, caching, coordination |
| [Docker](09-Docker/01-docker-fundamentals.md) | Images, Compose, Spring Boot containers |
| [System design](10-system-design/01-system-design-fundamentals.md) | Requirements, scale, reliability, case studies |

## A practical study loop

For each topic:

1. Read the guide and note concepts you cannot explain without the page.
2. Write or trace a small example, or solve a related coding problem.
3. Explain trade-offs and likely follow-up questions aloud.
4. Mark the roadmap item complete only when you can teach the idea to someone else.

You can follow [ROADMAP.md](ROADMAP.md) sequentially or jump via the table above to close a specific interview gap.

## Contributing

Contributions are welcome via fork and pull request:

1. Fork the repository and create a branch from `main`.
2. Keep changes focused (one topic or fix per PR when possible).
3. Use clear commit messages (e.g. `docs(spring): clarify bean scopes`).
4. Do not add secrets, personal data, or copyrighted material without permission.

## License

No `LICENSE` file is present in this repository at this time. Treat content as the author’s study notes; contact the repository owner before redistributing commercially. If you add a `LICENSE` file in a fork, document it here.
