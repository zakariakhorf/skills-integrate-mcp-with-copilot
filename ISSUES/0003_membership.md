# Issue: Implement membership model & roles

**Summary**
Add a `Membership` model that links students to activities and supports roles (member, officer). Implement APIs to request/join, invite, and manage members.

**Acceptance criteria**
- Add Membership model with role enum and timestamps.
- Endpoints to list members for an activity, invite a user, accept/decline invites, and remove members.
- Permission checks: only officers/admin can manage members.
- Tests to cover membership flows.

**Labels:** enhancement, backend, priority:medium
