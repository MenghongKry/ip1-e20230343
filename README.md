# LoanlyLab

Lab equipment booking for the faculty labs at ITC. Students reserve lab equipment for a time window, and lab staff approve or reject the requests, hand the equipment out, and track returns and overdue items. It replaces the paper sign-out sheets.

Individual project for **Internet Programming I** (I4-GIC, ITC, 2026–2027).

## Student info

| | |
| --- | --- |
| Name | Menghong Kry |
| Student ID | `e20230343` |
| Group | I4-GIC-A |
| Department | Department of Information and Communication Engineering (GIC) |
| Lecturer | Mr. CHUN Thavorac |

## Main features

- Browse and search equipment by lab, category and availability
- Students request 1–5 units of one or more items for a time window, and can cancel
- Lab staff approve or reject requests, record pick-up and return (OK or damaged)
- Overdue list and reservation history
- Admin manages labs, user accounts and sees an activity log

Roles: Guest, Student, Lab staff, Admin.

## Tech stack

- **Frontend:** Vue 3 + TypeScript
- **Backend:** NestJS
- **Database:** PostgreSQL (Prisma), run with Docker Compose

## Docs

- Specification: [docs/SPEC.md](docs/SPEC.md)

## Getting started

_Setup steps will be added once the frontend and backend are scaffolded._
