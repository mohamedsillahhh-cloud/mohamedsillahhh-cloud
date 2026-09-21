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

Most of my work is for Cape Verdean users and institutions: finance tools, school platforms and community software.

|  |  |
|---|---|
| 📍 **Based in** | Cape Verde 🇨🇻 |
| 🎯 **Focus** | Backend engineering, fintech |
| 💼 **Open to** | Backend roles in Cape Verde and Europe |

<br clear="right"/>

---

## 🚀 Projects

### 💰 Finance Bot
![private](https://img.shields.io/badge/repo-private-6e7681?style=flat-square) ![main](https://img.shields.io/badge/main_project-0077B5?style=flat-square) ![telegram](https://img.shields.io/badge/platform-telegram-2CA5E0?style=flat-square)

Personal finance assistant on Telegram, built for the Cape Verdean market. Users log and manage their money by chatting in natural language, including Cape Verdean Portuguese, and the bot keeps working even when every AI provider is down.

<details>
<summary><b>Detalhes</b></summary>

<br>

#### What it does

- **Natural language in Cape Verdean Portuguese:** understands slang, local terms and colloquial expressions, not just textbook Portuguese
- **Conversational, not command-driven:** short-term memory, follow-up questions when information is missing, correction detection, and inline keyboards to clarify ambiguous input
- **Full personal finance toolkit:** budgets, savings goals, auto-save, installments, split expenses and recurring transactions
- **Receipt scanning:** OCR to read receipts from photos

#### Under the hood

- **Multi-provider AI routing** across Gemini, Groq and OpenRouter, with automatic fallback and a circuit breaker to stop hammering a failing provider
- **Regex fallback engine** that takes over when all providers hit rate limits, so the bot never goes silent
- **PostgreSQL persistence**, after a migration to a production-grade database
- **Security hardening** pass on the codebase
- **Automated tests** with pytest

#### Stack

`Python 3.12` `python-telegram-bot` `PostgreSQL` `Gemini` `Groq` `OpenRouter` `pytest`

</details>

<br>

### 🏫 School Website + CMS
![private](https://img.shields.io/badge/repo-private-6e7681?style=flat-square) ![live](https://img.shields.io/badge/status-live_in_production-46E3B7?style=flat-square)

Institutional website with a custom content management system for a public technical school in Cape Verde, built so the school's own staff can keep it up to date without a developer.

<details>
<summary><b>Detalhes</b></summary>

<br>

#### What it does

- **Public institutional website** for a public technical school in Cape Verde, live in production
- **Custom CMS** designed for non-technical staff: publish and edit content through an admin interface instead of touching code
- Built end to end and presented to the school

#### Under the hood

- **Flask backend** with PostgreSQL for content storage
- **Supabase** in the stack for managed services
- **Deployed on Render** and running in production

#### Stack

`Python` `Flask` `PostgreSQL` `Supabase` `Render`

[![Live](https://img.shields.io/badge/Live_site-46E3B7?style=flat-square&logo=render&logoColor=black)](https://etjv.onrender.com)

</details>

<br>

### 💼 DevFlow
![public](https://img.shields.io/badge/repo-public-2ea44f?style=flat-square) ![web+desktop](https://img.shields.io/badge/platform-web_%2B_desktop-3ECF8E?style=flat-square)

Full-stack management dashboard for freelancers: projects, clients, finances and investments in one place, with a web app and a native desktop client sharing the same backend.

<details>
<summary><b>Detalhes</b></summary>

<br>

#### What it does

- **Projects and clients:** track work, clients and status in one dashboard
- **Finances and investments:** income, expenses and an investments portfolio
- **Project timer with billing estimate:** track time and see what a project is worth
- **Executive KPI dashboard:** the key numbers of a freelance business at a glance

#### Under the hood

- **Two clients, one backend:** React 19 + Vite + TypeScript web app and a native PyQt6 desktop client, both on the same Supabase backend
- **Security first:** Supabase Auth with an email allowlist and Row Level Security on every table
- **Versioned SQL migrations** for a reproducible database schema
- **Schema validation** with Zod on the frontend

#### Stack

`React 19` `TypeScript` `Vite` `Zod` `PyQt6` `Supabase` `Render`

[![Repo](https://img.shields.io/badge/View_repository-181717?style=flat-square&logo=github)](https://github.com/mohamedsillahhh-cloud/DevFlow)

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

## 📊 Activity

<div align="center">
  <img height="160" src="https://github-readme-stats.shion.dev/api?username=mohamedsillahhh-cloud&theme=dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
  <img height="160" src="https://github-readme-stats.shion.dev/api/top-langs/?username=mohamedsillahhh-cloud&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />
</div>

<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mohamedsillahhh-cloud/mohamedsillahhh-cloud/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mohamedsillahhh-cloud/mohamedsillahhh-cloud/output/github-snake.svg" />
    <img alt="Contribution graph with a snake eating the contributions" src="https://raw.githubusercontent.com/mohamedsillahhh-cloud/mohamedsillahhh-cloud/output/github-snake.svg" />
  </picture>
</div>

---

<div align="center">

*Open to backend engineering opportunities in Cape Verde and Europe.*

[![LinkedIn](https://img.shields.io/badge/Let's_connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-sllh)

</div>
