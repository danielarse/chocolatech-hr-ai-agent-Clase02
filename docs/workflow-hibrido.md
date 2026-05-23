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

## 💬 When Chat Message Received

Nodo trigger conversacional encargado de iniciar el workflow cuando el usuario interactúa mediante el chat integrado de n8n.

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

# 🔄 Flujo General

```text
When Chat Message Received
        ↓
Agente Inteligente RRHH
    ├── Cohere
    ├── PostgreSQL Memory
    ├── MySQL Retrieval
    └── Knowledge Base
        ↓
Respuesta Conversacional
```