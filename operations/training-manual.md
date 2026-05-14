# skunk-works — Project Training Manual

> This manual covers what is unique to the skunk-works repo. All global standards live in andredavisme/warrior-x-docs/operations/training-manual.md.

---

## What This Repo Is

skunk-works is the frontend and UI development repo for the Warrior X ecosystem. It is where app features, user interfaces, and interactive experiences are built. Projects here are citizen-facing tools designed to bring communities together.

## Who It Serves

Community members using Warrior X tools. Built by André and Warrior X contributors.

## Tech Stack

- HTML / CSS / JavaScript (primary)
- Supabase (backend/database, managed in andredavisme/alexandria)
- GitHub Pages (hosting where applicable)
- No frameworks required — keep it accessible to beginners

## Key Conventions

- Keep UI simple, accessible, and mobile-friendly
- Use plain HTML/CSS/JS unless a framework is explicitly justified
- Never embed API keys in frontend code — use the Supabase anon key only
- Never use the service role key in any frontend file
- All features start as a GitHub issue before any code is written

## Branch Naming

- Features: `feat/<short-description>`
- Fixes: `fix/<short-description>`
- Refactors: `refactor/<short-description>`

## How to Contribute

1. Pick or create a GitHub issue for the work
2. Branch from main using the naming convention above
3. Build the feature or fix
4. Commit: `feat: <short description>`
5. Push and open a PR
6. Do NOT merge without review

## Design Standards

- Empowerment tone in all UI copy — plain language, no jargon
- Accessible color contrast (WCAG AA minimum)
- Forms must have clear labels and error states
- Mobile-first layout

## Security Rules

- No secrets in any file committed to this repo
- Supabase anon key only in frontend code
- RLS enforced on all tables this frontend reads from (managed in alexandria)

---

## Chapter 15 — Post-Mortems & Lessons Learned

*Project-specific incidents and decisions get recorded here.*

---

*Last updated: 2026-05-14 — Initial project training manual seeded.*
