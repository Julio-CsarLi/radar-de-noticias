radar-de-noticias
funcionamiento de un workflow

Radar de noticias automático (n8n + Gemini AI + Telegram)

¿Qué hace este proyecto?
El sistema monitorea feeds RSS de tecnología, extrae las noticias más recientes, utiliza Inteligencia Artificial para resumir la información, y envía un reporte estructurado directamente a un canal de Telegram.

Arquitectura y Tecnologías
* **Motor de Orquestación:** [n8n](https://n8n.io/)
* **Extracción (Trigger):** Nodos `Schedule` y `RSS Read`
* **Transformación (LLM):** API de Google Gemini (Modelo 2.0 Flash)
* **Carga/Entrega:** API de Telegram
