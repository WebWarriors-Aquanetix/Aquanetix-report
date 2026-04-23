## 5.2. Landing Page, Services & Applications Implementation.
El desarrollo de la pagina principal, acoplamiento de servicios e implementación de las aplicaciones se consideran como pasos de alta importancia en lo que refiere a la elaboración del proyecto. Con el apoyo de estas etapas, permite al equipo tranformar conceptos simples en productos preparados para su uso. Esta fase nos ayuda a traducir los requisitos y especificaciones obtenidas a código con la finalidad de cumplir con las necesidades de nuestros segmentos objetivos.

### 5.2.1. Sprint 1
El primer sprint de nuestro proyecto posee una gran importancia en lo que refiere al proceso de desarrollo ágil. A lo largo de este periodo, se ha dado un enfoque con mayor énfasis en la implementación de las caracetericas fundamentales así como en las funcionalidades de mayor prioridad en nuestra planificación de inicio.

#### 5.2.1.1. Sprint Planning 1.

Para este sprint, la reunión de Sprint Planning nos permite evaluar nuestra velocidad previa y definir las nuevas metas técnicas del proyecto. En esta fase, el equipo selecciona las historias de usuario prioritarias del backlog, estima el esfuerzo necesario y asigna las tareas. El objetivo principal es mantener la alineación del equipo y garantizar que las nuevas funcionalidades operativas se integren de manera fluida, estableciendo un plan de trabajo claro.

| Campo / Sección | Detalle |
| :--- | :--- |
| Sprint # | Sprint 1 |
| Date | 2026-04-22 |
| Time | 9:00 PM |
| Location | Google meet |
| Prepared By | Castro Solorza, Nicolas Eduardo |
| Attendees (to planning meeting) | Pinedo Sánchez, Sebastián Martín / Castro Solorza, Nicolás Eduardo / Cochachi Chagua, Sebastián Josué / Cabrera Novoa, Leonardo Moisés |
| Sprint 1  Review Summary | Al ser el primer sprint del proyecto (Fase de Inicio), no hay un Review de entregables previos. Se revisaron los requisitos del Primer Entregable (TB1), estableciendo como prioridad el diseño de la arquitectura base, diseño de base de datos, además de los flujos de registro de empresas. |
| Sprint 1  Retrospective Summary | De igual manera al ser el inicio del proyecto, se establecieron las normas de trabajo del equipo: reuniones de seguimiento (Daily Stand-ups) mediante Meet, uso de herramientas ágiles para el control de tareas, sumado a la necesidad de mantener una comunicación constante para evitar bloqueos técnicos en el desarrollo del backend. |
| Sprint 1 Goal | Para este sprint se requiere el cumplimiento de los siguientes objetivos: Establecer la arquitectura base del backend, desplegar el esquema de la base de datos relacional, configurar el registro de clientes (Enterprise) junto con la seguridad (Login). La métrica de cumplimiento se basará en el proceso de cómo nuestro "Board de Jira" luzca con el paso del tiempo, nuestro resultado final debe de mostrar todas las tareas en el lado derecho de la herramienta, ubicándolos en la columna "Terminado". |
| Sprint 1 Velocity | Para este sprint se han elegido 5 User Stories con estimaciones basadas en la serie de Fibonacci. |
| Sum of Story Points | 26 |

### 5.2.1.2 Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (LACX), donde se definen los roles de cada integrante del equipo en los distintos aspectos considerados dentro del Sprint.

Los aspectos seleccionados corresponden a las principales áreas del proyecto Aquanetix, incluyendo diseño UX/UI, desarrollo de la landing page, documentación y modelado del sistema.

| Team Member (Last Name, First Name) | GitHub Username | UX/UI Design | Landing Page | Documentation | Modeling |
|------------------------------------|----------------|-------------|-------------|--------------|----------|
| Bojórquez Bustinza, Renzo Alejandro | DeterminedSoul7 | C | C | C | L |
| Cabrera Novoa, Leonardo Moisés | u202415820 | C | C | C | C |
| Castro Solorza, Nicolás Eduardo | NicoCSE | C | L | L | C |
| Cochachi Chagua, Sebastian Josue | sebastiancochachi02-cmd | L | C | C | C |
| Pinedo Sanchez, Sebastián Martín | smp1107 | L | C | C | C |

### 5.2.1.3. Sprint Backlog 1.

<table border="1" cellpadding="6" cellspacing="0" style="border-collapse: collapse; text-align: center;">
  
  <!-- Sprint -->
  <tr>
    <th>Sprint #</th>
    <td colspan="7">Sprint n</td>
  </tr>

  <!-- Encabezados principales -->
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>

  <!-- Subencabezados -->
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / In-Process / To-Review / Done)</th>
  </tr>

  <!-- Filas de ejemplo -->
  <tr>
    <td>US-01</td>
    <td>Lorem Ipsum</td>
    <td>T-01</td>
    <td>Diseñar UI</td>
    <td>Crear interfaz de login</td>
    <td>4</td>
    <td>Arturo</td>
    <td>To-do</td>
  </tr>

  <tr>
    <td>US-01</td>
    <td>Lorem Ipsum</td>
    <td>T-02</td>
    <td>Validación backend</td>
    <td>Implementar autenticación</td>
    <td>6</td>
    <td>Jorge</td>
    <td>In-Process</td>
  </tr>

  <tr>
    <td>US-02</td>
    <td>Lorem Ipsum</td>
    <td>T-03</td>
    <td>Formulario registro</td>
    <td>Crear formulario</td>
    <td>5</td>
    <td>Arturo</td>
    <td>Done</td>
  </tr>

</table>

### 5.2.1.4 Development Evidence for Sprint Review

| Repository | Branch | Commit Ids | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
| aquanetix-repo | develop | 4f01889ae5953aba422050a86048518fc2e68577 | docs: add epics for requirements | Added epics to define system requirements structure | 18/04/2026 |
| aquanetix-repo | develop | 80782311c16b14e26ad36489823096a0602afeb2 | docs: add landing page UI design | Defined UI design for the landing page | 20/04/2026 |
| aquanetix-repo | develop | 056333d1b065eda419cb3e109ebf525a4c3749cc | docs: add C4 model diagrams | Added C4 model diagrams for system architecture representation | 21/04/2026 |
| aquanetix-repo | develop | 73157436b4d739e7e78aa21fb0a791de3101dc81 | fix: update repository links | Updated repository links in chapter 5 documentation | 21/04/2026 |
| aquanetix-repo | develop | 68a41d56032b2c50eb7a681cc9581219c6923cd7 | docs: add web app mockups | Added web application mockups to the documentation | 22/04/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review.

### 5.2.1.6 Services Documentation Evidence for Sprint Review

En el alcance del presente Sprint, no se han implementado servicios web ni endpoints documentados con OpenAPI, debido a que el desarrollo del proyecto se ha centrado principalmente en la construcción de la landing page estática y en el diseño del prototipo de la aplicación.
Por lo tanto, en esta fase no se cuenta con documentación de Web Services, ya que estos serán considerados en Sprints posteriores, donde se abordará la implementación técnica del sistema y la integración de servicios backend.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

#### 5.2.1.8. Team Collaboration Insights during Sprint
