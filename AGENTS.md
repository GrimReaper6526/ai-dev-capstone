# Project Instructions for AI Agents

## Project Overview

AI-assisted full-stack development capstone project.
Student: [Tera naam] | Batch: 2024–2028 | UET Taxila

## Tech Stack

- Backend: Node.js + Express
- Frontend: React + Vite
- Database: MongoDB
- Package Manager: npm
- Version Control: Git + GitHub

## Coding Conventions

- Use ES6+ syntax (arrow functions, destructuring, async/await)
- camelCase for variables and functions
- PascalCase for React components
- kebab-case for file names
- No semicolons (Prettier default)
- 2 spaces for indentation

## Git Rules

- Commit format: Conventional Commits 1.0.0
  - feat: new feature
  - fix: bug fix
  - docs: documentation only
  - chore: tooling or setup
  - style: formatting, no logic change
  - refactor: code restructure
- Branch naming: kebab-case (e.g. feat/add-auth-route)
- Always write commit messages in English

## What NOT to do

- Do not commit node_modules/
- Do not commit .env files
- Do not use var — use let or const only
- Do not skip error handling in async functions

## Folder Structure (planned)

ai-dev-capstone/
├── client/ # React + Vite frontend
├── server/ # Node.js + Express backend
├── README.md
├── AGENTS.md
└── .gitignore
