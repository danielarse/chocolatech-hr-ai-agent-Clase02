# 🗃️ Integración MySQL

## 📌 Objetivo

La integración MySQL permite al agente IA consultar registros empresariales relacionados con Recursos Humanos.

---

# ⚙️ Funcionalidades

- consultas SQL automatizadas
- recuperación de registros
- integración con herramientas IA
- acceso estructurado a datos

---

# ☁️ Infraestructura

La base de datos MySQL se encuentra desplegada en Railway.

---

# 🔄 Flujo de Consulta

```text
Usuario Telegram
    ↓
Agente IA
    ↓
Herramienta SQL Retrieval
    ↓
MySQL Railway
    ↓
Resultado SQL
    ↓
Respuesta IA
```

---

# 📚 Casos de Uso

- consulta de empleados
- información RRHH
- registros internos
- automatización administrativa

---

# 🔒 Seguridad

Las credenciales se administran mediante variables de entorno y no son almacenadas en el repositorio.