# AGENTS.md

## Project

GameDate is an MVP web dating app for gamers who want to meet people nearby to play games together in real life.

The experience is mobile-first and inspired by Tinder:
users discover nearby players, swipe profiles, match when both like each other, and start a basic chat.

The app supports English and Spanish and allows players from all gaming platforms.

## Stack

Language: TypeScript
Framework: Next.js (App Router)

Main tools:

* Tailwind CSS
* Supabase (Auth, Database, Realtime)
* pnpm
* Vercel

## Local development

Install dependencies:

pnpm install

Run the dev server:

pnpm dev

App runs at:

http://localhost:3000

Build production version:

pnpm build
pnpm start

## Project structure

app/ → Next.js routes and layouts
src/ → components and business logic
lib/ → helpers and shared utilities
supabase/ → schema, policies, and config
public/ → static assets

## MVP features

The agent should only implement the following MVP features:

* user account creation
* gamer profile with:

  * profile photo
  * games
  * platform
  * city
* discover nearby players
* swipe system like Tinder
* match when both users like each other
* basic chat between matched users
* geolocation support
* English and Spanish support
* all gaming platforms

## Rules

* Keep the implementation simple.
* Focus on mobile-first UX.
* Follow the existing code style.
* Prefer small and focused changes.
* Avoid unnecessary dependencies.

## Restrictions

The agent must NOT:

* add payment systems
* build complex recommendation algorithms
* implement advanced moderation
* add push notifications
* introduce external integrations not required for the MVP
* deploy to production
* modify secrets or environment variables

## Decision making

If something is unclear:

* choose the simplest solution suitable for an MVP
* ask before changing architecture, database schema, or auth
* prioritize usability over technical complexity
