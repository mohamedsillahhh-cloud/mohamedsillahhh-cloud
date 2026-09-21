<div align="center">

![banner](https://i.pinimg.com/1200x/7b/87/1c/7b871cee4ff324b9cc17ea028b4074ce.jpg)

# Mohamed Sillah

### Junior Backend Developer · Python · REST APIs · PostgreSQL

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=17&pause=1200&color=0077B5&center=true&vCenter=true&width=520&lines=Building+real+products+that+solve+real+problems.;Fintech-minded+backend+engineer.;Based+in+Cape+Verde+%F0%9F%87%A8%F0%9F%87%BB)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-sllh)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedsillahhh@gmail.com)

</div>

<br>

## 👋 About

<img align="right" width="190" style="border-radius:12px" src="https://i.pinimg.com/736x/d4/10/ac/d410acd9734cb0715cfa969de285ba14.jpg" />

Self-taught developer focused on Python backends, REST APIs and payments-adjacent problems. I build end-to-end, from database schema to deployment, with a bias for clean architecture, tests and systems that keep working after launch.

Most of my work is for Cape Verdean users and communities: finance tools, remittance data, school and gaming platforms.

|  |  |
|---|---|
| 📍 **Based in** | Cape Verde 🇨🇻 |
| 🎯 **Focus** | Backend engineering, fintech |
| 💼 **Open to** | Backend roles in Cape Verde and Europe |

<br clear="right"/>

---

## 🚀 Projects

> Click a project to expand it.

### Fintech & Backend

<details open>
<summary><b>💸 Comparador de Remessas</b> &nbsp;·&nbsp; <code>public</code> &nbsp;·&nbsp; how much actually arrives in Cape Verde, EUR → CVE</summary>

<br>

- Ranks providers by amount received, exposing the hidden cost in the exchange rate against the official EUR/CVE peg
- Daily automated quote collection via GitHub Actions; providers without public data verified manually through an admin panel
- Quote history, staleness warnings, interpolation between reference amounts
- Backend and frontend tests, Alembic migrations, containerized deploy

`FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `React` `TypeScript` `Docker` `pytest` `Vitest`

[![Repo](https://img.shields.io/badge/View_repository-181717?style=flat-square&logo=github)](https://github.com/mohamedsillahhh-cloud/Comparador-de-remessas)

</details>

<details>
<summary><b>💰 Finance Bot</b> &nbsp;·&nbsp; <code>private</code> &nbsp;·&nbsp; Telegram finance assistant for the Cape Verdean market</summary>

<br>

- Multi-model AI routing (Gemini, Groq, OpenRouter) with automatic fallback and circuit breaker
- Understands Cape Verdean Portuguese, including slang and local terms
- Regex fallback engine when every AI provider is rate-limited, so the bot never goes silent
- Budgets, savings goals, installments, split expenses, recurring transactions, OCR receipts

`Python 3.12` `python-telegram-bot` `PostgreSQL` `Gemini` `Groq` `OpenRouter` `pytest`

</details>

<details>
<summary><b>🏆 HackHub</b> &nbsp;·&nbsp; <code>public</code> &nbsp;·&nbsp; <code>in development</code> &nbsp;·&nbsp; open-source hackathon management platform</summary>

<br>

- Clean Architecture with JWT authentication, rate limiting and multi-tenancy
- Certificate generation, CSV/Excel export, real-time updates
- Built solo, frontend and backend

`FastAPI` `PostgreSQL` `Redis` `Next.js 14` `TypeScript` `Docker`

[![Repo](https://img.shields.io/badge/View_repository-181717?style=flat-square&logo=github)](https://github.com/mohamedsillahhh-cloud/hackhub-platform)

</details>

### Products

<details>
<summary><b>💼 DevFlow</b> &nbsp;·&nbsp; <code>public</code> &nbsp;·&nbsp; management dashboard for freelancers</summary>

<br>

- React 19 + Vite + TypeScript web dashboard and a native PyQt6 desktop client sharing one Supabase backend
- Projects and clients, finances, investments, project timer with billing estimate, KPI dashboard
- Supabase Auth with email allowlist, Row Level Security on all tables, versioned SQL migrations

`React 19` `TypeScript` `Vite` `Zod` `PyQt6` `Supabase` `Render`

[![Repo](https://img.shields.io/badge/View_repository-181717?style=flat-square&logo=github)](https://github.com/mohamedsillahhh-cloud/DevFlow)

</details>

<details>
<summary><b>🏫 School Website + CMS</b> &nbsp;·&nbsp; <code>private</code> &nbsp;·&nbsp; live in production</summary>

<br>

- Institutional website with a custom CMS for a public technical school in Cape Verde
- CMS built for non-technical staff

`Python` `Flask` `PostgreSQL` `Supabase`

[Live](https://etjv.onrender.com)

</details>

### Community

<details>
<summary><b>🎮 Discord Bots & Community Tooling</b> &nbsp;·&nbsp; Cape Verdean gaming communities</summary>

<br>

- Official developer and staff of **Gameplay CV**: server architecture, forum channels, bot configuration
- **GAME HUB**: custom bot with a Components V2 UI design system, consolidating several bots into one
- Custom Minecraft plugin for the community's survival server, with a security audit and fixes
- Moderator on the Discord server of a large Free Fire content creator

`Discord API` `Discord.js` `Components V2` `Python`

</details>

---

## 🛠️ Tech Stack

<img align="right" width="190" style="border-radius:12px" src="https://i.pinimg.com/736x/1f/28/ed/1f28ed565650b82ef74e0e432002c201.jpg" />

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54"/>
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
      <img src="https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQLite-07405e?style=flat-square&logo=sqlite&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Bots & AI</b></td>
    <td>
      <img src="https://img.shields.io/badge/Discord.js-5865F2?style=flat-square&logo=discord&logoColor=white"/>
      <img src="https://img.shields.io/badge/Telegram_Bot_API-2CA5E0?style=flat-square&logo=telegram&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white"/>
      <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/>
      <img src="https://img.shields.io/badge/OpenRouter-000000?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Infra & Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
      <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
    </td>
  </tr>
</table>

<br clear="right"/>

---

<details>
<summary><b>📊 GitHub Stats</b></summary>

<br>

<div align="center">
  <img height="160" src="https://github-readme-stats.shion.dev/api?username=mohamedsillahhh-cloud&theme=dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
  <img height="160" src="https://github-readme-stats.shion.dev/api/top-langs/?username=mohamedsillahhh-cloud&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />
</div>

</details>

---

<div align="center">

*Open to backend engineering opportunities in Cape Verde and Europe.*

[![LinkedIn](https://img.shields.io/badge/Let's_connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-sllh)

</div>
