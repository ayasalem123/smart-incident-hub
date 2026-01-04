# smart-incident-hub

A web app to report, track, and resolve incidents with smart triage (priority suggestion) and similar-incident recommendations.

## Tech Stack
- Backend: Java, Spring Boot (Spring Web, Spring Security, Spring Data JPA)
- Frontend: Angular
- Database: PostgreSQL (dev can use H2)
- Tests: JUnit 5, Mockito

## Features (MVP)
- Authentication (JWT) + roles (USER, AGENT, ADMIN)
- Incident CRUD (create, list, detail, update)
- Status workflow: NEW → IN_PROGRESS → WAITING → RESOLVED
- Comments on incidents
- List + filters (status, priority)

## Screenshots
_TODO_

## How to run (dev)
_TODO_
