# AVACADO

An AI phone receptionist for small businesses. The owner sets the AI's personality, rules and knowledge in a simple dashboard, with no technical setup.

**Status:** paused. Dashboard and backend are built; no real phone call has gone through it yet, so the MVP is unfinished. Source code is not uploaded yet. Write-up: https://abhiraajr.github.io/projects/avacado.html

## What's built
- React dashboard with sign-in, agent configuration and phone-number management
- FastAPI backend on Supabase (Postgres and auth) with SQL migrations
- Agent settings synced to a third-party voice provider behind a swappable abstraction
- Phone-number provisioning, webhook ingestion and a calls API

## Stack
React, TypeScript, Vite, Tailwind, Python FastAPI, Supabase.

## Honest status
The blocker was billing setup on the voice provider, not code. I also haven't talked to customers or set pricing.

Author: Abhiraaj Rampal
