# LTI Project – Historias de Usuario y Planificación Inicial

---

## ✅ Punto 1: Historias de Usuario Iniciales para el Proyecto LTI

### 🔹 Historia 1: Creación de Vacantes

**Título de la Historia de Usuario:**  
Creación estructurada y centralizada de vacantes

**Como** reclutador,  
**quiero** poder crear ofertas de trabajo mediante formularios estructurados,  
**para que** pueda publicar fácilmente vacantes con información clara y consistente.

**Criterios de Aceptación:**

- El sistema debe permitir crear una oferta con campos como título, descripción, requisitos, tipo de contrato, etc.
- El sistema debe permitir guardar una vacante como borrador antes de publicarla.
- El sistema debe validar los campos obligatorios antes de permitir la publicación.

**Notas Adicionales:**  
Esta historia habilita la funcionalidad básica del sistema. No incluye publicación en canales externos (eso está en otra historia).

**Historias de Usuario Relacionadas:**  
- Publicación multicanal de vacantes  
- Edición y seguimiento de vacantes activas  

---

### 🔹 Historia 3: Registro de Candidaturas

**Título de la Historia de Usuario:**  
Recepción y visualización de candidaturas

**Como** reclutador,  
**quiero** que las postulaciones a las vacantes se almacenen automáticamente en LTI,  
**para que** pueda revisarlas centralizadas y sin duplicidades.

**Criterios de Aceptación:**

- Alguien que se postule a una vacante (desde cualquier canal) debe crear automáticamente una candidatura.
- El sistema debe asociar la candidatura con la vacante correspondiente.
- El reclutador debe poder acceder al CV del candidato y datos parseados.

**Notas Adicionales:**  
La postulación externa puede simularse mediante carga manual en la fase 1. Se irá automatizando con integraciones posteriores.

**Historias de Usuario Relacionadas:**  
- Matching automático  
- Recomendación de candidatos  

---

## ✅ Punto 2: Backlog de Producto

### 📌 Metodología de Priorización: MoSCoW

Se clasifican las historias en Must Have, Should Have, Could Have.

---

### 🎯 Backlog para Historia 1: Creación de Vacantes

| ID | Título | Tipo | Prioridad | Descripción Corta |
|----|--------|------|-----------|-------------------|
| US-001 | Crear formulario de vacantes | User Story | Must Have | Permite introducir los campos principales: título, descripción, requisitos, ubicación, etc. |
| US-002 | Validación de campos del formulario | User Story | Must Have | El sistema valida que los campos obligatorios estén completos. |
| US-003 | Guardar como borrador | User Story | Should Have | El usuario puede guardar una vacante sin publicarla. |
| US-004 | Editar vacante existente | User Story | Should Have | El reclutador puede reabrir una vacante y editar campos antes de publicarla. |
| US-005 | Asistente IA de descripción | User Story | Could Have | El sistema sugiere contenido en base a roles similares. |
| US-006 | Plantillas de vacantes | User Story | Could Have | Posibilidad de reutilizar una vacante como plantilla para futuras. |

---

### 🎯 Backlog para Historia 3: Registro de Candidaturas

| ID | Título | Tipo | Prioridad | Descripción Corta |
|----|--------|------|-----------|-------------------|
| US-010 | Registro automático de candidatura | User Story | Must Have | Toda postulación debe crear automáticamente una candidatura vinculada a una vacante. |
| US-011 | Asociación de candidatura a la oferta correcta | User Story | Must Have | El sistema debe vincular la candidatura con la vacante que originó la postulación. |
| US-012 | Visualización de perfil de candidato | User Story | Must Have | Los datos parseados del CV deben mostrarse junto a la candidatura. |
| US-013 | Registro del canal de origen | User Story | Should Have | El sistema debe guardar de qué canal proviene la aplicación (LinkedIn, portal interno, etc.). |
| US-014 | Carga manual de CVs | User Story | Could Have | Posibilidad de registrar candidatos recibidos por email o ferias. |
| US-015 | Parseo automático de CV | User Story | Should Have | El sistema extrae datos clave del CV para mostrar un resumen rápido. |

---

## ✅ Punto 3: Tickets Técnicos Iniciales

### 🛠 Para Historia 1

| Ticket ID | Título | Tipo | Descripción | Justificación |
|-----------|--------|------|-------------|----------------|
| DEV-001 | Crear entidad "JobOpening" en backend | Backend | Modelar en base de datos la entidad `Oferta`. | Fundacional. |
| DEV-002 | API REST: Crear, editar y consultar vacantes | Backend | Endpoint `POST /job`, `GET /job/{id}`, `PUT /job/{id}`. | Necesario para integración. |
| DEV-003 | Formulario UI de creación de vacantes | Frontend | Construir el formulario en la app web. | Interfaz principal. |
| DEV-004 | Conexión frontend–backend para vacantes | Frontend | Llamadas a la API. | Persistencia real. |
| DEV-005 | Modelo de permisos: validación de acceso por rol | Backend | Permisos para `Recruiter` y `Admin`. | Control de acceso. |

### 🛠 Para Historia 3

| Ticket ID | Título | Tipo | Descripción | Justificación |
|-----------|--------|------|-------------|----------------|
| DEV-006 | Crear entidad "Candidate" y "Application" | Backend | Modelo relacional con atributos clave. | Estructura del sistema. |
| DEV-007 | Endpoint API para registrar candidatura | Backend | `POST /application` con carga de CV. | Entrada principal. |
| DEV-008 | Parseo básico de CVs en backend | Backend | Parseo PDF/Word a texto. | Experiencia reclutador. |
| DEV-009 | Visualización de candidaturas en UI | Frontend | Listado por vacante, acceso al CV. | Visibilidad operativa. |
| DEV-010 | Lógica de asociación oferta–candidatura | Backend | Validación por ID. | Integridad del sistema. |
| DEV-011 | Validación de duplicados por email y oferta | Backend | Control de integridad. | Previene ruido de datos. |

---

## ✅ Punto 4: Estimación del Esfuerzo

### 📌 Metodología usada: Planning Poker + Story Points

| Ticket ID | Título | Story Points (SP) | Est. en horas | Justificación |
|-----------|--------|-------------------|----------------|----------------|
| DEV-001 | Crear entidad "JobOpening" | 3 SP | 6 h | Modelo simple. |
| DEV-002 | API REST para vacantes | 5 SP | 10–12 h | Lógica de negocio. |
| DEV-003 | Formulario UI de vacantes | 5 SP | 10 h | Validaciones incluidas. |
| DEV-004 | Conexión frontend–backend | 3 SP | 6 h | Llamadas básicas. |
| DEV-005 | Control de acceso por rol | 2 SP | 3–4 h | Middleware. |
| DEV-006 | Modelo Candidate y Application | 5 SP | 10 h | Dos entidades. |
| DEV-007 | API para registrar candidatura | 5 SP | 10–12 h | Incluye carga de archivos. |
| DEV-008 | Parseo básico de CVs | 5 SP | 8–10 h | Parsing simple. |
| DEV-009 | UI de candidaturas por vacante | 3 SP | 6 h | Tabla y acceso al CV. |
| DEV-010 | Asociación oferta–candidatura | 2 SP | 3–4 h | Validación sencilla. |
| DEV-011 | Validación de duplicados | 2 SP | 3 h | Control de duplicados. |

**Totales:**
- Total SP: 45 SP
- Total estimado: ~85–95 h