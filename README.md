<h1 align="center">Hola, soy Sebastian Montes Olivera</h1>

<p align="center">
  <strong>Desarrollador Backend Junior</strong> enfocado en Java, Spring Boot y APIs REST seguras, escalables y bien documentadas.
</p>

<p align="center">
  <a href="mailto:sebastianmontesolivera@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/sebastianmontesolivera">LinkedIn</a> ·
  <a href="https://github.com/SebastianMontes-Dev">GitHub</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## Sobre mi

Soy desarrollador backend junior y estudiante de Tecnologia en Desarrollo de Software. Me gusta construir sistemas con una base tecnica solida: autenticacion JWT, control de acceso por roles, arquitectura en capas, principios SOLID, migraciones con Flyway, pruebas automatizadas y despliegues reproducibles con Docker.

He trabajado en APIs REST con Spring Boot, PostgreSQL, MySQL y MongoDB, integrando busqueda, resiliencia, WebSockets, documentacion OpenAPI, CI/CD con GitHub Actions y patrones como Strategy, CQRS y multi-tenancy.

Actualmente busco oportunidades Junior, Trainee o practicas donde pueda aportar construyendo backend limpio, mantenible y orientado a producto.

---

## Stack principal

| Area | Tecnologias |
| --- | --- |
| Backend | Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate |
| Bases de datos | PostgreSQL, MySQL, MongoDB, Flyway |
| APIs | REST, WebSocket/STOMP, Swagger/OpenAPI, Postman |
| Testing y calidad | JUnit 5, Mockito, Testcontainers, GitHub Actions |
| Infraestructura | Docker, Docker Compose, Maven, Gradle |
| Conceptos | SOLID, arquitectura en capas, RBAC, JWT, concurrencia, validacion, excepciones centralizadas |

---

## Proyectos destacados

### NexaSaaS - API Cloud Multi-Tenant E-commerce

API backend para e-commerce B2B con arquitectura multi-tenant, aislamiento hibrido de datos y busqueda optimizada.

**Lo mas relevante:**

- Multi-tenancy con `Hibernate @Filter` para tenants estandar y `AbstractRoutingDataSource` para clientes premium.
- CQRS con sincronizacion asincrona de PostgreSQL hacia Elasticsearch.
- Integracion de pagos con Stripe usando Strategy para facilitar nuevas pasarelas.
- Resiliencia con Resilience4j, Redis, Flyway, Docker y pruebas con JUnit, Mockito y Testcontainers.

**Stack:** Java 21, Spring Boot 3.4.1, PostgreSQL 16, Elasticsearch 8.18, Redis 7.2, Flyway, Resilience4j, Docker.

[Ver repositorio](https://github.com/SebastianMontes-Dev/ecommerce-platform)

---

### MesaQR - Pedidos y pagos por QR para restaurantes

API REST que digitaliza la experiencia de restaurantes: el cliente escanea el QR de su mesa, ordena desde el celular y recibe actualizaciones en tiempo real.

**Lo mas relevante:**

- Codigos QR unicos por mesa y sesiones temporales con tokens UUID.
- Actualizaciones en tiempo real con WebSocket/STOMP para sala y cocina.
- Control de concurrencia con bloqueos pesimistas y reintentos con backoff.
- Observabilidad con Actuator, Micrometer/Prometheus y documentacion Swagger/OpenAPI.

**Stack:** Java 21, Spring Boot 3.3, PostgreSQL, Flyway, WebSocket, Spring Retry, JUnit 5, Mockito, Docker.

[Ver repositorio](https://github.com/SebastianMontes-Dev/MesaQR)

---

### PostgresPulse - Diagnostico y salud de bases PostgreSQL

Plataforma para analizar bases PostgreSQL en modo solo lectura, calcular un indice de salud y entregar recomendaciones tecnicas accionables.

**Lo mas relevante:**

- Diagnosticos sobre rendimiento, almacenamiento, integridad, concurrencia y conexiones.
- Recomendaciones SQL listas para ejecutar, como indices, vacuum y ajustes de esquema.
- Fuentes multiples en tiempo de ejecucion, credenciales cifradas y despliegue con Docker Compose.
- Integracion opcional con Prometheus y Grafana.

**Stack:** Java, Spring Boot, PostgreSQL, Docker, Prometheus, Grafana.

[Ver repositorio](https://github.com/SebastianMontes-Dev/PostgresPulse)

---

### Inventario de Proveedores - SaaS B2B

Plataforma para gestionar proveedores e inventario con backend robusto y frontend moderno.

**Lo mas relevante:**

- API RESTful en Spring Boot con autenticacion segura usando JWT.
- Persistencia con Spring Data JPA y MySQL.
- Frontend SPA con Angular 17 y Angular Material.
- Documentacion interactiva con SpringDoc OpenAPI.

**Stack:** Java 17, Spring Boot, Spring Security, JWT, MySQL 8, Angular 17, Docker.

[Ver repositorio](https://github.com/SebastianMontes-Dev/inventario-proveedores)

---

## Experiencia destacada

### Asistente Academico con IA Generativa - Pasantia de investigacion

Desarrolle un tutor virtual educativo con arquitectura RAG sobre Next.js y MongoDB. El sistema procesa PDFs de clase, genera embeddings con Gemini y responde con base en el material cargado usando Groq y Llama 3.3 70B.

Tambien implemente un modulo de deteccion temprana de desercion escolar que identifica estudiantes inactivos y permite notificarles por correo, apoyando procesos de retencion academica.

---

## Actividad en GitHub

> Este calendario se genera con `lowlighter/metrics` y el plugin `isocalendar`.

<p align="center">
  <img src="./github-metrics.svg" alt="Calendario isometrico de commits de Sebastian Montes" />
</p>

---

## En que estoy enfocado

- Profundizar en backend con Java, Spring Boot y arquitecturas escalables.
- Escribir APIs seguras, testeables y faciles de mantener.
- Mejorar observabilidad, rendimiento y resiliencia en aplicaciones reales.
- Seguir construyendo proyectos con criterio de producto y calidad profesional.
