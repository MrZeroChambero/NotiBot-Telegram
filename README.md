# 🤖 NotiBot Telegram

**NotiBot Telegram** es un bot automatizado y ligero que obtiene las noticias más recientes desde fuentes RSS públicas y las envía a un canal o grupo de Telegram en horarios predefinidos. Desarrollado en Node.js, el bot respeta un límite diario de envíos (máximo 5 noticias por día) y evita repetir titulares para ofrecer información variada y actualizada.

## ✨ Características

- 📰 Obtención de noticias desde RSS (ej. BBC Mundo, El País, etc.)
- ⏰ Envío programado en múltiples horarios (configurable)
- 📊 Control de límite diario (por defecto 5 noticias/día)
- 🔁 Prevención de duplicados en el mismo día
- 💾 Persistencia de estado (contador y títulos enviados)
- 🚀 Totalmente gratuito (API de Telegram + alojamiento en la nube con plan free)

## 🛠️ Tecnologías

- Node.js
- node-telegram-bot-api
- node-cron
- rss-parser

## 📦 Despliegue

Puedes alojarlo en servicios gratuitos como **Render** (Cron Jobs), **Cyclic** o **Fly.io**. El bot funciona sin necesidad de un servidor 24/7 gracias a ejecuciones programadas externas.


