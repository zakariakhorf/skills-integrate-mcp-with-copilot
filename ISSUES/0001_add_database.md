# Issue: Add database persistence and migrations

**Summary**
Replace the current in-memory storage with a persistent database (Postgres or SQLite for development). Add models, migrations, and a small migration script to migrate existing in-memory semantics to the DB. Update endpoints to use the DB.

**Acceptance criteria**
- Add SQLAlchemy (or SQLModel) models matching current in-memory data structures.
- Add Alembic or equivalent migrations and an initial migration.
- Update the signup and activity listing endpoints to persist to DB.
- Add a dev `docker-compose` or instructions to run DB locally.
- Add tests covering DB-backed endpoints.

**Labels:** enhancement, backend, priority:high
