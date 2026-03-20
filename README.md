<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0d1117,60:0b1a0b,100:132f13&height=200&section=header&text=sayomiyori&fontSize=50&fontColor=39d353&fontAlignY=35&desc=Python%20Backend%20Developer&descSize=18&descColor=7ee787&descAlignY=55&animation=fadeIn" width="100%"/>

<!-- TYPING SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=FastAPI+%C2%B7+Django+%C2%B7+PostgreSQL+%C2%B7+Redis+%C2%B7+Docker;Building+production-ready+backend+services" alt="Typing SVG" /></a>

<br/>

<!-- SOCIAL BADGES -->
[![GitHub](https://img.shields.io/badge/GitHub-sayomiyori-0d1117?style=flat-square&logo=github&logoColor=39d353)](https://github.com/sayomiyori)
[![Kwork](https://img.shields.io/badge/Kwork-sayomiyori-0d1117?style=flat-square&logo=freelancer&logoColor=39d353)](https://kwork.ru/user/sayomiyori)
[![Email](https://img.shields.io/badge/Email-flamxd@mail.ru-0d1117?style=flat-square&logo=gmail&logoColor=39d353)](mailto:flamxd@mail.ru)

</div>

---

## 🧑‍💻 About

```python
class SayomiYori:
    role      = "Python Backend Developer"
    location  = "Simferopol / Remote 🇷🇺"
    education = "Crimean Federal University (CS, 2028)"
    
    focus = [
        "Microservices (Django + FastAPI + RabbitMQ)",
        "Event-driven architecture & message brokers",
        "CI/CD pipelines, Docker, Observability",
        "WebSockets & real-time systems",
    ]
    
    looking_for = "Backend position in a team with code review & engineering culture"
```

---

## ⚡ Tech Stack

<div align="center">

**`Core Backend`**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=39d353)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=39d353)
![Django](https://img.shields.io/badge/Django-0d1117?style=for-the-badge&logo=django&logoColor=39d353)
![DRF](https://img.shields.io/badge/DRF-0d1117?style=for-the-badge&logo=django&logoColor=39d353)

**`Data & Messaging`**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=39d353)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=for-the-badge&logo=redis&logoColor=39d353)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-0d1117?style=for-the-badge&logo=rabbitmq&logoColor=39d353)
![Celery](https://img.shields.io/badge/Celery-0d1117?style=for-the-badge&logo=celery&logoColor=39d353)

**`Infrastructure & DevOps`**

![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=39d353)
![Nginx](https://img.shields.io/badge/Nginx-0d1117?style=for-the-badge&logo=nginx&logoColor=39d353)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=for-the-badge&logo=githubactions&logoColor=39d353)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=39d353)

**`Quality & Observability`**

![Pytest](https://img.shields.io/badge/Pytest-0d1117?style=for-the-badge&logo=pytest&logoColor=39d353)
![Prometheus](https://img.shields.io/badge/Prometheus-0d1117?style=for-the-badge&logo=prometheus&logoColor=39d353)
![Grafana](https://img.shields.io/badge/Grafana-0d1117?style=for-the-badge&logo=grafana&logoColor=39d353)
![Sentry](https://img.shields.io/badge/Sentry-0d1117?style=for-the-badge&logo=sentry&logoColor=39d353)

</div>

---

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔀 [TaskFlow](https://github.com/sayomiyori/TaskFlow)
**Microservice task platform — Django + FastAPI + RabbitMQ**

`Django 5` `DRF` `FastAPI` `RabbitMQ` `Redis` `Channels` `Nginx` `Docker`

- 🏛️ 2 microservices: Django API + FastAPI notification consumer
- 📡 RabbitMQ topic exchange (task.created, task.updated)
- ⚡ WebSocket updates via Django Channels + Redis
- 🔒 JWT auth, role-based permissions, django-filter
- 🌐 Nginx reverse proxy with rate limiting
- 🧪 pytest + factory_boy, CI/CD on GitHub Actions

</td>
<td width="50%" valign="top">

### 🪝 [WebHook Manager](https://github.com/sayomiyori/WebHook_Manager)
**SaaS platform for reliable webhook delivery**

`FastAPI` `Celery` `Redis` `PostgreSQL` `Prometheus` `Sentry` `Docker`

- 🔄 Celery delivery: exponential backoff (10s→1h), 5 retries
- 🔑 Idempotent intake (X-Idempotency-Key) + HMAC verification
- 🔌 Redis circuit breaker — no events lost
- 🏗️ Clean Architecture (domain/services/infrastructure/api)
- 📊 Prometheus metrics, Sentry, structlog (JSON + correlation ID)
- 🧪 >80% coverage, CI: ruff + mypy strict → pytest → auto-deploy

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💬 [RealTimeChat](https://github.com/sayomiyori/RealTimeChat)
**WebSocket chat with horizontal scaling**

`FastAPI` `WebSocket` `Redis Pub/Sub` `PostgreSQL` `JWT` `Docker`

- 📡 Redis Pub/Sub fan-out across multiple API replicas
- 💬 Room-based messaging with history (last 50 on connect)
- ⌨️ Typing indicators (real-time, not persisted)
- 🔐 JWT auth on WebSocket connections
- 🧪 CI + Codecov, async stack (asyncpg + redis.asyncio)

</td>
<td width="50%" valign="top">

### 📚 [BookFinder API](https://github.com/sayomiyori/BookFinder-API)
**REST API for book search & cataloging**

`FastAPI` `PostgreSQL` `SQLAlchemy 2` `JWT` `Prometheus` `Grafana` `Docker`

- 📖 10 endpoints (/api/v1/), Google Books integration
- 🗄️ Async PostgreSQL + Alembic migrations
- 📊 Prometheus + Grafana: error rate, latency p95, RPS
- 🔄 CI/CD: ruff → pytest (87% coverage) → Docker → auto-deploy
- 📝 Pydantic v2, Swagger UI, CORS

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🤖 [ChillLibrary Bot](https://github.com/sayomiyori/ChillLibraryTgBot)
**Telegram book search bot — commercial project**

`aiogram` `aiohttp` `Google APIs` `Gemini AI` `Docker`

- 🔍 3 search modes: title, book cover (Vision OCR), quote (Gemini AI)
- 📦 Full cycle: spec → architecture → dev → tests → deploy → docs
- 🏛️ Layered architecture (handlers/services/utils)
- ✅ Delivered to client, accepted without revisions

</td>
<td width="50%" valign="top">

### 💪 [BodyTelling Bot](https://github.com/sayomiyori/BodyTellingTelegramBot)
**Fitness club Telegram bot — commercial project**

`aiogram` `APScheduler` `pytest`

- 🎯 Workout selection algorithm by 5 parameters
- 🔥 Retention mechanics: streaks, achievements, auto-reminders (TZ-aware)
- 📦 Modular codebase, pytest + conftest
- ✅ Commercial delivery with full documentation

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sayomiyori&show_icons=true&hide_border=true&bg_color=0d1117&title_color=39d353&icon_color=2ea043&text_color=c9d1d9&ring_color=39d353" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sayomiyori&layout=compact&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9&langs_count=8" height="170"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sayomiyori&hide_border=true&background=0d1117&stroke=21262d&ring=39d353&fire=39d353&currStreakLabel=39d353&sideLabels=7ee787&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=484f58" height="170"/>

</div>

---

## 🧊 3D Contribution Calendar

<div align="center">

<img src="./profile-3d-contrib/profile-night-green.svg" width="100%"/>

</div>

---

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sayomiyori&hide_border=true&bg_color=0d1117&color=39d353&line=2ea043&point=39d353&area=true&area_color=238636" width="95%"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sayomiyori&style=flat-square&color=2ea043&label=Profile+Views" alt="Profile views"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sayomiyori/sayomiyori/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sayomiyori/sayomiyori/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/sayomiyori/sayomiyori/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

---

<div align="center">

**Open to opportunities · Python Backend Developer · Remote**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0d1117,60:0b1a0b,100:132f13&height=100&section=footer" width="100%"/>
