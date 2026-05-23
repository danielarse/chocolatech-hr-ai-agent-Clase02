# 🏗️ Arquitectura Híbrida del Sistema

## 📌 Descripción General

El proyecto implementa una arquitectura híbrida combinando:
- automatización mediante n8n
- inteligencia artificial conversacional
- memoria persistente
- consultas SQL empresariales
- recuperación semántica

La solución integra múltiples servicios cloud y motores de base de datos para distintos propósitos funcionales.

---

# 🔄 Flujo General

```text
n8n Chat Interface
        ↓
When Chat Message Received
        ↓
Agente IA RRHH
   ├── Cohere LLM
   ├── PostgreSQL Memory
   ├── MySQL Retrieval
   └── Knowledge Base
        ↓
Respuesta Conversacional
```