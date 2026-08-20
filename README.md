# Alieu Saidy

**Full-stack engineer — The Gambia 🇬🇲**

I build production platforms for West African and diaspora markets. Most of my work sits where transactional correctness matters: payments, multi-tenant data isolation, real-time state, and accounting ledgers that have to balance.

Currently studying Computer Science (BSc, University of the People) and AI Engineering (Ziti Group).

📫 alieusaidy1999@gmail.com · [LinkedIn](https://www.linkedin.com/in/alieu-saidy-b1833a27b/)

---

## What I've shipped

**KerrFaadia** — Property and rental marketplace
Event-driven architecture across four layers: Stripe webhooks for payment state, Socket.IO for live updates, transactional email triggers, and Expo push notifications. Server-authoritative booking state to prevent double-booking under concurrency.
`Next.js` `Node.js` `Stripe` `Socket.IO` `React Native`

**LexBook** — Lawyer discovery and booking platform
Turborepo monorepo sharing types between web and mobile. Postgres exclusion constraints enforce non-overlapping appointment slots at the database level rather than in application code. Row-level security for tenant isolation, with a Deno edge function handling Stripe webhooks.
`Next.js 15` `Supabase` `React Native` `Deno` `Turborepo`

**Kalamu** — Distribution ERP for building materials distributors
Double-entry accounting ledger that stays invisible to end users — shopkeepers record sales, the system maintains balanced books. Money and quantities stored as bigint to avoid float drift. Contractor debt aged per project and site.
`Node.js` `Express` `MongoDB` `Next.js` `React Native`

**Mizan** — AI Quran verse matcher
Semantic matching between natural-language queries and Quranic verses, built on the Claude API and Quran Foundation APIs. Submitted to the Quran Foundation Hackathon 2026.
`Python` `Claude API`

---

## Stack

**Core** — TypeScript · Python · Next.js · Node.js · React Native · PostgreSQL · MongoDB
**Platform** — Supabase · Stripe · Docker · GitHub Actions · Vercel
**AI** — Claude API · LangGraph · n8n

---

## Currently working on

- Multi-tenant AI automation for Gambian SMBs — WhatsApp inquiry handling for food businesses
- LangGraph agent orchestration in Python
- Writing about production engineering patterns on [LinkedIn](https://www.linkedin.com/in/alieu-saidy-b1833a27b/)

---

<img src="https://github-readme-stats.vercel.app/api?username=alieutech&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_title=true&theme=graywhite" height="150" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alieutech&layout=compact&hide_border=true&count_private=true&hide_title=true&theme=graywhite" height="150" alt="Top languages" />
