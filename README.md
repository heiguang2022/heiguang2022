# Jinlong He

### Java Backend Security & Reliability Engineer

I build and improve Java/Spring Boot backends that need more than generated code: secure authentication, reliable data changes, reproducible tests, deployment-ready packaging, and clear technical handoff.

My focus is existing systems and business-critical backend work—understanding the current behavior, isolating risk, implementing a scoped change, and verifying the result with executable evidence.

## What I deliver

- Spring Boot REST APIs and backend feature development
- Spring Security, JWT authentication, refresh-token rotation, and RBAC
- MySQL/PostgreSQL migrations, validation, idempotency, and SQL analysis
- Bug diagnosis, structured error handling, and regression protection
- JUnit/MockMvc integration tests and GitHub Actions CI
- Docker Compose environments, OpenAPI documentation, and reproducible handoff

## Selected engineering evidence

### [Spring Security JWT & RBAC API](https://github.com/heiguang2022/spring-security-jwt-rbac-api)

Security-focused Spring Boot API with short-lived access tokens, rotating refresh tokens, replay rejection, BCrypt password hashing, USER/ADMIN authorization, structured `401`/`403` responses, MySQL, Docker, OpenAPI, CI, and nine integration tests.

### [Java Database Migration & SQL Optimizer](https://github.com/heiguang2022/java-database-migration-optimizer)

Resumable MySQL-to-PostgreSQL migration with transactional checkpoints, idempotent upserts, failure recovery, row-count and SHA-256 validation, SQL `EXPLAIN` comparison, Docker Compose, CI, and integration tests.

### [Spring Boot Inventory API](https://github.com/heiguang2022/spring-boot-inventory-api)

Inventory REST API demonstrating validation, normalized SKU rules, duplicate protection, optimistic locking, consistent errors, H2/MySQL profiles, Docker, OpenAPI, CI, and end-to-end MockMvc tests.

### [E-commerce Product Data Automation](https://github.com/heiguang2022/ecommerce-product-data-automation)

Tested Python workflow that converts inconsistent supplier CSV/XLSX catalogs into Shopify-ready imports and formatted QA reports, with deterministic normalization, validation, deduplication, and traceable output rules.

## Delivery principles

1. Reproduce and define the problem before changing code.
2. Keep the implementation within an agreed scope.
3. Protect security and data integrity with explicit rules.
4. Verify behavior through tests, HTTP flows, database checks, or runtime evidence.
5. Deliver documentation and a setup another developer can reproduce.

## Current stack

`Java 17` · `Spring Boot` · `Spring Security` · `JWT/RBAC` · `REST/OpenAPI` · `JUnit/MockMvc` · `MySQL` · `PostgreSQL` · `Docker Compose` · `GitHub Actions` · `Python`

Available for focused Spring Boot diagnosis, backend security work, database migration, API development, and deployment-ready delivery.
