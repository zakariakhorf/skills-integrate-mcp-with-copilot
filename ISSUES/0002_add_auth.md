# Issue: Add authentication and user profiles

**Summary**
Add authentication to the API (OAuth2/JWT) and user profile endpoints. Support user registration, login, and a basic profile (name, grade, email). Add roles (student, admin) to support future permissions.

**Acceptance criteria**
- Add authentication (JWT access tokens) and secure endpoints.
- Add User model (or extend) and profile endpoints (GET/PUT profile).
- Add role field or simple permission flags and protection of admin endpoints.
- Update README with usage and env vars for auth.

**Labels:** enhancement, backend, priority:high
