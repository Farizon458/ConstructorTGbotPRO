# Telegram Bot Constructor (MVP, production-style)

## Stack
- Python 3.11+
- pyTelegramBotAPI (telebot)
- SQLAlchemy 2.0 + Alembic
- PostgreSQL (prod) / SQLite (dev)
- APScheduler
- .env via python-dotenv
- logging + rotating files
- docker-compose

---

## Quick start (Docker)
1) Create `.env` from `.env.example`
2) Run:
```bash
docker-compose up -d --build
