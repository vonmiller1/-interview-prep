# 30-Day Java Backend Interview Roadmap

A guided checklist for building Java backend interview skills. Each day links to relevant study notes and suggests a concrete practice outcome; use the links as a starting point rather than a limit on what to study.

**Suggested pace:** 1–2 hours a day. If a topic needs more time, carry it forward instead of rushing to keep the calendar. For the subject index and study routine, see the [README](README.md).

## Week 1 — Core Java foundations

- [ ] **Day 1 — OOP fundamentals:** [OOP](01-core-java/oops.md), [Java basics](01-core-java/java-basics.md). Explain encapsulation, inheritance, polymorphism, and abstraction with examples.
- [ ] **Day 2 — Classes, objects, constructors, and `this`:** [Java basics](01-core-java/java-basics.md). Sketch a small class and explain its state, behavior, and constructor choices.
- [ ] **Day 3 — Inheritance and polymorphism:** [OOP](01-core-java/oops.md). Compare composition and inheritance; describe dynamic dispatch.
- [ ] **Day 4 — Interfaces, abstract classes, and SOLID:** [OOP](01-core-java/oops.md), [SOLID principles](01-core-java/solid-oop-design-principles.md). Apply one principle to a small design.
- [ ] **Day 5 — Strings and immutability:** [Strings](01-core-java/strings.md). Explain the string pool and when to use `StringBuilder`.
- [ ] **Day 6 — Collections:** [Collections](01-core-java/collections.md). Choose suitable list, set, and map types for a few use cases.
- [ ] **Day 7 — Hashing and equality:** [equals/hashCode](01-core-java/equals-hashcode.md). Explain how hash-based collections use both methods and practice a short review of the week.

## Week 2 — Advanced Java and Spring

- [ ] **Day 8 — Exception handling:** [Exception handling](01-core-java/exception-handling.md). Distinguish checked and unchecked exceptions and design a useful error boundary.
- [ ] **Day 9 — Generics and type safety:** [Generics](01-core-java/generics.md). Explain a generic type and when a bounded type parameter helps.
- [ ] **Day 10 — Lambdas and streams:** [Java 8 lambdas and streams](01-core-java/java-8-lambda-streams.md). Transform and group a small collection, then explain the pipeline.
- [ ] **Day 11 — Concurrency:** [Multithreading and concurrency](01-core-java/multithreading-concurrency.md). Describe a race condition and a way to prevent it.
- [ ] **Day 12 — JVM, memory, and garbage collection:** [JVM memory and GC](01-core-java/jvm-memory-gc.md). Trace stack and heap use in a simple example.
- [ ] **Day 13 — Spring Core and dependency injection:** [Dependency injection and IoC](03-spring-boot/03-dependency-injection-and-ioc.md). Explain how injection reduces coupling.
- [ ] **Day 14 — Spring Boot and configuration:** [Spring Boot fundamentals](03-spring-boot/01-spring-boot-fundamentals.md), [configuration and profiles](03-spring-boot/06-configuration-properties-and-profiles.md). Describe auto-configuration and how environment-specific settings are managed.

## Week 3 — APIs, persistence, and data

- [ ] **Day 15 — REST and HTTP fundamentals:** [REST API fundamentals](04-rest-api/01-rest-api-fundamentals.md), [HTTP methods and status codes](04-rest-api/02-http-methods-and-status-codes.md). Design a small resource API and choose its status codes.
- [ ] **Day 16 — Spring REST development:** [Spring Boot REST API development](03-spring-boot/07-rest-api-development.md). Trace a request through controller, service, and persistence layers.
- [ ] **Day 17 — Spring Data JPA and Hibernate:** [Spring Data JPA](03-spring-boot/08-spring-data-jpa.md), [Hibernate/JPA fundamentals](07-hibernate/01-hibernate-jpa-fundamentals.md). Explain entity state and repository responsibilities.
- [ ] **Day 18 — Transactions, fetching, and N+1 queries:** [Hibernate fetching](07-hibernate/03-fetching-lazy-eager-n-plus-one.md), [SQL transactions](05-sql/08-sql-transactions-acid.md). Identify a transaction boundary and how you would detect excess queries.
- [ ] **Day 19 — Security and JWT:** [Spring Security](03-spring-boot/10-spring-security.md), [JWT security](03-spring-boot/20-spring-boot-security-jwt.md). Explain authentication versus authorization and outline a token-based request.
- [ ] **Day 20 — SQL, joins, and subqueries:** [SQL fundamentals](05-sql/01-sql-fundamentals-and-database-basics.md), [joins](05-sql/04-sql-joins.md), [subqueries](05-sql/05-sql-subqueries-nested-queries.md). Write queries that combine and filter related records.
- [ ] **Day 21 — Indexes and query performance:** [Indexes and query performance](05-sql/07-sql-indexes-query-performance.md), [pagination and performance](05-sql/12-sql-pagination-performance-production.md). Explain how you would investigate a slow query.

## Week 4 — Distributed systems and interview practice

- [ ] **Day 22 — Microservices fundamentals:** [Microservices fundamentals](06-microservices/01-microservices-fundamentals.md). Discuss when splitting a service is useful and what complexity it adds.
- [ ] **Day 23 — API gateways and service discovery:** [Gateway and service discovery](06-microservices/04-microservices-service-discovery-api-gateway.md). Trace a request through a gateway to a service.
- [ ] **Day 24 — Kafka and event-driven architecture:** [Kafka and event-driven architecture](06-microservices/06-microservices-kafka-event-driven-architecture.md). Explain a producer-consumer flow and delivery concerns.
- [ ] **Day 25 — Redis and caching:** [Redis fundamentals](08-Redis/01-redis-fundamentals.md), [caching patterns](08-Redis/04-redis-caching-patterns-spring-boot.md). Pick a cache strategy and discuss invalidation.
- [ ] **Day 26 — Resilience and circuit breakers:** [Resilience patterns](06-microservices/05-microservices-resilience4j-circuit-breaker-retry-timeout-bulkhead.md). Explain the difference between retry, timeout, and circuit breaker.
- [ ] **Day 27 — System design fundamentals:** [System design fundamentals](10-system-design/01-system-design-fundamentals.md), [requirements and estimation](10-system-design/02-requirements-and-estimation.md). Clarify requirements and estimate a simple system before choosing components.
- [ ] **Day 28 — DSA revision:** [Arrays](02-dsa/01-arrays.md), [hashing](02-dsa/03-hashing.md), [trees](02-dsa/12-trees.md), [graphs](02-dsa/16-graphs.md), [dynamic programming](02-dsa/17-dynamic-programming.md). Solve a timed problem and explain complexity.
- [ ] **Day 29 — Project and behavioral discussion:** [Spring Boot real-world scenarios](03-spring-boot/17-spring-boot-real-world-scenarios.md), [project architecture](03-spring-boot/15-spring-boot-project-architecture-and-best-practices.md). Prepare a concise project story covering your contribution, trade-offs, and lessons learned.
- [ ] **Day 30 — Mock interview and final review:** [Core Java interview questions](01-core-java/core-java-interview-questions.md), [Spring Boot interview questions](03-spring-boot/16-spring-boot-interview-questions.md), [SQL mock scenarios](05-sql/15-sql-mock-interview-scenarios.md), [system design case studies](10-system-design/21-system-design-case-studies.md). Do a timed mock, record gaps, and schedule follow-up practice.

## Daily practice loop

1. Read the linked guide and write down the key idea in your own words.
2. Build or trace a small example; for DSA, solve at least one problem.
3. Explain the design, trade-offs, and likely follow-up questions aloud.
4. Revisit any gap before checking off the day.

## End-of-plan goals

By the end of the roadmap, aim to explain core Java clearly, design and discuss a Spring Boot API, reason about persistence and SQL performance, describe common distributed-system trade-offs, solve representative DSA problems, and present a project with concrete decisions and lessons learned.