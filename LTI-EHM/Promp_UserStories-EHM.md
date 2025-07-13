# User

<span class="" data-state="closed"><a target="_blank" rel="noreferrer" class="cursor-pointer"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36 36" fill="none" class="h-10 w-10 shrink-0" width="36" height="36"><rect width="36" height="36" rx="6" fill="#0088FF"></rect><path d="M18.833 9.66663H12.9997C12.5576 9.66663 12.1337 9.84222 11.8212 10.1548C11.5086 10.4673 11.333 10.8913 11.333 11.3333V24.6666C11.333 25.1087 11.5086 25.5326 11.8212 25.8451C12.1337 26.1577 12.5576 26.3333 12.9997 26.3333H22.9997C23.4417 26.3333 23.8656 26.1577 24.1782 25.8451C24.4907 25.5326 24.6663 25.1087 24.6663 24.6666V15.5L18.833 9.66663Z" stroke="white" stroke-width="1.66667" stroke-linecap="round" stroke-linejoin="round"></path><path d="M18.833 9.66663V15.5H24.6663" stroke="white" stroke-width="1.66667" stroke-linecap="round" stroke-linejoin="round"></path></svg>LTI-EHM.mdArchivo</a>El fichero adjunto LTI-EHM.md es el PRD del proyecto.

Teniendo en cuenta como patrón la siguiente estructura como historia de usuario:

**INICIO ejemplo historia de usuario
Título de la Historia de Usuario: 

Como [rol del usuario],
quiero [acción que desea realizar el usuario],
para que [beneficio que espera obtener el usuario].
Criterios de Aceptación:

[Detalle específico de funcionalidad]
[Detalle específico de funcionalidad]
[Detalle específico de funcionalidad]
Notas Adicionales:

[Cualquier consideración adicional]
Historias de Usuario Relacionadas:

[Relaciones con otras historias de usuario]
**FIN ejemplo historia de usuario


Necesito que te comportes como dos roles según consideres necesario,  Product Manager y Business Analyst, ambos muy experimentados y capaces.

El objetivo es lograr 4 puntos clave, y no pasaremos de uno al siguiente sin que te de el "ok".

1. Necesitamos Generar las User Stories para este proyecto basándose en el PRD. 
Priorízamelas por viabilidad para empezar a trabajar con ellas, para que no se generen dependencias de historias futuras.
Usa la plantilla definida para generar la salida.
Y lístamelas para que pueda elegir 2.

2. Arma el Backlog de producto con las User Stories definidas en el punto 1, priorizándolas como consideres conveniente acorde a alguna metodología concreta.

3. Con las historias de usuario generadas en el punto 1, genera los Tickets de trabajo que consideres necesarios para arrancar el proyecto técnicamente, y justifícame el porque de cada ticket.

4. Una vez completado el punto 3, estima el esfuerzo de los tickets de trabajo usando la metodología que consideres (justificándola) y las unidades (horas y puntos de historia) que se precisan para cada ticket.

--------------------------------------

# ChatGPT

<p data-start="0" data-end="77">Perfecto, ya tengo toda la información del PRD del sistema LTI para comenzar.</p>
<hr data-start="79" data-end="82">
<h2 data-start="84" data-end="149">✅ Punto 1: Historias de Usuario Iniciales para el Proyecto LTI</h2>
<p data-start="151" data-end="266">Como Product Manager y Business Analyst, he descompuesto el PRD en funcionalidades clave y priorizado aquellas que:</p>

<ul data-start="268" data-end="440">
<li data-start="268" data-end="309">
<p data-start="270" data-end="309">Pueden desarrollarse de forma autónoma.</p>

<li data-start="310" data-end="352">
<p data-start="312" data-end="352">Representan el núcleo del sistema (MVP).</p>

<li data-start="353" data-end="440">
<p data-start="355" data-end="440">No dependen de funcionalidades más avanzadas (IA, reportes, integraciones profundas).</p>


<p data-start="442" data-end="583">A continuación, te presento una primera tanda de <strong data-start="491" data-end="544">6 historias de usuario priorizadas por viabilidad</strong>, siguiendo la plantilla que indicaste.</p>
<hr data-start="585" data-end="588">
<h3 data-start="590" data-end="629">🔹 Historia 1: Creación de Vacantes</h3>
<p data-start="631" data-end="719"><strong data-start="631" data-end="668">Título de la Historia de Usuario:</strong>

Creación estructurada y centralizada de vacantes</p>
<p data-start="721" data-end="908"><strong data-start="721" data-end="729">Como</strong> reclutador,

<strong data-start="744" data-end="754">quiero</strong> poder crear ofertas de trabajo mediante formularios estructurados,

<strong data-start="824" data-end="836">para que</strong> pueda publicar fácilmente vacantes con información clara y consistente.</p>
<p data-start="910" data-end="938"><strong data-start="910" data-end="938">Criterios de Aceptación:</strong></p>

<ul data-start="940" data-end="1221">
<li data-start="940" data-end="1055">
<p data-start="942" data-end="1055">El sistema debe permitir crear una oferta con campos como título, descripción, requisitos, tipo de contrato, etc.</p>

<li data-start="1056" data-end="1137">
<p data-start="1058" data-end="1137">El sistema debe permitir guardar una vacante como borrador antes de publicarla.</p>

<li data-start="1138" data-end="1221">
<p data-start="1140" data-end="1221">El sistema debe validar los campos obligatorios antes de permitir la publicación.</p>


<p data-start="1223" data-end="1379"><strong data-start="1223" data-end="1245">Notas Adicionales:</strong>

Esta historia habilita la funcionalidad básica del sistema. No incluye publicación en canales externos (eso está en otra historia).</p>
<p data-start="1381" data-end="1421"><strong data-start="1381" data-end="1419">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="1422" data-end="1506">
<li data-start="1422" data-end="1460">
<p data-start="1424" data-end="1460">Publicación multicanal de vacantes</p>

<li data-start="1461" data-end="1506">
<p data-start="1463" data-end="1506">Edición y seguimiento de vacantes activas</p>


<hr data-start="1508" data-end="1511">
<h3 data-start="1513" data-end="1566">🔹 Historia 2: Gestión del Pipeline de Candidatos</h3>
<p data-start="1568" data-end="1653"><strong data-start="1568" data-end="1605">Título de la Historia de Usuario:</strong>

Gestión visual del estado de cada candidatura</p>
<p data-start="1655" data-end="1838"><strong data-start="1655" data-end="1663">Como</strong> reclutador,

<strong data-start="1678" data-end="1688">quiero</strong> poder mover a los candidatos a través de las etapas del proceso de selección,

<strong data-start="1769" data-end="1781">para que</strong> tenga visibilidad clara del avance y estado de cada uno.</p>
<p data-start="1840" data-end="1868"><strong data-start="1840" data-end="1868">Criterios de Aceptación:</strong></p>

<ul data-start="1870" data-end="2082">
<li data-start="1870" data-end="1947">
<p data-start="1872" data-end="1947">El sistema debe mostrar un tablero tipo Kanban con las etapas configuradas.</p>

<li data-start="1948" data-end="2020">
<p data-start="1950" data-end="2020">Cada candidatura debe poder moverse de una etapa a otra arrastrándola.</p>

<li data-start="2021" data-end="2082">
<p data-start="2023" data-end="2082">El cambio de etapa debe guardar el historial del candidato.</p>


<p data-start="2084" data-end="2174"><strong data-start="2084" data-end="2106">Notas Adicionales:</strong>

Se asume que las etapas iniciales están predefinidas para el MVP.</p>
<p data-start="2176" data-end="2216"><strong data-start="2176" data-end="2214">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="2217" data-end="2286">
<li data-start="2217" data-end="2245">
<p data-start="2219" data-end="2245">Evaluación de candidatos</p>

<li data-start="2246" data-end="2286">
<p data-start="2248" data-end="2286">Automatización de tareas según etapa</p>


<hr data-start="2288" data-end="2291">
<h3 data-start="2293" data-end="2336">🔹 Historia 3: Registro de Candidaturas</h3>
<p data-start="2338" data-end="2419"><strong data-start="2338" data-end="2375">Título de la Historia de Usuario:</strong>

Recepción y visualización de candidaturas</p>
<p data-start="2421" data-end="2594"><strong data-start="2421" data-end="2429">Como</strong> reclutador,

<strong data-start="2444" data-end="2454">quiero</strong> que las postulaciones a las vacantes se almacenen automáticamente en LTI,

<strong data-start="2531" data-end="2543">para que</strong> pueda revisarlas centralizadas y sin duplicidades.</p>
<p data-start="2596" data-end="2624"><strong data-start="2596" data-end="2624">Criterios de Aceptación:</strong></p>

<ul data-start="2626" data-end="2879">
<li data-start="2626" data-end="2732">
<p data-start="2628" data-end="2732">Alguien que se postule a una vacante (desde cualquier canal) debe crear automáticamente una candidatura.</p>

<li data-start="2733" data-end="2805">
<p data-start="2735" data-end="2805">El sistema debe asociar la candidatura con la vacante correspondiente.</p>

<li data-start="2806" data-end="2879">
<p data-start="2808" data-end="2879">El reclutador debe poder acceder al CV del candidato y datos parseados.</p>


<p data-start="2881" data-end="3032"><strong data-start="2881" data-end="2903">Notas Adicionales:</strong>

La postulación externa puede simularse mediante carga manual en la fase 1. Se irá automatizando con integraciones posteriores.</p>
<p data-start="3034" data-end="3074"><strong data-start="3034" data-end="3072">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="3075" data-end="3130">
<li data-start="3075" data-end="3098">
<p data-start="3077" data-end="3098">Matching automático</p>

<li data-start="3099" data-end="3130">
<p data-start="3101" data-end="3130">Recomendación de candidatos</p>


<hr data-start="3132" data-end="3135">
<h3 data-start="3137" data-end="3188">🔹 Historia 4: Evaluación Interna del Candidato</h3>
<p data-start="3190" data-end="3279"><strong data-start="3190" data-end="3227">Título de la Historia de Usuario:</strong>

Registro estructurado de feedback post-entrevista</p>
<p data-start="3281" data-end="3468"><strong data-start="3281" data-end="3289">Como</strong> entrevistador,

<strong data-start="3307" data-end="3317">quiero</strong> poder registrar mis evaluaciones y comentarios sobre cada candidato,

<strong data-start="3389" data-end="3401">para que</strong> el equipo tenga una visión común y objetiva para tomar decisiones.</p>
<p data-start="3470" data-end="3498"><strong data-start="3470" data-end="3498">Criterios de Aceptación:</strong></p>

<ul data-start="3500" data-end="3722">
<li data-start="3500" data-end="3581">
<p data-start="3502" data-end="3581">El sistema debe permitir rellenar un formulario con puntuaciones y comentarios.</p>

<li data-start="3582" data-end="3650">
<p data-start="3584" data-end="3650">Las evaluaciones deben quedar asociadas al candidato y a la etapa.</p>

<li data-start="3651" data-end="3722">
<p data-start="3653" data-end="3722">Todos los miembros del equipo con permiso deben ver las evaluaciones.</p>


<p data-start="3724" data-end="3804"><strong data-start="3724" data-end="3746">Notas Adicionales:</strong>

Es clave para fomentar la colaboración y transparencia.</p>
<p data-start="3806" data-end="3846"><strong data-start="3806" data-end="3844">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="3847" data-end="3907">
<li data-start="3847" data-end="3879">
<p data-start="3849" data-end="3879">Herramientas de colaboración</p>

<li data-start="3880" data-end="3907">
<p data-start="3882" data-end="3907">Notificaciones internas</p>


<hr data-start="3909" data-end="3912">
<h3 data-start="3914" data-end="3961">🔹 Historia 5: Talent Pool (base histórica)</h3>
<p data-start="3963" data-end="4036"><strong data-start="3963" data-end="4000">Título de la Historia de Usuario:</strong>

Consulta de candidatos históricos</p>
<p data-start="4038" data-end="4203"><strong data-start="4038" data-end="4046">Como</strong> reclutador,

<strong data-start="4061" data-end="4071">quiero</strong> poder buscar candidatos anteriores en la base de datos,

<strong data-start="4130" data-end="4142">para que</strong> pueda reutilizar perfiles cualificados para nuevas vacantes.</p>
<p data-start="4205" data-end="4233"><strong data-start="4205" data-end="4233">Criterios de Aceptación:</strong></p>

<ul data-start="4235" data-end="4482">
<li data-start="4235" data-end="4327">
<p data-start="4237" data-end="4327">El sistema debe permitir búsquedas filtradas por habilidades, experiencia, ubicación, etc.</p>

<li data-start="4328" data-end="4417">
<p data-start="4330" data-end="4417">Debe mostrar el historial del candidato (procesos anteriores, evaluaciones, resultado).</p>

<li data-start="4418" data-end="4482">
<p data-start="4420" data-end="4482">Se debe poder asociar un perfil histórico a una nueva vacante.</p>


<p data-start="4484" data-end="4562"><strong data-start="4484" data-end="4506">Notas Adicionales:</strong>

No requiere IA aún, se asume un buscador por filtros.</p>
<p data-start="4564" data-end="4604"><strong data-start="4564" data-end="4602">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="4605" data-end="4660">
<li data-start="4605" data-end="4631">
<p data-start="4607" data-end="4631">Recomendaciones por IA</p>

<li data-start="4632" data-end="4660">
<p data-start="4634" data-end="4660">Recontacto de candidatos</p>


<hr data-start="4662" data-end="4665">
<h3 data-start="4667" data-end="4711">🔹 Historia 6: Notificación al Candidato</h3>
<p data-start="4713" data-end="4794"><strong data-start="4713" data-end="4750">Título de la Historia de Usuario:</strong>

Comunicación automatizada en puntos clave</p>
<p data-start="4796" data-end="4975"><strong data-start="4796" data-end="4804">Como</strong> reclutador,

<strong data-start="4819" data-end="4829">quiero</strong> que el sistema envíe correos automáticos en puntos definidos,

<strong data-start="4894" data-end="4906">para que</strong> los candidatos estén informados sin que yo deba hacerlo manualmente.</p>
<p data-start="4977" data-end="5005"><strong data-start="4977" data-end="5005">Criterios de Aceptación:</strong></p>

<ul data-start="5007" data-end="5235">
<li data-start="5007" data-end="5088">
<p data-start="5009" data-end="5088">Al recibir una candidatura, se envía automáticamente un correo de confirmación.</p>

<li data-start="5089" data-end="5160">
<p data-start="5091" data-end="5160">Al ser rechazado, el candidato recibe una notificación personalizada.</p>

<li data-start="5161" data-end="5235">
<p data-start="5163" data-end="5235">El sistema permite personalizar los textos de los correos por plantilla.</p>


<p data-start="5237" data-end="5301"><strong data-start="5237" data-end="5259">Notas Adicionales:</strong>

Se asume un motor de plantillas simple.</p>
<p data-start="5303" data-end="5343"><strong data-start="5303" data-end="5341">Historias de Usuario Relacionadas:</strong></p>

<ul data-start="5344" data-end="5412">
<li data-start="5344" data-end="5371">
<p data-start="5346" data-end="5371">Automatización avanzada</p>

<li data-start="5372" data-end="5412">
<p data-start="5374" data-end="5412">Integración con servicios de mailing</p>


<hr data-start="5414" data-end="5417">
<h2 data-start="5419" data-end="5468">✅ Lista priorizada de historias para selección</h2>
<p data-start="5470" data-end="5552">Ordenadas por viabilidad técnica y lógica secuencial para evitar bloqueos futuros:</p>

- 
Historia 1: Creación de Vacantes


- 
Historia 3: Registro de Candidaturas


- 
Historia 2: Gestión del Pipeline


- 
Historia 4: Evaluación Interna


- 
Historia 6: Notificación al Candidato


- 
Historia 5: Talent Pool
<hr data-start="5793" data-end="5796">
<h3 data-start="5798" data-end="5831">✅ ¿Cuál es el siguiente paso?</h3>
<p data-start="5833" data-end="5987">Por favor, indícame qué 2 historias de usuario eliges para avanzar al Punto 2: <em data-start="5912" data-end="5986">“Armar el backlog de producto con las historias definidas y priorizadas”</em>.</p>
<p data-start="5989" data-end="6021" data-is-last-node="" data-is-only-node="">Estoy listo cuando digas <strong data-start="6014" data-end="6020">OK</strong>.</p>

--------------------------------------

# User

OK, hazme las dos primeras:
- Historia 1: Creación de Vacantes
- Historia 3: Registro de Candidaturas

--------------------------------------

# ChatGPT

<p data-start="0" data-end="37">Perfecto. Pasamos al siguiente punto.</p>
<hr data-start="39" data-end="42">
<h2 data-start="44" data-end="88">✅ Punto 2: Armado del Backlog de Producto</h2>
<h3 data-start="90" data-end="136">📌 Metodología de Priorización: <strong data-start="126" data-end="136">MoSCoW</strong></h3>
<p data-start="138" data-end="207">Aplicamos la metodología <strong data-start="163" data-end="173">MoSCoW</strong> para clasificar cada historia en:</p>

<ul data-start="209" data-end="456">
<li data-start="209" data-end="272">
<p data-start="211" data-end="272"><strong data-start="211" data-end="224">Must Have</strong>: esenciales para una primera entrega funcional.</p>

<li data-start="273" data-end="340">
<p data-start="275" data-end="340"><strong data-start="275" data-end="290">Should Have</strong>: importantes pero no críticas para un MVP usable.</p>

<li data-start="341" data-end="392">
<p data-start="343" data-end="392"><strong data-start="343" data-end="357">Could Have</strong>: mejoras opcionales, nice-to-have.</p>

<li data-start="393" data-end="456">
<p data-start="395" data-end="456"><strong data-start="395" data-end="421">Won’t Have (por ahora)</strong>: quedan fuera del alcance inicial.</p>


<p data-start="458" data-end="626">Dado que nos centramos ahora en solo dos historias, el foco está en desglosarlas en elementos accionables que conformen el <strong data-start="581" data-end="612">Backlog de Producto inicial</strong> con foco MVP.</p>
<hr data-start="628" data-end="631">
<h2 data-start="633" data-end="684">🎯 Backlog para Historia 1: Creación de Vacantes</h2>
<p data-start="686" data-end="763"><strong data-start="686" data-end="707">Prioridad general</strong>: ⭐️⭐️⭐️⭐️⭐️ (Must Have)

<strong data-start="734" data-end="742">Epic</strong>: Gestión de Vacantes</p>
<table data-start="765" data-end="1705" class="w-fit min-w-(--thread-content-width)"><thead data-start="765" data-end="819"><tr data-start="765" data-end="819"><th data-start="765" data-end="770" data-col-size="sm">ID</th><th data-start="770" data-end="779" data-col-size="md">Título</th><th data-start="779" data-end="786" data-col-size="sm">Tipo</th><th data-start="786" data-end="798" data-col-size="sm">Prioridad</th><th data-start="798" data-end="819" data-col-size="md">Descripción Corta</th></tr></thead><tbody data-start="875" data-end="1705"><tr data-start="875" data-end="1035"><td data-start="875" data-end="884" data-col-size="sm">US-001</td><td data-col-size="md" data-start="884" data-end="915">Crear formulario de vacantes</td><td data-col-size="sm" data-start="915" data-end="928">User Story</td><td data-col-size="sm" data-start="928" data-end="940">Must Have</td><td data-col-size="md" data-start="940" data-end="1035">Permite introducir los campos principales: título, descripción, requisitos, ubicación, etc.</td></tr><tr data-start="1036" data-end="1174"><td data-start="1036" data-end="1045" data-col-size="sm">US-002</td><td data-col-size="md" data-start="1045" data-end="1083">Validación de campos del formulario</td><td data-col-size="sm" data-start="1083" data-end="1096">User Story</td><td data-col-size="sm" data-start="1096" data-end="1108">Must Have</td><td data-col-size="md" data-start="1108" data-end="1174">El sistema valida que los campos obligatorios estén completos.</td></tr><tr data-start="1175" data-end="1291"><td data-start="1175" data-end="1184" data-col-size="sm">US-003</td><td data-col-size="md" data-start="1184" data-end="1208">Guardar como borrador</td><td data-col-size="sm" data-start="1208" data-end="1221">User Story</td><td data-col-size="sm" data-start="1221" data-end="1235">Should Have</td><td data-col-size="md" data-start="1235" data-end="1291">El usuario puede guardar una vacante sin publicarla.</td></tr><tr data-start="1292" data-end="1435"><td data-start="1292" data-end="1301" data-col-size="sm">US-004</td><td data-start="1301" data-end="1328" data-col-size="md">Editar vacante existente</td><td data-start="1328" data-end="1341" data-col-size="sm">User Story</td><td data-start="1341" data-end="1355" data-col-size="sm">Should Have</td><td data-start="1355" data-end="1435" data-col-size="md">El reclutador puede reabrir una vacante y editar campos antes de publicarla.</td></tr><tr data-start="1436" data-end="1574"><td data-start="1436" data-end="1445" data-col-size="sm">US-005</td><td data-start="1445" data-end="1489" data-col-size="md">Asistente IA de descripción (sugerencias)</td><td data-start="1489" data-end="1502" data-col-size="sm">User Story</td><td data-start="1502" data-end="1515" data-col-size="sm">Could Have</td><td data-start="1515" data-end="1574" data-col-size="md">El sistema sugiere contenido en base a roles similares.</td></tr><tr data-start="1575" data-end="1705"><td data-start="1575" data-end="1584" data-col-size="sm">US-006</td><td data-start="1584" data-end="1609" data-col-size="md">Plantillas de vacantes</td><td data-start="1609" data-end="1622" data-col-size="sm">User Story</td><td data-start="1622" data-end="1635" data-col-size="sm">Could Have</td><td data-start="1635" data-end="1705" data-col-size="md">Posibilidad de reutilizar una vacante como plantilla para futuras.</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="1707" data-end="1710">
<h2 data-start="1712" data-end="1767">🎯 Backlog para Historia 3: Registro de Candidaturas</h2>
<p data-start="1769" data-end="1850"><strong data-start="1769" data-end="1790">Prioridad general</strong>: ⭐️⭐️⭐️⭐️⭐️ (Must Have)

<strong data-start="1817" data-end="1825">Epic</strong>: Gestión de Candidaturas</p>
<table data-start="1852" data-end="2904" class="w-fit min-w-(--thread-content-width)"><thead data-start="1852" data-end="1906"><tr data-start="1852" data-end="1906"><th data-start="1852" data-end="1857" data-col-size="sm">ID</th><th data-start="1857" data-end="1866" data-col-size="md">Título</th><th data-start="1866" data-end="1873" data-col-size="sm">Tipo</th><th data-start="1873" data-end="1885" data-col-size="sm">Prioridad</th><th data-start="1885" data-end="1906" data-col-size="md">Descripción Corta</th></tr></thead><tbody data-start="1962" data-end="2904"><tr data-start="1962" data-end="2121"><td data-start="1962" data-end="1971" data-col-size="sm">US-010</td><td data-start="1971" data-end="2008" data-col-size="md">Registro automático de candidatura</td><td data-start="2008" data-end="2021" data-col-size="sm">User Story</td><td data-start="2021" data-end="2033" data-col-size="sm">Must Have</td><td data-start="2033" data-end="2121" data-col-size="md">Toda postulación debe crear automáticamente una candidatura vinculada a una vacante.</td></tr><tr data-start="2122" data-end="2291"><td data-start="2122" data-end="2131" data-col-size="sm">US-011</td><td data-start="2131" data-end="2180" data-col-size="md">Asociación de candidatura a la oferta correcta</td><td data-start="2180" data-end="2193" data-col-size="sm">User Story</td><td data-start="2193" data-end="2205" data-col-size="sm">Must Have</td><td data-start="2205" data-end="2291" data-col-size="md">El sistema debe vincular la candidatura con la vacante que originó la postulación.</td></tr><tr data-start="2292" data-end="2435"><td data-start="2292" data-end="2301" data-col-size="sm">US-012</td><td data-start="2301" data-end="2340" data-col-size="md">Visualización de perfil de candidato</td><td data-start="2340" data-end="2353" data-col-size="sm">User Story</td><td data-start="2353" data-end="2365" data-col-size="sm">Must Have</td><td data-start="2365" data-end="2435" data-col-size="md">Los datos parseados del CV deben mostrarse junto a la candidatura.</td></tr><tr data-start="2436" data-end="2608"><td data-start="2436" data-end="2445" data-col-size="sm">US-013</td><td data-start="2445" data-end="2484" data-col-size="md">Registro de origen de la candidatura</td><td data-start="2484" data-end="2497" data-col-size="sm">User Story</td><td data-start="2497" data-end="2511" data-col-size="sm">Should Have</td><td data-start="2511" data-end="2608" data-col-size="md">El sistema debe guardar de qué canal proviene la aplicación (LinkedIn, portal interno, etc.).</td></tr><tr data-start="2609" data-end="2748"><td data-start="2609" data-end="2618" data-col-size="sm">US-014</td><td data-start="2618" data-end="2653" data-col-size="md">Recepción manual de CVs externos</td><td data-start="2653" data-end="2666" data-col-size="sm">User Story</td><td data-start="2666" data-end="2679" data-col-size="sm">Could Have</td><td data-start="2679" data-end="2748" data-col-size="md">Posibilidad de registrar candidatos recibidos por email o ferias.</td></tr><tr data-start="2749" data-end="2904"><td data-start="2749" data-end="2758" data-col-size="sm">US-015</td><td data-start="2758" data-end="2805" data-col-size="md">Parseo automático del CV (estructura básica)</td><td data-start="2805" data-end="2818" data-col-size="sm">User Story</td><td data-start="2818" data-end="2832" data-col-size="sm">Should Have</td><td data-start="2832" data-end="2904" data-col-size="md">El sistema extrae datos clave del CV para mostrar un resumen rápido.</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="2906" data-end="2909">
<h2 data-start="2911" data-end="2952">✅ Resumen del Backlog inicial completo</h2>
<table data-start="2954" data-end="3992" class="w-fit min-w-(--thread-content-width)"><thead data-start="2954" data-end="3001"><tr data-start="2954" data-end="3001"><th data-start="2954" data-end="2959" data-col-size="sm">ID</th><th data-start="2959" data-end="2981" data-col-size="sm">Historia de Usuario</th><th data-start="2981" data-end="2988" data-col-size="sm">Epic</th><th data-start="2988" data-end="3001" data-col-size="sm">Prioridad</th></tr></thead><tbody data-start="3050" data-end="3992"><tr data-start="3050" data-end="3125"><td data-start="3050" data-end="3059" data-col-size="sm">US-001</td><td data-start="3059" data-end="3090" data-col-size="sm">Crear formulario de vacantes</td><td data-start="3090" data-end="3112" data-col-size="sm">Gestión de Vacantes</td><td data-col-size="sm" data-start="3112" data-end="3125">Must Have</td></tr><tr data-start="3126" data-end="3208"><td data-start="3126" data-end="3135" data-col-size="sm">US-002</td><td data-col-size="sm" data-start="3135" data-end="3173">Validación de campos del formulario</td><td data-col-size="sm" data-start="3173" data-end="3195">Gestión de Vacantes</td><td data-col-size="sm" data-start="3195" data-end="3208">Must Have</td></tr><tr data-start="3209" data-end="3279"><td data-start="3209" data-end="3218" data-col-size="sm">US-003</td><td data-col-size="sm" data-start="3218" data-end="3242">Guardar como borrador</td><td data-col-size="sm" data-start="3242" data-end="3264">Gestión de Vacantes</td><td data-col-size="sm" data-start="3264" data-end="3279">Should Have</td></tr><tr data-start="3280" data-end="3353"><td data-start="3280" data-end="3289" data-col-size="sm">US-004</td><td data-col-size="sm" data-start="3289" data-end="3316">Editar vacante existente</td><td data-col-size="sm" data-start="3316" data-end="3338">Gestión de Vacantes</td><td data-col-size="sm" data-start="3338" data-end="3353">Should Have</td></tr><tr data-start="3354" data-end="3429"><td data-start="3354" data-end="3363" data-col-size="sm">US-005</td><td data-col-size="sm" data-start="3363" data-end="3393">Asistente IA de descripción</td><td data-col-size="sm" data-start="3393" data-end="3415">Gestión de Vacantes</td><td data-col-size="sm" data-start="3415" data-end="3429">Could Have</td></tr><tr data-start="3430" data-end="3500"><td data-start="3430" data-end="3439" data-col-size="sm">US-006</td><td data-start="3439" data-end="3464" data-col-size="sm">Plantillas de vacantes</td><td data-col-size="sm" data-start="3464" data-end="3486">Gestión de Vacantes</td><td data-col-size="sm" data-start="3486" data-end="3500">Could Have</td></tr><tr data-start="3501" data-end="3586"><td data-start="3501" data-end="3510" data-col-size="sm">US-010</td><td data-col-size="sm" data-start="3510" data-end="3547">Registro automático de candidatura</td><td data-col-size="sm" data-start="3547" data-end="3573">Gestión de Candidaturas</td><td data-col-size="sm" data-start="3573" data-end="3586">Must Have</td></tr><tr data-start="3587" data-end="3673"><td data-start="3587" data-end="3596" data-col-size="sm">US-011</td><td data-col-size="sm" data-start="3596" data-end="3634">Asociación de candidatura a vacante</td><td data-col-size="sm" data-start="3634" data-end="3660">Gestión de Candidaturas</td><td data-col-size="sm" data-start="3660" data-end="3673">Must Have</td></tr><tr data-start="3674" data-end="3761"><td data-start="3674" data-end="3683" data-col-size="sm">US-012</td><td data-start="3683" data-end="3722" data-col-size="sm">Visualización de perfil de candidato</td><td data-col-size="sm" data-start="3722" data-end="3748">Gestión de Candidaturas</td><td data-col-size="sm" data-start="3748" data-end="3761">Must Have</td></tr><tr data-start="3762" data-end="3843"><td data-start="3762" data-end="3771" data-col-size="sm">US-013</td><td data-start="3771" data-end="3802" data-col-size="sm">Registro del canal de origen</td><td data-start="3802" data-end="3828" data-col-size="sm">Gestión de Candidaturas</td><td data-start="3828" data-end="3843" data-col-size="sm">Should Have</td></tr><tr data-start="3844" data-end="3915"><td data-start="3844" data-end="3853" data-col-size="sm">US-014</td><td data-start="3853" data-end="3875" data-col-size="sm">Carga manual de CVs</td><td data-start="3875" data-end="3901" data-col-size="sm">Gestión de Candidaturas</td><td data-start="3901" data-end="3915" data-col-size="sm">Could Have</td></tr><tr data-start="3916" data-end="3992"><td data-start="3916" data-end="3925" data-col-size="sm">US-015</td><td data-start="3925" data-end="3951" data-col-size="sm">Parseo automático de CV</td><td data-start="3951" data-end="3977" data-col-size="sm">Gestión de Candidaturas</td><td data-start="3977" data-end="3992" data-col-size="sm">Should Have</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="3994" data-end="3997">
<p data-start="3999" data-end="4112">¿Damos luz verde para el Punto 3: generar los tickets de trabajo técnicos necesarios para arrancar el desarrollo?</p>
<p data-start="4114" data-end="4158" data-is-last-node="" data-is-only-node="">Cuando estés listo, dime simplemente <strong data-start="4151" data-end="4157">OK</strong>.</p>

--------------------------------------

# User

OK

--------------------------------------

# ChatGPT

<p data-start="0" data-end="42">Perfecto. Avanzamos con el siguiente paso.</p>
<hr data-start="44" data-end="47">
<h2 data-start="49" data-end="114">✅ Punto 3: Generación de Tickets de Trabajo Técnicos Iniciales</h2>
<p data-start="116" data-end="475">Como Business Analyst y Product Manager, he desglosado las historias <strong data-start="185" data-end="222">US-001 a US-002 y US-010 a US-012</strong> en <strong data-start="226" data-end="261">tickets de desarrollo concretos</strong> que permiten comenzar la implementación técnica del sistema LTI. La lógica utilizada responde al principio de <em data-start="372" data-end="410">entregables mínimos pero funcionales</em> y facilita un flujo de trabajo eficiente para el equipo técnico.</p>
<hr data-start="477" data-end="480">
<h2 data-start="482" data-end="544">🛠 Tickets Técnicos para Historia 1: <em data-start="522" data-end="544">Creación de Vacantes</em></h2>
<h3 data-start="546" data-end="578">🧱 Epic: Gestión de Vacantes</h3>
<table data-start="580" data-end="1805" class="w-fit min-w-(--thread-content-width)"><thead data-start="580" data-end="639"><tr data-start="580" data-end="639"><th data-start="580" data-end="592" data-col-size="sm">Ticket ID</th><th data-start="592" data-end="601" data-col-size="md">Título</th><th data-start="601" data-end="608" data-col-size="sm">Tipo</th><th data-start="608" data-end="622" data-col-size="lg">Descripción</th><th data-start="622" data-end="639" data-col-size="md">Justificación</th></tr></thead><tbody data-start="701" data-end="1805"><tr data-start="701" data-end="962"><td data-start="701" data-end="711" data-col-size="sm">DEV-001</td><td data-col-size="md" data-start="711" data-end="751">Crear entidad "JobOpening" en backend</td><td data-col-size="sm" data-start="751" data-end="761">Backend</td><td data-col-size="lg" data-start="761" data-end="898">Modelar en base de datos la entidad <code data-start="799" data-end="807">Oferta``` con atributos clave: ID, título, descripción, tipo contrato, estado, fecha creación, etc.</td><td data-col-size="md" data-start="898" data-end="962">Permite persistencia y consulta de vacantes. Es fundacional.</td></tr><tr data-start="963" data-end="1190"><td data-start="963" data-end="973" data-col-size="sm">DEV-002</td><td data-col-size="md" data-start="973" data-end="1020">API REST: Crear, editar y consultar vacantes</td><td data-col-size="sm" data-start="1020" data-end="1030">Backend</td><td data-col-size="lg" data-start="1030" data-end="1131">Endpoint <code data-start="1041" data-end="1052">POST /job```, <code data-start="1054" data-end="1069">GET /job/{id}```, <code data-start="1071" data-end="1086">PUT /job/{id}``` con validaciones y respuesta estandarizada.</td><td data-col-size="md" data-start="1131" data-end="1190">Necesario para que el frontend pueda gestionar ofertas.</td></tr><tr data-start="1191" data-end="1420"><td data-start="1191" data-end="1201" data-col-size="sm">DEV-003</td><td data-col-size="md" data-start="1201" data-end="1241">Formulario UI de creación de vacantes</td><td data-col-size="sm" data-start="1241" data-end="1252">Frontend</td><td data-col-size="lg" data-start="1252" data-end="1354">Construir el formulario en la app web, con campos estructurados. Validación de campos obligatorios.</td><td data-col-size="md" data-start="1354" data-end="1420">Es la interfaz principal del reclutador para iniciar el flujo.</td></tr><tr data-start="1421" data-end="1600"><td data-start="1421" data-end="1431" data-col-size="sm">DEV-004</td><td data-col-size="md" data-start="1431" data-end="1473">Conexión frontend–backend para vacantes</td><td data-col-size="sm" data-start="1473" data-end="1484">Frontend</td><td data-col-size="lg" data-start="1484" data-end="1570">Llamadas a la API (axios/fetch) para persistir los datos del formulario en la base.</td><td data-col-size="md" data-start="1570" data-end="1600">Asegura persistencia real.</td></tr><tr data-start="1601" data-end="1805"><td data-start="1601" data-end="1611" data-col-size="sm">DEV-005</td><td data-col-size="md" data-start="1611" data-end="1662">Modelo de permisos: validación de acceso por rol</td><td data-col-size="sm" data-start="1662" data-end="1672">Backend</td><td data-col-size="lg" data-start="1672" data-end="1767">Asegurar que solo usuarios autenticados con rol <code data-start="1722" data-end="1733">Recruiter``` o <code data-start="1736" data-end="1743">Admin``` puedan crear vacantes.</td><td data-col-size="md" data-start="1767" data-end="1805">Control de acceso desde el inicio.</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="1807" data-end="1810">
<h2 data-start="1812" data-end="1878">🛠 Tickets Técnicos para Historia 3: <em data-start="1852" data-end="1878">Registro de Candidaturas</em></h2>
<h3 data-start="1880" data-end="1916">🧱 Epic: Gestión de Candidaturas</h3>
<table data-start="1918" data-end="3430" class="w-fit min-w-(--thread-content-width)"><thead data-start="1918" data-end="1977"><tr data-start="1918" data-end="1977"><th data-start="1918" data-end="1930" data-col-size="sm">Ticket ID</th><th data-start="1930" data-end="1939" data-col-size="md">Título</th><th data-start="1939" data-end="1946" data-col-size="sm">Tipo</th><th data-start="1946" data-end="1960" data-col-size="xl">Descripción</th><th data-start="1960" data-end="1977" data-col-size="md">Justificación</th></tr></thead><tbody data-start="2039" data-end="3430"><tr data-start="2039" data-end="2319"><td data-start="2039" data-end="2049" data-col-size="sm">DEV-006</td><td data-col-size="md" data-start="2049" data-end="2093">Crear entidad "Candidate" y "Application"</td><td data-col-size="sm" data-start="2093" data-end="2103">Backend</td><td data-col-size="xl" data-start="2103" data-end="2277">Modelo de datos: un candidato (<code data-start="2136" data-end="2147">Candidate```) puede tener múltiples candidaturas (<code data-start="2185" data-end="2198">Application```) asociadas a vacantes. Campos como nombre, email, CV, estado de proceso, etc.</td><td data-col-size="md" data-start="2277" data-end="2319">Soporte estructural clave del sistema.</td></tr><tr data-start="2320" data-end="2562"><td data-start="2320" data-end="2330" data-col-size="sm">DEV-007</td><td data-start="2330" data-end="2372" data-col-size="md">Endpoint API para registrar candidatura</td><td data-col-size="sm" data-start="2372" data-end="2382">Backend</td><td data-col-size="xl" data-start="2382" data-end="2511"><code data-start="2384" data-end="2403">POST /application``` que recibe datos de candidato y los asocia a una oferta existente. Soporte para uploads de CV (multipart).</td><td data-col-size="md" data-start="2511" data-end="2562">Es el punto de entrada principal de candidatos.</td></tr><tr data-start="2563" data-end="2807"><td data-start="2563" data-end="2573" data-col-size="sm">DEV-008</td><td data-col-size="md" data-start="2573" data-end="2607">Parseo básico de CVs en backend</td><td data-col-size="sm" data-start="2607" data-end="2631">Backend (IA opcional)</td><td data-col-size="xl" data-start="2631" data-end="2753">Parsear PDF/Word a texto y extraer datos clave: nombre, email, experiencia, skills (puede ser MVP sin IA inicialmente).</td><td data-col-size="md" data-start="2753" data-end="2807">Mejora la experiencia de screening del reclutador.</td></tr><tr data-start="2808" data-end="3008"><td data-start="2808" data-end="2818" data-col-size="sm">DEV-009</td><td data-col-size="md" data-start="2818" data-end="2856">Visualización de candidaturas en UI</td><td data-col-size="sm" data-start="2856" data-end="2867">Frontend</td><td data-col-size="xl" data-start="2867" data-end="2967">Mostrar listado de candidaturas por vacante, con nombre, email, resumen del perfil. Acceso al CV.</td><td data-col-size="md" data-start="2967" data-end="3008">Visibilidad operativa para el equipo.</td></tr><tr data-start="3009" data-end="3237"><td data-start="3009" data-end="3019" data-col-size="sm">DEV-010</td><td data-col-size="md" data-start="3019" data-end="3061">Lógica de asociación oferta–candidatura</td><td data-col-size="sm" data-start="3061" data-end="3071">Backend</td><td data-col-size="xl" data-start="3071" data-end="3201">Garantizar que cada postulación llega asociada a la vacante correcta (por ID). Incluye validaciones si la vacante está cerrada.</td><td data-col-size="md" data-start="3201" data-end="3237">Mantiene integridad del sistema.</td></tr><tr data-start="3238" data-end="3430"><td data-start="3238" data-end="3248" data-col-size="sm">DEV-011</td><td data-col-size="md" data-start="3248" data-end="3294">Validación de duplicados por email y oferta</td><td data-col-size="sm" data-start="3294" data-end="3304">Backend</td><td data-col-size="xl" data-start="3304" data-end="3382">Evitar que un mismo candidato se postule más de una vez a la misma vacante.</td><td data-col-size="md" data-start="3382" data-end="3430">Previene carga innecesaria y ruido de datos.</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="3432" data-end="3435">
<h2 data-start="3437" data-end="3487">🔄 Flujo operativo habilitado con estos tickets</h2>
<p data-start="3489" data-end="3839">✔️ Crear una vacante desde la interfaz

✔️ Guardarla correctamente en base de datos

✔️ Permitir postulaciones externas o internas

✔️ Almacenar y visualizar las candidaturas

✔️ Disponer de estructura básica de entidades clave (<code data-start="3722" data-end="3727">Job```, <code data-start="3729" data-end="3740">Candidate```, <code data-start="3742" data-end="3755">Application```)

✔️ Mostrar en frontend todo lo necesario para trabajar con ambas funcionalidades</p>
<hr data-start="3841" data-end="3844">
<p data-start="3846" data-end="3961">¿Pasamos al <strong data-start="3858" data-end="3907">Punto 4: estimar el esfuerzo de estos tickets</strong>, eligiendo una metodología adecuada y justificándola?</p>
<p data-start="3963" data-end="3991" data-is-last-node="" data-is-only-node="">Cuando quieras, dime <strong data-start="3984" data-end="3990">OK</strong>.</p>

--------------------------------------

# User

OK

--------------------------------------

# ChatGPT

<p data-start="0" data-end="112">Perfecto. Cerramos el punto 4 con la <strong data-start="37" data-end="72">estimación del esfuerzo técnico</strong> de los tickets definidos anteriormente.</p>
<hr data-start="114" data-end="117">
<h2 data-start="119" data-end="155">✅ Punto 4: Estimación de Esfuerzo</h2>
<h3 data-start="157" data-end="237">📌 Metodología usada: <strong data-start="183" data-end="237">Planning Poker + Puntos de Historia (Story Points)</strong></h3>
<p data-start="239" data-end="335">He optado por usar <strong data-start="258" data-end="279">Story Points (SP)</strong> como unidad principal de estimación, por estas razones:</p>

<ul data-start="337" data-end="639">
<li data-start="337" data-end="403">
<p data-start="339" data-end="403">Es un enfoque <strong data-start="353" data-end="361">ágil</strong>, ideal para la fase inicial del proyecto.</p>

<li data-start="404" data-end="532">
<p data-start="406" data-end="532">Permite estimar <strong data-start="422" data-end="473">complejidad + incertidumbre + esfuerzo relativo</strong> sin quedar atrapado en estimaciones horarias poco fiables.</p>

<li data-start="533" data-end="639">
<p data-start="535" data-end="639">Puede mapearse fácilmente a horas/días más adelante cuando el equipo defina su <strong data-start="614" data-end="638">velocidad (velocity)</strong>.</p>


<p data-start="641" data-end="793">Para facilitar decisiones iniciales, añado una <strong data-start="688" data-end="723">estimación orientativa en horas</strong> como complemento, aunque el seguimiento real se debería hacer por SP.</p>
<hr data-start="795" data-end="798">
<h2 data-start="800" data-end="855">🎯 Estimaciones para los Tickets del Backlog Inicial</h2>
<table data-start="857" data-end="2204" class="w-fit min-w-(--thread-content-width)"><thead data-start="857" data-end="945"><tr data-start="857" data-end="945"><th data-start="857" data-end="869" data-col-size="sm">Ticket ID</th><th data-start="869" data-end="878" data-col-size="sm">Título</th><th data-start="878" data-end="898" data-col-size="sm">Story Points (SP)</th><th data-start="898" data-end="928" data-col-size="sm">Est. en horas (referencial)</th><th data-start="928" data-end="945" data-col-size="md">Justificación</th></tr></thead><tbody data-start="1037" data-end="2204"><tr data-start="1037" data-end="1131"><td data-start="1037" data-end="1047" data-col-size="sm">DEV-001</td><td data-col-size="sm" data-start="1047" data-end="1076">Crear entidad "JobOpening"</td><td data-col-size="sm" data-start="1076" data-end="1083">3 SP</td><td data-col-size="sm" data-start="1083" data-end="1089">6 h</td><td data-col-size="md" data-start="1089" data-end="1131">Modelo de datos moderado, bajo riesgo.</td></tr><tr data-start="1132" data-end="1248"><td data-start="1132" data-end="1142" data-col-size="sm">DEV-002</td><td data-col-size="sm" data-start="1142" data-end="1167">API REST para vacantes</td><td data-col-size="sm" data-start="1167" data-end="1174">5 SP</td><td data-col-size="sm" data-start="1174" data-end="1184">10–12 h</td><td data-col-size="md" data-start="1184" data-end="1248">Incluye lógica de validación, control de errores, seguridad.</td></tr><tr data-start="1249" data-end="1357"><td data-start="1249" data-end="1259" data-col-size="sm">DEV-003</td><td data-col-size="sm" data-start="1259" data-end="1287">Formulario UI de vacantes</td><td data-col-size="sm" data-start="1287" data-end="1294">5 SP</td><td data-col-size="sm" data-start="1294" data-end="1301">10 h</td><td data-col-size="md" data-start="1301" data-end="1357">Desarrollo de interfaz con validaciones en frontend.</td></tr><tr data-start="1358" data-end="1450"><td data-start="1358" data-end="1368" data-col-size="sm">DEV-004</td><td data-col-size="sm" data-start="1368" data-end="1396">Conexión frontend–backend</td><td data-col-size="sm" data-start="1396" data-end="1403">3 SP</td><td data-col-size="sm" data-start="1403" data-end="1409">6 h</td><td data-col-size="md" data-start="1409" data-end="1450">Integración básica con la API creada.</td></tr><tr data-start="1451" data-end="1549"><td data-start="1451" data-end="1461" data-col-size="sm">DEV-005</td><td data-col-size="sm" data-start="1461" data-end="1489">Control de acceso por rol</td><td data-col-size="sm" data-start="1489" data-end="1496">2 SP</td><td data-col-size="sm" data-start="1496" data-end="1504">3–4 h</td><td data-col-size="md" data-start="1504" data-end="1549">Uso de middlewares o decorators estándar.</td></tr><tr data-start="1550" data-end="1670"><td data-start="1550" data-end="1560" data-col-size="sm">DEV-006</td><td data-col-size="sm" data-start="1560" data-end="1593">Modelo Candidate y Application</td><td data-col-size="sm" data-start="1593" data-end="1600">5 SP</td><td data-col-size="sm" data-start="1600" data-end="1607">10 h</td><td data-col-size="md" data-start="1607" data-end="1670">Doble entidad con relaciones y estructura inicial de datos.</td></tr><tr data-start="1671" data-end="1782"><td data-start="1671" data-end="1681" data-col-size="sm">DEV-007</td><td data-col-size="sm" data-start="1681" data-end="1714">API para registrar candidatura</td><td data-col-size="sm" data-start="1714" data-end="1721">5 SP</td><td data-col-size="sm" data-start="1721" data-end="1731">10–12 h</td><td data-col-size="md" data-start="1731" data-end="1782">Validación de inputs + manejo de archivos (CV).</td></tr><tr data-start="1783" data-end="1873"><td data-start="1783" data-end="1793" data-col-size="sm">DEV-008</td><td data-col-size="sm" data-start="1793" data-end="1816">Parseo básico de CVs</td><td data-col-size="sm" data-start="1816" data-end="1823">5 SP</td><td data-col-size="sm" data-start="1823" data-end="1832">8–10 h</td><td data-col-size="md" data-start="1832" data-end="1873">Parsing simple de texto, sin NLP aún.</td></tr><tr data-start="1874" data-end="1983"><td data-start="1874" data-end="1884" data-col-size="sm">DEV-009</td><td data-col-size="sm" data-start="1884" data-end="1917">UI de candidaturas por vacante</td><td data-col-size="sm" data-start="1917" data-end="1924">3 SP</td><td data-col-size="sm" data-start="1924" data-end="1930">6 h</td><td data-col-size="md" data-start="1930" data-end="1983">Componente de tabla/listado con acceso a detalle.</td></tr><tr data-start="1984" data-end="2091"><td data-start="1984" data-end="1994" data-col-size="sm">DEV-010</td><td data-col-size="sm" data-start="1994" data-end="2026">Asociación oferta–candidatura</td><td data-col-size="sm" data-start="2026" data-end="2033">2 SP</td><td data-col-size="sm" data-start="2033" data-end="2041">3–4 h</td><td data-col-size="md" data-start="2041" data-end="2091">Lógica de negocio sencilla, validación por ID.</td></tr><tr data-start="2092" data-end="2204"><td data-start="2092" data-end="2102" data-col-size="sm">DEV-011</td><td data-col-size="sm" data-start="2102" data-end="2129">Validación de duplicados</td><td data-col-size="sm" data-start="2129" data-end="2136">2 SP</td><td data-col-size="sm" data-start="2136" data-end="2142">3 h</td><td data-col-size="md" data-start="2142" data-end="2204">Consulta previa antes de registrar, control de integridad.</td></tr></tbody></table><span class="" data-state="closed"><button aria-label="Copiar tabla" class="hover:bg-token-bg-tertiary text-token-text-secondary my-1 rounded-sm p-1 transition-opacity group-[:not(:hover):not(:focus-within)]:pointer-events-none group-[:not(:hover):not(:focus-within)]:opacity-0"><svg width="20" height="20" viewBox="0 0 20 20" fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="icon"><path d="M12.668 10.667C12.668 9.95614 12.668 9.46258 12.6367 9.0791C12.6137 8.79732 12.5758 8.60761 12.5244 8.46387L12.4688 8.33399C12.3148 8.03193 12.0803 7.77885 11.793 7.60254L11.666 7.53125C11.508 7.45087 11.2963 7.39395 10.9209 7.36328C10.5374 7.33197 10.0439 7.33203 9.33301 7.33203H6.5C5.78896 7.33203 5.29563 7.33195 4.91211 7.36328C4.63016 7.38632 4.44065 7.42413 4.29688 7.47559L4.16699 7.53125C3.86488 7.68518 3.61186 7.9196 3.43555 8.20703L3.36524 8.33399C3.28478 8.49198 3.22795 8.70352 3.19727 9.0791C3.16595 9.46259 3.16504 9.95611 3.16504 10.667V13.5C3.16504 14.211 3.16593 14.7044 3.19727 15.0879C3.22797 15.4636 3.28473 15.675 3.36524 15.833L3.43555 15.959C3.61186 16.2466 3.86474 16.4807 4.16699 16.6348L4.29688 16.6914C4.44063 16.7428 4.63025 16.7797 4.91211 16.8027C5.29563 16.8341 5.78896 16.835 6.5 16.835H9.33301C10.0439 16.835 10.5374 16.8341 10.9209 16.8027C11.2965 16.772 11.508 16.7152 11.666 16.6348L11.793 16.5645C12.0804 16.3881 12.3148 16.1351 12.4688 15.833L12.5244 15.7031C12.5759 15.5594 12.6137 15.3698 12.6367 15.0879C12.6681 14.7044 12.668 14.211 12.668 13.5V10.667ZM13.998 12.665C14.4528 12.6634 14.8011 12.6602 15.0879 12.6367C15.4635 12.606 15.675 12.5492 15.833 12.4688L15.959 12.3975C16.2466 12.2211 16.4808 11.9682 16.6348 11.666L16.6914 11.5361C16.7428 11.3924 16.7797 11.2026 16.8027 10.9209C16.8341 10.5374 16.835 10.0439 16.835 9.33301V6.5C16.835 5.78896 16.8341 5.29563 16.8027 4.91211C16.7797 4.63025 16.7428 4.44063 16.6914 4.29688L16.6348 4.16699C16.4807 3.86474 16.2466 3.61186 15.959 3.43555L15.833 3.36524C15.675 3.28473 15.4636 3.22797 15.0879 3.19727C14.7044 3.16593 14.211 3.16504 13.5 3.16504H10.667C9.9561 3.16504 9.46259 3.16595 9.0791 3.19727C8.79739 3.22028 8.6076 3.2572 8.46387 3.30859L8.33399 3.36524C8.03176 3.51923 7.77886 3.75343 7.60254 4.04102L7.53125 4.16699C7.4508 4.32498 7.39397 4.53655 7.36328 4.91211C7.33985 5.19893 7.33562 5.54719 7.33399 6.00195H9.33301C10.022 6.00195 10.5791 6.00131 11.0293 6.03809C11.4873 6.07551 11.8937 6.15471 12.2705 6.34668L12.4883 6.46875C12.984 6.7728 13.3878 7.20854 13.6533 7.72949L13.7197 7.87207C13.8642 8.20859 13.9292 8.56974 13.9619 8.9707C13.9987 9.42092 13.998 9.97799 13.998 10.667V12.665ZM18.165 9.33301C18.165 10.022 18.1657 10.5791 18.1289 11.0293C18.0961 11.4302 18.0311 11.7914 17.8867 12.1279L17.8203 12.2705C17.5549 12.7914 17.1509 13.2272 16.6553 13.5313L16.4365 13.6533C16.0599 13.8452 15.6541 13.9245 15.1963 13.9619C14.8593 13.9895 14.4624 13.9935 13.9951 13.9951C13.9935 14.4624 13.9895 14.8593 13.9619 15.1963C13.9292 15.597 13.864 15.9576 13.7197 16.2939L13.6533 16.4365C13.3878 16.9576 12.9841 17.3941 12.4883 17.6982L12.2705 17.8203C11.8937 18.0123 11.4873 18.0915 11.0293 18.1289C10.5791 18.1657 10.022 18.165 9.33301 18.165H6.5C5.81091 18.165 5.25395 18.1657 4.80371 18.1289C4.40306 18.0962 4.04235 18.031 3.70606 17.8867L3.56348 17.8203C3.04244 17.5548 2.60585 17.151 2.30176 16.6553L2.17969 16.4365C1.98788 16.0599 1.90851 15.6541 1.87109 15.1963C1.83431 14.746 1.83496 14.1891 1.83496 13.5V10.667C1.83496 9.978 1.83432 9.42091 1.87109 8.9707C1.90851 8.5127 1.98772 8.10625 2.17969 7.72949L2.30176 7.51172C2.60586 7.0159 3.04236 6.6122 3.56348 6.34668L3.70606 6.28027C4.04237 6.136 4.40303 6.07083 4.80371 6.03809C5.14051 6.01057 5.53708 6.00551 6.00391 6.00391C6.00551 5.53708 6.01057 5.14051 6.03809 4.80371C6.0755 4.34588 6.15483 3.94012 6.34668 3.56348L6.46875 3.34473C6.77282 2.84912 7.20856 2.44514 7.72949 2.17969L7.87207 2.11328C8.20855 1.96886 8.56979 1.90385 8.9707 1.87109C9.42091 1.83432 9.978 1.83496 10.667 1.83496H13.5C14.1891 1.83496 14.746 1.83431 15.1963 1.87109C15.6541 1.90851 16.0599 1.98788 16.4365 2.17969L16.6553 2.30176C17.151 2.60585 17.5548 3.04244 17.8203 3.56348L17.8867 3.70606C18.031 4.04235 18.0962 4.40306 18.1289 4.80371C18.1657 5.25395 18.165 5.81091 18.165 6.5V9.33301Z"></path></svg></button>
<hr data-start="2206" data-end="2209">
<h3 data-start="2211" data-end="2225">🔢 Totales</h3>

<ul data-start="2227" data-end="2441">
<li data-start="2227" data-end="2260">
<p data-start="2229" data-end="2260"><strong data-start="2229" data-end="2252">Total Story Points:</strong> 45 SP</p>

<li data-start="2261" data-end="2304">
<p data-start="2263" data-end="2304"><strong data-start="2263" data-end="2291">Total estimado en horas:</strong> ~85 a 95 h</p>

<li data-start="2305" data-end="2441">
<p data-start="2307" data-end="2441"><strong data-start="2307" data-end="2360">Duración estimada (equipo de 2–3 devs dedicados):</strong> 5–6 días de trabajo intensivo (~2 sprints de 1 semana para MVP funcional básico)</p>


<hr data-start="2443" data-end="2446">
<h2 data-start="2448" data-end="2487">🧩 Notas finales sobre la estimación</h2>

<ul data-start="2489" data-end="2797">
<li data-start="2489" data-end="2569">
<p data-start="2491" data-end="2569"><strong data-start="2491" data-end="2509">Alta prioridad</strong>: DEV-001 a DEV-007 deberían ir en el primer sprint del MVP.</p>

<li data-start="2570" data-end="2649">
<p data-start="2572" data-end="2649"><strong data-start="2572" data-end="2602">Baja incertidumbre técnica</strong>: muchas tareas son CRUD + validación estándar.</p>

<li data-start="2650" data-end="2797">
<p data-start="2652" data-end="2797"><strong data-start="2652" data-end="2693">Tareas como el parseo de CV (DEV-008)</strong> podrían entregarse con lógica mínima y evolucionar en un segundo sprint con IA/NLP si se desea escalar.</p>


<hr data-start="2799" data-end="2802">
<p data-start="2804" data-end="2956">¿Quieres que prepare ahora los <strong data-start="2835" data-end="2907">boards listos para herramienta de gestión tipo Jira, Notion o Trello</strong> con etiquetas, dependencias y estados sugeridos?</p>
<p data-start="2958" data-end="3069" data-is-last-node="" data-is-only-node="">O ¿avanzamos hacia <strong data-start="2977" data-end="3015">la siguiente funcionalidad del PRD</strong> (por ejemplo, "Gestión del Pipeline" o "Evaluación")?</p>

--------------------------------------

