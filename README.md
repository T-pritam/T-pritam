# T Pritam

**Full-Stack Developer @ Tach21** · Berhampur, India

> I ship entire app ecosystems — customer apps, admin apps, and the backend that runs them — end-to-end. Currently open to full-stack roles at product startups.

[![Portfolio](https://img.shields.io/badge/Portfolio-pritamrao.tech-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio.pritamrao.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-t--pritam-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/t-pritam)
[![Email](https://img.shields.io/badge/Email-pritamrao38@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pritamrao38@gmail.com)
[![Open to Work](https://img.shields.io/badge/Open%20to-Product%20Startup%20Roles-3ECF8E?style=flat-square)](#)

---

## About

I'm a full-stack developer with 1.5 years of professional experience building production systems that customers actually touch every day. My favourite kind of work is owning a problem from the database schema up through the React Native screen — designing the API, modelling the data, and making sure the whole thing feels fast.

Outside of work, I've been building complete multi-app platforms for cafes, gyms and hospitals — the kind of work that usually takes a small team. I care about clean architecture, real-time UX, and shipping things that hold up under real traffic.

Right now I'm sharpening my system-design instincts and exploring background-job patterns (BullMQ, cron workers) for high-throughput consumer apps.

---

## Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-1A1A1A?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=react-query&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

**Mobile**
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3068B7?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)

**Database**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**Tools & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Razorpay](https://img.shields.io/badge/Razorpay-0C4887?style=flat-square&logo=razorpay&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Featured Projects

### Build Cafe — Full Cafe Ordering Ecosystem
Four-app platform for table-based cafe ordering: customers scan a QR, browse the menu, pay via Razorpay, and watch their order move through the kitchen in real time. Staff run the kitchen, deliveries, and admin from a single role-aware app.

`React Native` `React + Vite` `Fastify` `PostgreSQL + Drizzle` `Supabase Realtime` `Razorpay` `S3`

**Why it's impressive:** Four production apps (customer mobile, customer web, staff app with three roles, backend API) — designed, built, and integrated as one system. End-to-end order lifecycle, HMAC-verified webhooks, 100+ database tables.

---

### Build Gym — Member + Trainer Platform with Virtual Currency
A full gym platform with digital membership cards, an in-gym cafe powered by a virtual "Build Coins" wallet, workout tracking, community feed, and BLE-simulated access control. Trainers and admins manage members, classes, and announcements through a dedicated app.

`Expo · React Native` `Fastify` `PostgreSQL + Drizzle` `Socket.io` `BullMQ` `Supabase`

**Why it's impressive:** Custom virtual-currency economy with full transaction logging, BullMQ background workers for leaderboards and KPI aggregation, cron-driven membership lifecycle, AxTrax gym access integration, and 130+ database tables.

---

### KKR Hospital Management System
A web-based HMS managing the full hospital workflow — patient records, OPD billing, lab orders, doctor and employee management, and a financial dashboard with P&L, doctor settlements and PDF exports.

`Next.js App Router` `TypeScript` `Supabase + RLS` `Tailwind CSS` `Edge Functions (Deno)`

**Why it's impressive:** Four-role RBAC enforced in middleware *and* at the database via Supabase Row-Level Security, 10-minute JWT access tokens with 7-day refresh rotation, multi-format financial PDF export, daily ledger with close-day finalization.

---

### ChatPulse — Real-Time Chat
Full-stack one-to-one and group messaging app with typing indicators, file uploads, unread tracking and friend management.

`Next.js` `TypeScript` `Redux Toolkit` `Node.js + Express` `MongoDB` `Pusher` `Cloudinary`

**Why it's impressive:** Real-time messaging built on Pusher with reliable state via Redux Toolkit — clean separation between transport, state, and UI.

---

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=T-pritam&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=T-pritam&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>
<p>
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=T-pritam&theme=tokyonight&hide_border=true" />
</p>

---

## Currently

- **Building** — production React Native and Fastify systems at Tach21
- **Learning** — distributed background-job patterns, queue design with BullMQ, and finer-grained Postgres performance tuning
- **Looking for** — full-stack roles at product startups where I can own features end-to-end and work close to the problem

---

## Connect

- [LinkedIn](https://linkedin.com/in/t-pritam)
- [Portfolio](https://portfolio.pritamrao.tech)
- [Email](mailto:pritamrao38@gmail.com)
