# Study Paths

**Live: [kingpingx.github.io/azure-study-path](https://kingpingx.github.io/azure-study-path/)**

Phase-by-phase learning checklists for a C#/.NET, PostgreSQL, and Angular developer.
Six tabs, 59 phases, 444 items — each tab tracks its own progress.

## Usage

Open the [live page](https://kingpingx.github.io/azure-study-path/) and check items off as
you go, or open `index.html` directly in a browser to use it offline. Progress is saved per
tab in that browser's local storage.

Phases tagged **Core focus** and items tagged **Deep dive** are the ones worth studying
beyond the surface. Each tab has its own accent colour.

## The tabs

| Tab | Phases | Items | What it covers |
| --- | ---: | ---: | --- |
| **Azure** | 14 | 89 | One cloud in depth, for the .NET stack |
| **Java** | 16 | 138 | Language, Spring, persistence, security, delivery |
| **Distributed Systems** | 9 | 68 | Failure, consistency, replication, consensus, resilience |
| **Scaling** | 7 | 57 | Measurement, caching, the database ladder, load management |
| **Event-Driven** | 8 | 59 | Kafka, delivery guarantees, schemas, outbox/CDC/saga/CQRS |
| **System Design** | 5 | 33 | A repeatable method and problems to work end to end |

The last four tabs are language-neutral — they apply equally to the .NET work you do today
and the Java work you are moving toward. Where a concept has a concrete implementation, the
implementation lives in the language tab and the thinking lives in the systems tab:

- Redis and Spring Cache mechanics are in **Java**; cache patterns, stampedes and
  invalidation strategy are in **Scaling**.
- `@KafkaListener`, outbox wiring and consumer tests are in **Java**; broker semantics,
  schema evolution and the integration patterns are in **Event-Driven**.
- Postgres engine internals are in **Java**; replicas, partitioning and sharding are in
  **Scaling**.

Two tabs open with a collapsible translation table: **Java** maps each .NET tool to its Java
counterpart, and **Event-Driven** maps Azure and .NET messaging to the Kafka/OSS stack.

## Notes

The repository name predates the other five tabs. Everything lives in `index.html`, a single
self-contained file — no build step, no dependencies beyond a webfont.
