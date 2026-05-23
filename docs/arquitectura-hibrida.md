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

# ⚙️ Componentes Principales

## 💬 Telegram

Canal principal de interacción entre el usuario y el agente IA.

---

## ⚙️ n8n

Motor de automatización encargado de:
- orquestar workflows
- gestionar lógica conversacional
- ejecutar herramientas
- integrar servicios externos

---

## 🧠 Cohere

Modelo LLM utilizado para:
- comprensión del lenguaje natural
- generación de respuestas
- razonamiento conversacional

---

## 🗄️ PostgreSQL

Utilizado para:
- memoria conversacional
- persistencia de contexto
- historial del usuario

---

## 🗃️ MySQL

Utilizado para:
- registros empresariales RRHH
- consultas SQL
- almacenamiento estructurado

---

## 🔎 Base de Conocimiento

Sistema de recuperación semántica mediante embeddings.

---

# 🔄 Flujo General

```text
Telegram
   ↓
n8n Workflow
   ↓
Agente IA RRHH
   ├── Cohere LLM
   ├── PostgreSQL Memory
   ├── MySQL Retrieval
   └── Knowledge Base
   ↓
Telegram Response
```

---

# 🚀 Beneficios de la Arquitectura

- modularidad
- escalabilidad
- separación de responsabilidades
- integración multi-base de datos
- persistencia conversacional
- consultas empresariales dinámicas