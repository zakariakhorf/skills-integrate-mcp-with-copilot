# Issue: Events with multi-slot scheduling and simple ticketing

**Summary**
Add Event and EventShowing models (multi-slot/time ranges) and a simple ticketing/sign-up flow without payment integration. Support capacities, holds, and sign-up cancellation.

**Acceptance criteria**
- Event and EventShowing models with start/end times and location.
- Endpoints to create events and showings (admin) and to sign up for showings (students).
- Capacity handling and simple ticket holds with expiration.
- Tests that simulate sign-ups and holds.

**Labels:** enhancement, backend, priority:medium
