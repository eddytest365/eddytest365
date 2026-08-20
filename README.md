# 👋 Hola, soy Eddy

**QA Engineer** enfocado en testing de APIs, automatización con Python y documentación técnica de calidad.

Actualmente trabajando en el ecosistema **Mastershop** — plataforma e-commerce con módulos de IA conversacional, gestión de órdenes y logística.

---

## 🛠️ Stack de QA

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

| Área | Herramientas |
|---|---|
| **Automatización API** | pytest · requests · python-dotenv |
| **Automatización E2E** | WebdriverIO · Selenium · Cucumber (Gherkin) · TypeScript |
| **Testing manual** | Postman · Chrome DevTools · cURL |
| **Documentación** | Casos de prueba BRD/DRD · Bug reports · Test plans |
| **Seguridad básica** | XSS · SQL injection · aislamiento multi-tenant |

---

## 📁 Proyectos destacados

### 🤖 [mastershop-agentes-ia-qa](https://github.com/eddytest365/mastershop-agentes-ia-qa)
Suite de automatización para el módulo **Agentes IA** de Mastershop (WhatsApp Business + inbox unificado).

- **53 tests automatizados** cubriendo autenticación, idempotencia, seguridad multi-tenant, conversaciones, plantillas y notificaciones
- **12 bugs reportados** con evidencia, pasos de reproducción y referencia a casos de prueba

### 🛒 [MasterShop-Automation](https://github.com/ByMrFireball/MasterShop-Automation) _(colaborador)_
Suite de pruebas **End-to-End** para la plataforma Mastershop.

- Stack: WebdriverIO · Selenium · Cucumber (Gherkin) · TypeScript · Allure Report
- Estructura POM con Page Objects, Step Definitions y flujos de negocio reutilizables
- Datos de prueba reproducibles con `@faker-js/faker`

### 💬 [mastershop-help-center](https://github.com/LuisFR-23/mastershop-help-center) _(colaborador)_
Sistema de **Q&A inteligente** con búsqueda vectorial y RAG para artículos de ayuda de Mastershop.

- Stack: Next.js 14 · PostgreSQL + pgvector · OpenAI embeddings · GPT-4o Mini
- 60 artículos markdown indexados con similitud coseno

### 🤖 [EddyBot](https://github.com/eddytest365/EddyBot)
Bot de Slack con IA que responde preguntas usando documentación local (RAG).

- Stack: Node.js · JavaScript · ChromaDB · OpenAI
- Desplegado en Northflank

### 📋 [Casos-de-Testing](https://github.com/eddytest365/Casos-de-Testing)
Documentación de casos de prueba y control de cambios para flujos de QA manual.

---

## 🐛 Qué encuentro en mis pruebas

Algunos bugs reales identificados en proyectos activos:

- 🔴 Loops infinitos de 401 por falta de refresh token
- 🔴 Mensajes multimedia (imágenes) no entregados ni renderizados en ambas direcciones
- 🔴 Estado de error engañoso en pantalla (`META_SDK_LOAD_FAILED` vs estado real)
- 🟠 Datos de usuario sin resolver en UI (ID numérico en lugar del nombre)
- 🟡 Búsqueda case-sensitive que genera falsos negativos en inbox

---

## 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=eddytest365&show_icons=true&theme=default&hide_border=true&count_private=true)

---

## 📬 Contacto

¿Quieres saber más sobre mi trabajo o tienes un proyecto de QA?

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/TU-PERFIL)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:TU-EMAIL)
