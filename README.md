# 📦 StockWise – Skladový systém

Kompletní open-source skladová aplikace využívající **Django + PostgreSQL** na backendu a **Next.js + React + MUI** na frontendu. Umožňuje správu produktů, šarží, operací, pozic, a přináší integraci s **OpenAI** pro pokročilé statistiky a chatbot.

---

## 🚀 Spuštění projektu (lokálně přes Docker)

1. **Zkopíruj `.env` soubor do složky** `be/`.
2. Spusť v rootu:

```bash
docker-compose up --build
```

Aplikace poběží na:
- Frontend: http://localhost:3000
- Backend: http://localhost:8000
- Swagger (API): http://localhost:8000/swagger
