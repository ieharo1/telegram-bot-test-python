# telegram-bot-test-python

Scripts simples en **Python** para probar la API de **Telegram Bots**, obtener el `chat_id` de un chat o grupo y enviar mensajes de prueba.  
Pensado para ejecutarse en **Google Colab**, pero compatible con cualquier entorno Python.

---

## 🚀 Funcionalidades

- Obtener actualizaciones del bot usando `getUpdates`
- Identificar fácilmente el `chat_id` de usuarios, grupos o canales
- Enviar mensajes de prueba a Telegram
- Ideal para validar bots antes de integrarlos en scripts de:
  - Backups
  - Monitoreo
  - Alertas
  - Automatización DevOps

---

## 🧰 Requisitos

- Python 3.7+
- Librería `requests`
- Un bot creado con **@BotFather** en Telegram

Instalar dependencias:
```bash
pip install requests
