<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:101b2e,70:0f2b1e,100:1a3a2a&height=200&section=header&text=sayomiyori&fontSize=50&fontColor=a3d9b1&fontAlignY=35&desc=Python%20Backend%20Developer&descSize=18&descColor=7fb89e&descAlignY=55&animation=fadeIn" width="100%"/>

<!-- TYPING SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=A3D9B1&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=FastAPI+%C2%B7+Django+%C2%B7+PostgreSQL+%C2%B7+Redis+%C2%B7+Docker;Building+production-ready+backend+services" alt="Typing SVG" /></a>

<br/>

<!-- SOCIAL BADGES -->
[![GitHub](https://img.shields.io/badge/GitHub-sayomiyori-161b22?style=flat-square&logo=github&logoColor=a3d9b1)](https://github.com/sayomiyori)
[![Kwork](https://img.shields.io/badge/Kwork-sayomiyori-161b22?style=flat-square&logo=freelancer&logoColor=a3d9b1)](https://kwork.ru/user/sayomiyori)
[![Email](https://img.shields.io/badge/Email-flamxd@mail.ru-161b22?style=flat-square&logo=gmail&logoColor=a3d9b1)](mailto:flamxd@mail.ru)

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

![Python](https://img.shields.io/badge/Python-1a2332?style=for-the-badge&logo=python&logoColor=a3d9b1)
![FastAPI](https://img.shields.io/badge/FastAPI-1a2332?style=for-the-badge&logo=fastapi&logoColor=a3d9b1)
![Django](https://img.shields.io/badge/Django-1a2332?style=for-the-badge&logo=django&logoColor=a3d9b1)
![DRF](https://img.shields.io/badge/DRF-1a2332?style=for-the-badge&logo=django&logoColor=a3d9b1)

**`Data & Messaging`**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a2332?style=for-the-badge&logo=postgresql&logoColor=a3d9b1)
![Redis](https://img.shields.io/badge/Redis-1a2332?style=for-the-badge&logo=redis&logoColor=a3d9b1)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-1a2332?style=for-the-badge&logo=rabbitmq&logoColor=a3d9b1)
![Celery](https://img.shields.io/badge/Celery-1a2332?style=for-the-badge&logo=celery&logoColor=a3d9b1)

**`Infrastructure & DevOps`**

![Docker](https://img.shields.io/badge/Docker-1a2332?style=for-the-badge&logo=docker&logoColor=a3d9b1)
![Nginx](https://img.shields.io/badge/Nginx-1a2332?style=for-the-badge&logo=nginx&logoColor=a3d9b1)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1a2332?style=for-the-badge&logo=githubactions&logoColor=a3d9b1)
![Linux](https://img.shields.io/badge/Linux-1a2332?style=for-the-badge&logo=linux&logoColor=a3d9b1)

**`Quality & Observability`**

![Pytest](https://img.shields.io/badge/Pytest-1a2332?style=for-the-badge&logo=pytest&logoColor=a3d9b1)
![Prometheus](https://img.shields.io/badge/Prometheus-1a2332?style=for-the-badge&logo=prometheus&logoColor=a3d9b1)
![Grafana](https://img.shields.io/badge/Grafana-1a2332?style=for-the-badge&logo=grafana&logoColor=a3d9b1)
![Sentry](https://img.shields.io/badge/Sentry-1a2332?style=for-the-badge&logo=sentry&logoColor=a3d9b1)

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

## 🧠 Architecture Decisions

> Why this stack? Every choice is intentional.

**TaskFlow** — Django for ORM-heavy domain logic (models, permissions, admin) + FastAPI for the async notification consumer. Each framework where it's strongest. RabbitMQ topic exchange instead of direct HTTP calls — write-side transactions stay decoupled from delivery, and adding new event handlers doesn't touch core API code.

**WebHook Manager** — Celery with Redis broker for delivery retries because webhooks are fire-and-forget by nature — the caller shouldn't wait. Circuit breaker in Redis prevents hammering a dead endpoint. HMAC + idempotency key at the intake layer, not in business logic — infrastructure concern stays in infrastructure.

**RealTimeChat** — Redis Pub/Sub instead of in-memory broadcast because in-memory only works within a single process. With Pub/Sub, scaling to N replicas is transparent — each instance subscribes to room channels and fans out locally. WebSocket auth via query param token, not headers, because browsers don't support custom headers on WS handshake.

**BookFinder API** — Async SQLAlchemy 2 + asyncpg instead of sync ORM because the main bottleneck is I/O (database + Google Books API). Prometheus from day one, not as an afterthought — error rate spike is visible in the dashboard before the first bug report arrives.

**ChillLibrary / BodyTelling** — Commercial projects built to spec. Layered architecture (handlers → services → utils) so the client's next developer can onboard without a call. Deployed on Railway with Docker — client doesn't need to maintain infrastructure.

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sayomiyori&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a3d9b1&icon_color=7fb89e&text_color=b0b8c4&ring_color=a3d9b1" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sayomiyori&layout=compact&hide_border=true&bg_color=0d1117&title_color=a3d9b1&text_color=b0b8c4&langs_count=8" height="170"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sayomiyori&hide_border=true&background=0d1117&stroke=1e2a3a&ring=a3d9b1&fire=7fb89e&currStreakLabel=a3d9b1&sideLabels=7fb89e&currStreakNum=b0b8c4&sideNums=b0b8c4&dates=4a5568" height="170"/>

</div>

---

## 🧊 3D Contribution Calendar

<div align="center">

<img src="./profile-3d-contrib/profile-night-green.svg" width="100%"/>

</div>

---

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sayomiyori&hide_border=true&bg_color=0d1117&color=a3d9b1&line=7fb89e&point=a3d9b1&area=true&area_color=1a3a2a" width="95%"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sayomiyori&style=flat-square&color=7fb89e&label=Profile+Views" alt="Profile views"/>

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:101b2e,70:0f2b1e,100:1a3a2a&height=100&section=footer" width="100%"/>
