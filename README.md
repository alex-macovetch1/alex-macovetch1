<h1 align="center">Hi, I'm Alexandru 👋</h1>

<p align="center">
  <b>Junior web developer</b> from Chișinău, Moldova · Next.js · React · TypeScript · Python<br>
  Everything below is online right now — open any link and check it.
</p>

<p align="center">
  <a href="https://alex-macovetch1.github.io/portofoliu/?lang=en">🌐 Portfolio</a> ·
  <a href="https://alex-macovetch1.github.io/portofoliu/cv/Alexandru-Macovetchi-CV.pdf">📄 CV (PDF)</a> ·
  <a href="mailto:alexmacovetchi23@gmail.com">✉️ alexmacovetchi23@gmail.com</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel">
</p>

---

### 💼 Paid client work

**[TerraLux SPA](https://terralux.md/en/)** — website for a luxury spa in Chișinău. Three separate
language versions (RO / RU / EN, 15 pages) with translated URLs for SEO. I build and maintain it,
and I watch its uptime with my own monitoring tool. It is a real business paying for the work.

I also build and maintain smaller business sites and landing pages for local clients.

---

### 🚀 Apps I built and deployed

| Project | What it does | Stack |
|---|---|---|
| **[WASD](https://wasd-dun.vercel.app)** · [code](https://github.com/alex-macovetch1/wasd) | Store for mechanical keyboards: 393 products, filters, cart, checkout, wishlist, order tracking, blog and an admin panel behind a login. 22 routes. | Next.js 16 · React 19 · TypeScript · Tailwind 4 · Zustand |
| **[ALVEA](https://alvea-taupe.vercel.app)** *(private repo)* | Dental clinic site with real online booking: pick service, doctor, day and hour — a taken slot disappears for everyone else. 13 pages, 5 API routes, RO/RU. Double booking is blocked by a unique index in Postgres, not by frontend code. | Next.js 16 · TypeScript · Supabase Postgres · CSS Modules |
| **[LeadBot](https://leadbot-inky.vercel.app)** · [code](https://github.com/alex-macovetch1/leadbot) | Chat widget in Romanian and Russian that asks visitors a few questions, shows matching offers and saves every lead in Postgres. One deployment serves 5 different businesses, chosen by a URL parameter. | Next.js 16 · TypeScript · Google Gemini API · Supabase |
| **[Senkai](https://senkai-app.vercel.app)** · [code](https://github.com/alex-macovetch1/senkai) | Media tracker for anime, movies, series and games. Users register and log in, then keep a personal list saved on the server. Data comes from 3 external APIs (AniList GraphQL, Cinemeta, RAWG). Login and sessions are written by me, without an auth library. | Next.js 16 · TypeScript · Supabase Postgres |
| **[Playdex](https://playdex-omega.vercel.app)** · [code](https://github.com/alex-macovetch1/playdex) | Games analytics dashboard on live RAWG data (900K+ games). No database — every number is computed from the API on the server and cached for one hour. 3 charts, filtered browse page, game pages. | Next.js 16 · React 19 · TypeScript · Recharts |
| **[Portfolio](https://alex-macovetch1.github.io/portofoliu/?lang=en)** · [code](https://github.com/alex-macovetch1/portofoliu) | My own site: 3 languages switched without reload, light/dark theme, self-hosted fonts. No framework, no build step, no trackers and no analytics. | HTML · CSS · JavaScript |

---

### 🐍 Backend and Python

Two tools I use myself. Both are typed, tested and run in Docker.
The repositories are private — I can show the code in an interview.

- **chirie-bot** — Telegram bot that watches new rental listings in Chișinău. It reads the private
  GraphQL API of 999.md (faster and more stable than parsing HTML) plus a second site, filters by
  price, district and rooms, and sends each new listing once. SQLite for history.
  **78 tests**, `mypy --strict`, `ruff`, GitHub Actions on Python 3.11 and 3.12.
- **site-monitor** — uptime monitor for client sites, running every 5 minutes. It checks HTTP status,
  response time, TLS certificate expiry and that the page still contains the expected text, sends
  Telegram alerts when the state changes, and generates a status page. **90 tests**, `mypy --strict`,
  `ruff`, Docker Compose. It currently watches 9 sites, 3 of them paid client sites.

---

### 📌 About me

I am a junior developer, and I learn by building things that actually run: databases, login,
API routes and deployment are already part of my work, not only the UI. My daily tools are
Next.js, TypeScript and Python.

🌍 Romanian · Russian (native) · English (technical reading and writing) &nbsp;·&nbsp; 💼 Open to remote work and to jobs in Chișinău
