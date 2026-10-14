# Budget Buddy

A gamified personal finance app designed to make saving feel less like a chore and more like a habit-building experience. The project combines budgeting, social accountability, progress tracking, and retro game-inspired UX to encourage financial consistency.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61dafb)](https://react.dev/)
[![Backend](https://img.shields.io/badge/Backend-Supabase-3ecf8e)](https://supabase.com/)
[![Finance API](https://img.shields.io/badge/Finance%20API-Plaid-4f46e5)](https://plaid.com/)

## Project overview

Budget Buddy is a budgeting and savings application that turns everyday financial decisions into an engaging, rewarding loop. Users can:

- track spending and saving habits
- join or create social saving circles
- complete quests and learning streaks
- earn XP, coins, and achievements
- connect real bank accounts through Plaid for transaction insights

The core goal is to make financial wellness more approachable, social, and motivating.

## Why this project matters

Traditional budgeting tools often feel complicated or discouraging. Budget Buddy addresses that by combining:

- friendly UX and game-like progression
- real world financial data integration
- peer accountability through groups and leaderboards
- educational micro-interactions such as quizzes and streaks

This makes it a strong example of a product-focused full-stack project that blends UX, APIs, and data-driven user engagement.

## Key features

### Financial tracking and account sync
- Plaid-powered bank connection
- transaction-based spending insights
- savings and budgeting workflows tied to user actions

### Social accountability
- private circles and group-based saving goals
- invite-code group flow
- leaderboards and performance comparison

### Habit reinforcement
- quests and daily tasks
- streak tracking and achievement logic
- XP/coin progression and reward feedback

### Visual design
- retro arcade / CRT-inspired interface
- polished dashboard experience
- gamified UI states and progression feedback

## Tech stack

| Layer | Tech | Role |
| --- | --- | --- |
| Frontend | React + Vite + TypeScript | app interface and client-side flows |
| Backend | Supabase | authentication, data storage, and app logic backing |
| Banking integration | Plaid | real transaction syncing and account data |
| UI / motion | Framer Motion, CSS styling | interactive and retro interface experience |
| Deployment / local dev | Node.js + npm | local app development and tooling |

## Repository structure

```text
budget-buddy-1/
├── README.md                  # project overview and entry point
├── package-lock.json          # lockfile for reproducible installs
├── backend/                   # Express + Plaid + Supabase API server
├── frontend/                  # React app UI and client-side flows
├── docs/                      # implementation notes, fixes, and engineering docs
├── backups/                   # local data snapshots for reference
├── archive/                   # older starter/example resources kept for reference
├── .github/                   # repo automation and metadata
└── .git/                      # git metadata
```

## Recommended project flow

1. Review the main project overview in this README.
2. Open the frontend app in the `frontend/` directory.
3. Use the docs in `docs/` for implementation notes, debugging, and feature-specific context.
4. Treat the starter and quickstart folders as references rather than the primary product code.

## Local setup

### Prerequisites
- Node.js 18+
- npm
- Supabase account
- Plaid developer account

### Install and run

```bash
# install backend dependencies
cd backend
npm install

# copy .env.example to .env and fill in your credentials
cp .env.example .env

# start the API server
npm run server
```

Then in a second terminal:

```bash
cd frontend
npm install
npm run dev
```

Or, from the repo root, you can use:

```bash
npm install
npm run install:backend
npm run install:frontend
npm run dev
```

This keeps the app split into a proper backend folder and a frontend app folder, which makes the project much cleaner for demos and internship handoff.

## Contributors

- Sathvik Kotapati
- Nini Le
- Kaitlin Qu
- Abhinav Damarla
- Divyansh Kamboj
- Sydney Vo
- Ruoying Wu

## Project status

This project is structured as a full-stack, product-oriented financial app demo with strong emphasis on:

- user experience design
- API integration
- data flow planning
- frontend polish
- feature iteration and debugging

It is a strong internship-ready project because it shows product thinking, implementation depth, and practical engineering work across the stack.

## Documentation index

See the documentation set in `docs/` for deeper implementation details, feature notes, and debugging records.

## License

This project is distributed under the MIT License. See LICENSE for details if available in the repository structure.