<img src="banner.svg" alt="Alieu Saidy — Full-stack engineer" width="100%" />

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alieu-saidy-b1833a27b/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alieusaidy1999@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@alieutech)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/alieutech132)

</div>

---

I build production platforms for West African and diaspora markets — mostly systems where correctness under load actually matters: payment state machines, multi-tenant isolation, real-time updates, and accounting ledgers that have to balance.

Four years shipping full-stack. Currently studying **Computer Science** at the University of the People and **AI Engineering** with Ziti Group.

---

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🏠 KerrFaadia
**Property & rental marketplace**

Event-driven across four layers — Stripe webhooks for payment state, Socket.IO for live updates, transactional email triggers, and Expo push. Booking state is server-authoritative to survive concurrent requests.

`Next.js` `Node.js` `Stripe` `Socket.IO` `React Native`

</td>
<td width="50%" valign="top">

### ⚖️ LexBook
**Lawyer discovery & booking**

Turborepo monorepo sharing types across web and mobile. Postgres exclusion constraints enforce non-overlapping appointment slots at the database layer instead of in application code. RLS for tenant isolation; Stripe webhooks on a Deno edge function.

`Next.js 15` `Supabase` `Deno` `Turborepo`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📦 Kalamu
**Distribution ERP for hardware suppliers**

A double-entry accounting ledger that stays invisible to the user — shopkeepers record sales, the system keeps the books balanced. Money and quantities stored as bigint to avoid float drift. Contractor debt aged per project and site.

`Node.js` `Express` `MongoDB` `React Native`

</td>
<td width="50%" valign="top">

### ✂️ TailorFlow
**Tailor shop management SaaS**

Multi-tenant from the schema up, with RLS policies and a JSONB measurements model that adapts to each shop's garment specs without running migrations.

`Next.js` `Supabase` `TypeScript`

</td>
</tr>
</table>

<details>
<summary><b>Other projects</b></summary>

<br>

**Mizan** — AI Quran verse matcher. Semantic matching between natural-language queries and Quranic verses, built on the Claude API and Quran Foundation APIs. Submitted to the Quran Foundation Hackathon 2026. `Python` `Claude API`

**LinkedIn content pipeline** — Multi-tenant n8n workflow: Google Sheets calendar → Claude drafts → parallel fan-out to Sheets, Notion, and Gmail, with an idempotency gate and a dedicated error-handling branch. `n8n` `Claude API`

</details>

---

## Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

</div>

---

## Currently building

- **AI automation for Gambian SMBs** — WhatsApp inquiry handling, starting with food businesses
- **LangGraph agent orchestration** in Python
- Writing about production engineering patterns on [LinkedIn](https://www.linkedin.com/in/alieu-saidy-b1833a27b/)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=alieutech&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_title=true&theme=tokyonight&bg_color=0D1117&icon_color=38BDF8&text_color=94A3B8&title_color=F8FAFC" height="160" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alieutech&layout=compact&hide_border=true&count_private=true&hide_title=true&theme=tokyonight&bg_color=0D1117&text_color=94A3B8" height="160" alt="Top languages" />

</div>
