# 🔍 BCV Uptime Monitor

> Website uptime monitor micro-SaaS by Adastra BCV

![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## 🎯 Özellikler

- ⏱️ Website uptime monitoring
- 📊 Response time tracking
- 🔔 Status notifications
- 📈 Historical data & charts
- 🌐 Multi-site monitoring

## 🚀 Teknolojiler

- **Backend:** Node.js / Express
- **Database:** PostgreSQL / Redis
- **Frontend:** React / Next.js
- **Monitoring:** Cron-based health checks
- **Notifications:** Telegram / Email / Webhook

## 📦 Kurulum

\`\`\`bash
# Clone
git clone https://github.com/Garbaun/bcv-uptime.git

# Install dependencies
npm install

# Setup environment
cp .env.example .env

# Run
npm run dev
\`\`\`

## 🔧 Environment Variables

\`\`\`env
DATABASE_URL=postgresql://...
REDIS_URL=redis://...
TELEGRAM_BOT_TOKEN=...
NOTIFICATION_WEBHOOK=...
\`\`\`

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/sites` | GET | List all monitored sites |
| `/api/sites` | POST | Add new site |
| `/api/sites/:id` | DELETE | Remove site |
| `/api/status/:id` | GET | Get site status |
| `/api/history/:id` | GET | Get uptime history |

## 📅 Roadmap

- [ ] Basic uptime monitoring
- [ ] Response time tracking
- [ ] Telegram notifications
- [ ] Web dashboard
- [ ] Multi-user support
- [ ] SSL certificate monitoring
- [ ] Status page generator

## 📝 Lisans

MIT License - Adastra BCV

---

**Adastra BCV** - Global Teknoloji ve Medya Ajansı
