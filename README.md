# Campus Notice Board

A small API that lets campus clubs publish notices for students.

## Tech stack

Node.js 18 or later, using only built-in modules. No npm install is needed.

## Setup

1. Clone the repository.
2. Copy `.env.example` to `.env` and fill in your own values.

## Run

```bash
npm start
```

Open http://localhost:3000/notices to see the notices, or http://localhost:3000/health to check the app is up.

## Test

```bash
npm test
```

## Environment variables

| Name | Purpose |
| --- | --- |
| `PORT` | Port the server listens on (default 3000) |
| `ADMIN_API_KEY` | Key for admin actions |
| `DB_PASSWORD` | Database password |

## Project plan

See the [PRD](docs/PRD.md).
