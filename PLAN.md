# CS407 — DBMS Project Lab — PLAN

**Semester:** 4 · **Credits:** 2 · **Level:** Intermediate-Advanced
**Theory:** 15 hrs · **Lab:** 30 hrs · **Stack:** PostgreSQL, Python (psycopg2), Flask or FastAPI, SQLAlchemy (optional)

## Project Format
One semester-long project: build a complete database-backed application end to end. Weekly milestones.

## Syllabus

### Unit 1 — Project Setup and Requirements (3 lectures)
1. Choosing a project domain — scope and feasibility
2. Requirements gathering — use cases and user stories
3. Data requirements — entities, attributes, relationships

### Unit 2 — Schema Design (3 lectures)
1. ER modelling for the project
2. Converting ER to relational schema
3. Normalisation to 3NF and review

### Unit 3 — Implementation (3 lectures)
1. PostgreSQL setup — users, roles, connection
2. Schema DDL — tables, constraints, indexes
3. Seed data and fixtures

### Unit 4 — Application Layer (3 lectures)
1. Connecting from Python — psycopg2 / SQLAlchemy
2. CRUD API endpoints — design
3. Transactions and error handling

### Unit 5 — Testing and Delivery (3 lectures)
1. Testing the database layer
2. Query optimisation — EXPLAIN, indexes
3. Deployment and backup

## Practical Labs (15 — weekly milestones)

1. Project proposal — domain, users, key features
2. ER diagram — initial version
3. Refined ER diagram — review with feedback
4. Relational schema — tables and constraints
5. Normalisation check — 3NF validation
6. PostgreSQL setup and first DDL script
7. Full schema DDL committed to repo
8. Seed data script
9. Python connection and first query
10. Read endpoints — list and detail
11. Write endpoints — create, update, delete
12. Transaction handling and error paths
13. Database test suite — 10 test cases
14. Query performance — index review and EXPLAIN
15. Final deployment, README, and demo

## Deliverables
- GitHub repo with `schema.sql`, `seed.sql`, `app/`, `tests/`, `README.md`
- ER diagram (in repo, as image or Mermaid)
- API documentation (OpenAPI or equivalent)
- Deployment link or runnable instructions
- Final demo recording
