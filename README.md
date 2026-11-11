# TutorPlan

A web app for tutors who also study: manage students, teaching schedules and session note, and plan self-study time (math, physics, chemistry) around teaching hours.

> Status: planning (week 1). Not usable yet

## Features (planned)

**v1:** authentication, students, weekly teaching schedule with conflict detection, session attendance and notes, study subjects and deadlines, free-slot finder and study-block suggestions, spaced-repetition flashcards (SM-2), weekly dashboard.

**v2:** question bank, exam generator (printable PDF), homework, student progress report, English vocabulary tools, calendar export (ICS).

## Tech stack

- Frontend: React, TypeScript, Vite
- Backend: ASP.NET Core Web API (.NET 10), EF Core
- Database: SQL Server
- Tooling: Docker Compose, Github Actions

## Project structure

```
backend/    ASP.NET Core API (Clean Architecture)
frontend/   React app
docs/   requirements, ERD, wireframes
```

## Getting started (planned)

```bash
cp .env.example .env
docker compose up -d # start SQL Server
cd backend && dotnet run --project src/TutorPlan.Api
cd frontend && npm install && npm run dev
```

## Documentation

See the `docs/` folder.

## License

MIT