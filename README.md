<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=200&section=header&text=sayomiyori&fontSize=50&fontColor=58a6ff&fontAlignY=35&desc=Python%20Backend%20Developer&descSize=18&descColor=8b949e&descAlignY=55&animation=fadeIn" width="100%"/>

<!-- TYPING SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=FastAPI+%C2%B7+Django+%C2%B7+PostgreSQL+%C2%B7+Redis+%C2%B7+Docker;Building+production-ready+backend+services" alt="Typing SVG" /></a>

<br/>

<!-- SOCIAL BADGES -->
[![GitHub](https://img.shields.io/badge/GitHub-sayomiyori-181717?style=flat-square&logo=github)](https://github.com/sayomiyori)
[![Kwork](https://img.shields.io/badge/Kwork-sayomiyori-ff6600?style=flat-square)](https://kwork.ru/user/sayomiyori)
[![Email](https://img.shields.io/badge/Email-flamxd@mail.ru-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:flamxd@mail.ru)

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

**Core Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Quality & Observability**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

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

<img src="https://github-readme-stats.vercel.app/api?username=sayomiyori&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sayomiyori&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="170"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sayomiyori&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="170"/>

</div>

---

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sayomiyori&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&area_color=58a6ff" width="95%"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sayomiyori&style=flat-square&color=58a6ff&label=Profile+Views" alt="Profile views"/>

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1b27&height=100&section=footer" width="100%"/>
