# 🔄 Workflow Híbrido

## 📌 Descripción

El workflow híbrido combina:
- automatización
- memoria conversacional
- recuperación SQL
- generación de respuestas IA

Todo dentro de un único flujo orquestado mediante n8n.

---

# ⚙️ Componentes del Workflow

## 💬 Telegram Trigger

Recibe mensajes desde Telegram.

---

## 🤖 Agente Inteligente RRHH

Nodo principal encargado de:
- gestionar contexto
- procesar prompts
- coordinar herramientas
- generar respuestas

---

## 🧠 Motor Conversacional Cohere

Genera respuestas inteligentes utilizando IA conversacional.

---

## 🗄️ Memoria Conversacional RRHH

Mantiene contexto persistente mediante PostgreSQL.

---

## 🗃️ Consulta de Registros RRHH

Ejecuta consultas SQL en MySQL.

---

## 📚 Base de Conocimiento RRHH

Permite recuperación semántica mediante embeddings.

---

## 📤 Send Message

Envía respuestas nuevamente al usuario en Telegram.

---

# 🔄 Flujo General

```text
Telegram Trigger
    ↓
Agente Inteligente RRHH
    ├── Cohere
    ├── PostgreSQL Memory
    ├── MySQL Retrieval
    └── Knowledge Base
    ↓
Telegram Response
```

---

# 🚀 Características

- arquitectura modular
- integración multi-servicio
- recuperación híbrida
- automatización empresarial
- IA conversacional
- persistencia contextual