
# Proyecto LTI - Historias de Usuario, Backlog, Tickets Técnicos y Estimación

## ✅ Punto 1: Historias de Usuario basadas en el PRD

### Historia de Usuario 1: Registro Manual de Candidatos en el Sistema

**Título de la Historia de Usuario:**  
Como Reclutador,  
quiero registrar manualmente perfiles de candidatos en el sistema,  
para que pueda comenzar procesos de selección incluso sin haber publicado la vacante en ningún portal.

**Criterios de Aceptación:**

- El sistema debe ofrecer un formulario para crear un nuevo perfil de candidato desde cero.
- El reclutador debe poder adjuntar el CV del candidato y añadir información clave: nombre, email, experiencia, habilidades, comentarios internos, etc.
- El CV debe ser parseado automáticamente para extraer datos estructurados básicos.
- El candidato creado debe poder asociarse inmediatamente a una oferta de trabajo activa o futura.
- El perfil debe quedar disponible en la base de talento de la empresa para futuras búsquedas y seguimiento.

**Notas Adicionales:**

- Esta funcionalidad permite registrar candidatos referenciados, conocidos en eventos, recibidos por email o encontrados en LinkedIn fuera del sistema.
- El formulario debe ser accesible desde el módulo de “Candidatos” o desde una vacante específica.

**Historias de Usuario Relacionadas:**

- Asociación de candidatos a una vacante.
- Evaluación colaborativa del candidato.
- Consulta y filtrado de la base de talento.

---

### Historia de Usuario 2: Consulta Básica de Candidatos por Filtros

**Título de la Historia de Usuario:**  
Como Reclutador,  
quiero poder buscar candidatos existentes en la base de datos usando filtros simples,  
para que pueda identificar rápidamente perfiles relevantes sin tener que revisar uno por uno.

**Criterios de Aceptación:**

- El sistema debe mostrar una lista de todos los candidatos registrados (manual o automáticamente).
- Se debe poder aplicar filtros por campos como: puesto deseado, experiencia previa, tecnologías clave, fecha de alta o estado.
- Los resultados deben poder ordenarse por fecha de registro o nombre.
- El usuario debe poder acceder al perfil completo del candidato desde los resultados.

**Notas Adicionales:**

- Este MVP no requiere recomendación automática por IA, solo búsqueda básica.
- En el futuro se podrá añadir ranking por “matching” o sugerencias inteligentes.

**Historias de Usuario Relacionadas:**

- Registro manual de candidatos.
- Asociación de candidatos a procesos activos.
- Evaluación posterior de candidatos.

---

## ✅ Punto 2: Backlog de Producto (Revisado y Ampliado)

### 🎯 Metodología de Priorización: MoSCoW + Riesgo/Oportunidad

| Prioridad | Historia de Usuario | Descripción breve | MoSCoW | Valor | Complejidad | Justificación |
|----------|---------------------|-------------------|--------|-------|-------------|----------------|
| 🥇 1 | **Creación de Vacantes Manualmente** | Permite a un reclutador crear una oferta de trabajo sin necesidad de publicarla externamente. | Must | Alta | Media | Es la base para poder asociar candidatos a un proceso, aunque el foco inicial no sea la publicación. |
| 🥈 2 | **Registro Manual de Candidatos** | Permite ingresar perfiles en el sistema desde fuera del flujo tradicional. | Must | Alta | Media | Llena el sistema de contenido valioso desde el inicio sin necesidad de integraciones externas. |
| 🥉 3 | **Consulta Básica de Candidatos** | Visualización y búsqueda por filtros simples (nombre, puesto, habilidades, etc.). | Must | Alta | Baja | Hace operativa la base de talento. Es esencial para no perder el valor del registro. |
| 4 | **Asociar candidato a vacante existente** | Vincular perfiles con procesos de selección activos o en preparación. | Should | Media | Baja | Permite estructurar flujos de selección, entrevistas y análisis más adelante. |
| 5 | **Evaluación manual básica de candidatos** | Posibilidad de agregar feedback textual o calificaciones por parte del equipo. | Could | Media | Media | Imprescindible a futuro para decisiones compartidas, pero no bloqueante en el MVP. |
| 6 | **Autoetiquetado por skills desde CV** | Asignación automática de etiquetas desde el parsing del CV. | Won’t (por ahora) | Alta | Alta | Alta complejidad técnica. Depende de procesamiento de lenguaje natural e IA no priorizado ahora. |

### 🔄 Nueva Secuencia de Implementación por Sprints

| Iteración | Objetivo | Historias incluidas |
|-----------|----------|----------------------|
| Sprint 1 | **Base operativa del sistema** | Historia 1: Crear vacantes manuales |
| Sprint 2 | **Captura de talento inicial** | Historia 2: Registro manual de candidatos |
| Sprint 3 | **Consulta y organización básica** | Historia 3: Búsqueda de candidatos + Historia 4: Asociación con vacantes |
| Sprint 4 | **Colaboración sobre candidatos** | Historia 5: Evaluación manual |

---

## ✅ Punto 3: Tickets Técnicos Iniciales

### 🧱 Módulo: Gestión de Vacantes (Sprint 1)

- **TICKET 1.1 – Backend: Modelo de datos y API de Vacante**  
  Descripción: diseñar modelo de datos `Vacante` y exponer endpoints RESTful para CRUD.  
  Justificación: base para todo el sistema.

- **TICKET 1.2 – Frontend: Formulario de creación de vacantes**  
  Descripción: interfaz para crear ofertas internas.  
  Justificación: primera pantalla operativa del sistema.

### 👤 Módulo: Gestión de Candidatos (Sprint 2)

- **TICKET 2.1 – Backend: Modelo y API para candidatos**  
  Descripción: entidad `Candidato`, subida de CV, parseo básico.  
  Justificación: almacenamiento del perfil desde el día 1.

- **TICKET 2.2 – Frontend: Formulario de alta de candidatos**  
  Descripción: interfaz con carga de CV y campos clave.

### 🔍 Módulo: Búsqueda de candidatos (Sprint 3)

- **TICKET 3.1 – Backend: Endpoint de búsqueda y filtros básicos**  
  Descripción: búsqueda en base de candidatos por campos clave.

- **TICKET 3.2 – Frontend: Lista y búsqueda de candidatos**  
  Descripción: listado con filtros rápidos y navegación.

### 🔗 Módulo: Asociación de Candidatos a Vacantes (Sprint 3)

- **TICKET 4.1 – Backend: Vinculación candidato ↔ vacante**  
  Descripción: creación de entidad `Candidatura` y lógica relacional.

- **TICKET 4.2 – Frontend: Selección de vacante al registrar o editar candidato**  
  Descripción: asignación contextual desde UI.

### 📝 Módulo: Evaluaciones Básicas (Sprint 4)

- **TICKET 5.1 – Backend: Entidad y API de evaluación**  
  Descripción: estructura de evaluación (texto, puntuación).

- **TICKET 5.2 – Frontend: Formulario de evaluación manual**  
  Descripción: interfaz desde perfil de candidato.

---

## ✅ Punto 4: Estimación del Esfuerzo

### 🎯 Metodología utilizada: Planning Poker con Story Points + Horas

- Story Points (SP): escala Fibonacci (1, 2, 3, 5, 8, 13)
- Horas: promedio conservador de 1 SP ≈ 4–6 horas

### Estimación por Ticket

| Ticket | Descripción | SP | Horas estimadas | Notas |
|--------|-------------|----|------------------|-------|
| 1.1 | Backend: Modelo y API de Vacante | 5 | 24 h | |
| 1.2 | Frontend: Formulario de vacantes | 3 | 12 h | |
| 2.1 | Backend: Modelo/API de Candidato + CV parseo | 8 | 32 h | |
| 2.2 | Frontend: Alta de candidato | 5 | 20 h | |
| 3.1 | Backend: Búsqueda y filtros | 3 | 12 h | |
| 3.2 | Frontend: Lista/filtros candidatos | 3 | 12 h | |
| 4.1 | Backend: Asociación candidato-vacante | 5 | 20 h | |
| 4.2 | Frontend: Asociación en UI | 3 | 12 h | |
| 5.1 | Backend: Evaluación | 3 | 12 h | |
| 5.2 | Frontend: Evaluación manual | 2 | 8 h | |

### Totales

- **Total Story Points:** 50 SP  
- **Total en Horas:** ~164 h  
- **Duración sugerida (2 devs full-time):** ~2 semanas  
- **Duración sugerida (1 dev full-time):** ~4 semanas  

---

**Fin del documento**
