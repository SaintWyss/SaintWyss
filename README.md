<h1 align="center">Santiago Vicente Scacciaferro Wyss</h1>

<p align="center">
  <strong>Estudiante avanzado de Ingeniería en Sistemas de Información</strong><br/>
  Software · Inteligencia artificial aplicada · Ciberseguridad · Sistemas distribuidos
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/santiago-vicente-scacciaferro-wyss-48b69a223/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sanv.swyss@gmail.com">
    <img src="https://img.shields.io/badge/Contacto-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Correo electrónico" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=SaintWyss&style=flat-square&color=6f42c1" alt="Visitas al perfil" />
</p>

---

## Sobre mí

Soy estudiante de cuarto año de **Ingeniería en Sistemas de Información en la UTN Facultad Regional Resistencia**. Trabajo en la intersección entre ingeniería de software, inteligencia artificial aplicada y seguridad.

Además de desarrollar productos propios, participo como:

- **Becario de investigación en GIESIN**, dentro de una línea de inteligencia artificial aplicada a la educación técnica.
- **Ayudante de cátedra de Algoritmos y Estructuras de Datos**.
- Estudiante de formación especializada en **desarrollo seguro, pentesting web y arquitectura de software**.

Mi objetivo no es construir demostraciones aisladas. Diseño sistemas completos: modelo de dominio, arquitectura, seguridad, pruebas, observabilidad, despliegue, documentación y operación.

## Áreas de trabajo

| Área | En qué trabajo |
|---|---|
| **Inteligencia artificial aplicada** | RAG, agentes, herramientas, memoria, evaluación, citas y automatización controlada. |
| **Ingeniería de software** | Arquitectura limpia y hexagonal, contratos, testing, CI/CD y documentación técnica. |
| **Ciberseguridad** | Modelado de amenazas, RBAC, prevención de IDOR, hardening, auditoría y desarrollo seguro. |
| **Sistemas y automatización** | Linux, servicios, redes locales, control de dispositivos y aplicaciones multiplataforma. |
| **Datos y plataformas** | PostgreSQL, pgvector, Redis, colas, almacenamiento de objetos y observabilidad. |

## Portafolio técnico principal

Estos sistemas se encuentran en repositorios privados mientras completo su productización, seguridad y publicación. Los presento como parte de mi portafolio porque representan mi trabajo actual de ingeniería de extremo a extremo.

### Wyss

Asistente personal multi-dispositivo para controlar y automatizar computadoras, servicios y flujos cotidianos.

- Ciclo completo de solicitud, planificación, política, confirmación, ejecución, verificación y auditoría.
- Modo determinista y soporte para modelos de lenguaje mediante gateway.
- Memoria del propietario, rutinas, resumen diario, integración con Notion e intake mediante n8n.
- PWA, emparejamiento seguro y aplicación Android.
- Confirmaciones obligatorias, journal de ejecución y deshacer cuando la operación lo permite.

### RAG Corp

Plataforma RAG multi-tenant orientada a organizaciones y conocimiento corporativo.

- Ingesta documental, embeddings, búsqueda híbrida, reranking y respuestas con citas.
- Organizaciones, miembros, invitaciones, RBAC, MFA, SSO, API keys y webhooks.
- Conectores, crawler web, observabilidad, evaluación, límites y auditoría.
- Backend FastAPI, frontend Next.js, PostgreSQL con pgvector, Redis y MinIO.

### Pellegrini

Plataforma financiera personal y familiar con dominio determinista e inteligencia artificial basada en evidencia.

- Movimientos, cuentas, presupuestos, hogares y análisis financiero.
- Separación estricta entre cálculos financieros y explicaciones generadas por IA.
- Cifrado, aislamiento por hogar, trazabilidad y clientes web, móvil y escritorio.
- Arquitectura diseñada para evitar que un modelo de lenguaje altere datos financieros por sí solo.

### Sarmiento

Sistema nativo para administrar y controlar computadoras dentro de una red local.

- Aplicación de escritorio, control-plane y agentes instalados en cada equipo.
- Integración con RustDesk para acceso remoto y Deskflow para compartir teclado y mouse.
- Descubrimiento, enrolamiento, rotación de credenciales, estado de equipos y recuperación.
- Diseñado como programa de escritorio, no únicamente como panel web.

### Borjes

Explorador visual de archivos en tres dimensiones desarrollado con Rust y Bevy.

- Navegación por carpetas como constelaciones espaciales.
- Búsqueda global, lentes temáticos, favoritos, pins y ranking por frecuencia y recencia.
- Integración con el escritorio Linux y foco en consumo reducido de recursos.
- Arquitectura basada en ECS para separar datos, comportamiento y representación visual.

### Güemes

Plataforma de entrenamiento físico, progreso personal y competencia social.

- Planes, sesiones, métricas, actividad social y clasificación.
- Funcionamiento offline, sincronización y privacidad de información corporal.
- Controles de fraude, moderación y separación entre datos privados y contenido público.
- API FastAPI, cliente web y persistencia relacional.

### Alberdi

Motor experimental para detectar y ejecutar oportunidades de arbitraje en mercados predictivos.

- Modos scanner, paper trading y operación real claramente separados.
- Cálculo de comisiones, profundidad, libros desactualizados y riesgo máximo.
- Ejecución emparejada, reconciliación y pausa automática ante resultados parciales.
- El sistema prioriza control de riesgo y validación; no promete rentabilidad.

## Investigación y docencia

Formo parte del grupo **GIESIN de UTN FRRe**, trabajando en inteligencia artificial aplicada a educación técnica y aula invertida.

Mi línea de trabajo incluye:

- Diseño y análisis de instrumentos de observación educativa.
- Categorización de evidencias con herramientas de IA generativa.
- Trazabilidad entre observaciones, indicadores, citas y conclusiones.
- Presentación de resultados en **CONAIISI 2024 y 2025**.

Como ayudante de cátedra, trabajo con fundamentos de programación, estructuras de datos, resolución de problemas y buenas prácticas de desarrollo.

## Proyectos públicos

### [Notion File Uploader](https://github.com/SaintWyss/Notion-File-Uploader)

Herramienta en Python y Docker que replica una estructura local de archivos dentro de una base de datos de Notion.

- Sincronización incremental y jerarquía recursiva.
- Arquitectura limpia y separación entre dominio, aplicación e infraestructura.
- Implementación tradicional en Python y alternativa mediante n8n.

### [Bienal del Chaco 2024](https://github.com/SaintWyss/Bienal-del-Chaco-2024)

Aplicación académica full-stack relacionada con la Bienal Internacional de Escultura del Chaco.

- Frontend, autenticación, administración y documentación de API.
- Refactorización con Clean Code, tipos estrictos y organización por funcionalidades.
- Documentación de instalación, arquitectura y trabajo práctico integrador.

## Tecnologías

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111" alt="React" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111111" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

**Backend y datos:** Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, pgvector, Redis, MinIO y SQLite.

**Frontend y clientes:** TypeScript, React, Next.js, Tailwind CSS, PWA, Android y Tauri.

**Sistemas:** Rust, Bevy, Docker Compose, Linux, systemd, redes LAN, RustDesk y Deskflow.

**Calidad y seguridad:** pytest, testing de integración y E2E, contratos OpenAPI, threat modeling, RBAC, auditoría, CI/CD y observabilidad.

## Cómo trabajo

1. **Primero entiendo el problema.** No elijo tecnologías antes de conocer el dominio, los riesgos y las restricciones.
2. **Separo el dominio de la infraestructura.** Un proveedor, framework o modelo de IA debe poder reemplazarse sin destruir la lógica central.
3. **La seguridad forma parte del diseño.** Autorización, validación, límites y auditoría no se agregan al final.
4. **Pruebo lo que afirmo.** Distingo entre implementado, probado, parcialmente validado y pendiente.
5. **Documento para operar.** Incluyo arquitectura, decisiones, configuración, pruebas, despliegue, recuperación e incidentes.
6. **Automatizo con control.** Las acciones sensibles deben tener política, confirmación, evidencia y una estrategia de recuperación.

## Idiomas

- Español: nativo.
- Inglés: lectura y comunicación técnica profesional.

---

<p align="center">
  Construyo sistemas que puedan explicarse, probarse, operarse y mantenerse.
</p>
