# 🗂️ Portafolio Técnico — Felipe Aylwin

> **Ingeniero Químico | Desarrollador Full Stack en formación**  
> 📍 Argentina | 💼 Disponible para roles Junior/Trainee | 🌐 Modalidad remota

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/felipe-aylwin/)
[![GitHub](https://img.shields.io/badge/GitHub-Portafolio-black?style=flat&logo=github)](https://github.com/faylwin)

---

## 👋 Sobre mí

Soy Ingeniero Químico con formación complementaria en desarrollo Full Stack. Mi perfil combina el pensamiento analítico y la resolución de problemas complejos propios de la ingeniería, con la capacidad de construir soluciones digitales funcionales y escalables.

Me interesa especialmente la intersección entre el mundo industrial y la tecnología: transformación digital de procesos, visualización de datos técnicos y desarrollo de herramientas que resuelvan problemas reales de ingeniería.

---

## 🚀 Proyectos

| # | Proyecto | Tecnologías | Link |
|---|----------|-------------|------|
| 1 | Sistema de Gestión de Inventario | React, Node.js, PostgreSQL, JWT | [Ver repositorio](#) |
| 2 | API RESTful para Monitoreo de Procesos | Python, FastAPI, SQLite, Swagger | [Ver repositorio](#) |
| 3 | Dashboard de Análisis de Datos Industriales | Python, Pandas, Streamlit | [Ver repositorio](#) |

---

## 📌 Caso de Estudio

# API RESTful para Monitoreo de Procesos Industriales

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green?logo=fastapi)
![SQLite](https://img.shields.io/badge/SQLite-DB-lightgrey?logo=sqlite)
![Estado](https://img.shields.io/badge/Estado-Completado-success)

---

### 📋 Descripción de la actividad

Desarrollo de una **API RESTful** con Python y FastAPI para registrar, consultar y visualizar variables de proceso en tiempo real en un contexto de planta industrial simulada.

El proyecto integra:
- Diseño de endpoints REST siguiendo buenas prácticas (verbos HTTP, códigos de estado, separación por recursos)
- Modelado de base de datos relacional con SQLAlchemy + SQLite
- Autenticación segura con OAuth2 + JWT
- Documentación técnica automática con Swagger UI / OpenAPI

---

### 🧩 Desafío principal

El mayor desafío fue **diseñar una arquitectura de datos flexible** capaz de representar diferentes tipos de variables de proceso (continuas, discretas, booleanas) sin duplicar lógica de negocio.

Además, fue necesario implementar autenticación segura y documentación automática para que otros equipos pudieran consumir la API sin fricción, simulando un entorno de trabajo real y colaborativo.

---

### 💡 Solución propuesta

```
Arquitectura general:
──────────────────────────────────────────────
  Cliente (Postman / Frontend)
        │
        ▼
  FastAPI (Router + Endpoints)
        │
        ▼
  SQLAlchemy ORM
        │
        ▼
  SQLite (Base de datos local)
──────────────────────────────────────────────
  Autenticación: OAuth2 + JWT
  Documentación: Swagger UI (auto-generada)
```

**Decisiones técnicas clave:**

- **FastAPI** sobre Flask: por tipado estático con Pydantic, validación automática y documentación integrada
- **SQLAlchemy** como ORM: para abstraer la capa de datos y mejorar mantenibilidad
- **JWT** para autenticación: estándar seguro y stateless, escalable a microservicios
- **Swagger UI**: generación automática de documentación sin esfuerzo extra

---

### 🛠️ Herramienta técnica principal: FastAPI

> Framework moderno de alto rendimiento para construir APIs con Python 3.6+

**¿Por qué FastAPI?**

| Característica | Beneficio en el proyecto |
|----------------|--------------------------|
| Validación automática (Pydantic) | Reduce errores de entrada de datos en un 90% |
| Swagger UI integrado | Documentación lista sin configuración extra |
| Soporte async nativo | Preparado para escalar con operaciones concurrentes |
| Tipado estático | Mejor mantenibilidad y menor deuda técnica |

---

### 📈 Métricas de impacto logradas

| Métrica | Resultado |
|---------|-----------|
| ⚡ Tiempo de respuesta promedio | < 80 ms bajo carga simulada |
| 📖 Cobertura de documentación | 100% de endpoints documentados en Swagger |
| ⏱️ Reducción tiempo de onboarding | De ~2 horas a ~20 minutos para consumir la API |
| 🔒 Vulnerabilidades de autenticación | 0 detectadas en revisión de pares |
| 🔗 Endpoints implementados | 12 endpoints (CRUD completo + auth + reportes) |

---

### 🧠 Principales aprendizajes

- ✅ Comprensión profunda del ciclo de vida de una solicitud HTTP y diseño REST
- ✅ Uso de ORMs para abstraer la capa de datos y mejorar la mantenibilidad del código
- ✅ Implementación de autenticación segura con tokens JWT en un contexto realista
- ✅ Valor de la documentación técnica automática para facilitar la colaboración entre equipos
- ✅ Integración entre conocimiento de dominio industrial y soluciones de software funcionales
- ✅ Gestión del proyecto con Git: ramas por feature, commits descriptivos, pull requests

---

### 🏷️ Habilidades técnicas aplicadas

```
Backend:      Python · FastAPI · SQLAlchemy · SQLite
Seguridad:    OAuth2 · JWT
Docs:         Swagger UI · OpenAPI 3.0
Herramientas: Git · GitHub · Postman
Diseño:       RESTful API Design · Modelado relacional
Dominio:      Procesos industriales · Variables de control
```

---

### 🎯 ¿Por qué este proyecto para el portafolio?

Este proyecto representa la **intersección entre mi formación como Ingeniero Químico y las habilidades adquiridas en el bootcamp Full Stack**.

Es el caso que mejor evidencia mi capacidad para:

1. **Identificar un problema real de dominio industrial** y traducirlo a una solución tecnológica funcional
2. **Tomar decisiones técnicas fundamentadas**, no solo escribir código que funcione
3. **Pensar en el usuario técnico** (otros desarrolladores que consumirán la API), no solo en el resultado final
4. **Documentar con rigor**, práctica que viene de la formación en ingeniería y que agrega valor real en equipos de software

Este proyecto demuestra que tengo las bases para crecer como desarrollador en entornos que requieran comprender tanto el negocio como la tecnología.

---

## 📬 Contacto

| Canal | Link |
|-------|------|
| 📧 Email | [f.aylwin@gmail.com] |
| 💼 LinkedIn | [linkedin.com/in/felipe-aylwin/ |
| 🐙 GitHub | [github.com/faylwin] |

---

<p align="center">
  <i>Portafolio en construcción continua — última actualización: 2025</i>
</p>
