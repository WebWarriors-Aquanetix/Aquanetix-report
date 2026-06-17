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
| Attendees (to planning meeting) | Pinedo Sánchez, Sebastián Martín / Castro Solorza, Nicolás Eduardo / Cochachi Chagua, Sebastián Josué / Cabrera Novoa, Leonardo Moisés / Bojórquez Bustinza, Renzo Alejandro |
| Sprint 1  Review Summary | Al ser el primer sprint del proyecto, no existe una revisión de un sprint anterior. El equipo partió de la aprobación del Product Backlog inicial, enfocándose en las Historias de Usuario prioritarias relacionadas al registro de empresas (Enterprise), configuración de planes y seguridad. |
| Sprint 1  Retrospective Summary | De igual manera al ser el inicio del proyecto, se establecieron las normas de trabajo del equipo: reuniones de seguimiento (Daily Stand-ups) mediante Meet, uso de herramientas ágiles para el control de tareas, sumado a la necesidad de mantener una comunicación constante para evitar bloqueos técnicos en el desarrollo del backend. |
| Sprint 1 Goal |Nuestro enfoque se centra en ofrecer el proceso inicial de registro y el acceso seguro a la plataforma para los clientes corporativos.
||Creemos que esto entrega autonomía a los administradores de las EPS para registrar sus organizaciones, seleccionar un plan de suscripción y gestionar de forma segura el acceso de sus ingenieros operativos.
||Esto será confirmado cuando un administrador de la empresa pueda registrar exitosamente su organización, elegir el plan 'Piloto' o 'Integral', e iniciar sesión en el panel de control de Aquanetix de forma segura sin intervención del equipo de soporte técnico.|
| Sprint 1 Velocity | El equipo ha establecido un Velocity de 26 Story Points, que representa la capacidad máxima de esfuerzo que los developers pueden aceptar de manera realista para este Sprint 1. |
| Sum of Story Points | 24 |

#### 5.2.1.2 Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (LACX), donde se definen los roles de cada integrante del equipo en los distintos aspectos considerados dentro del Sprint.

Los aspectos seleccionados corresponden a las principales áreas del proyecto Aquanetix, incluyendo diseño UX/UI, desarrollo de la landing page, documentación y modelado del sistema.

| Team Member (Last Name, First Name) | GitHub Username | UX/UI Design | Landing Page | Documentation | Modeling |
|------------------------------------|----------------|-------------|-------------|--------------|----------|
| Bojórquez Bustinza, Renzo Alejandro | DeterminedSoul7 | C | C | C | L |
| Cabrera Novoa, Leonardo Moisés | u202415820 | C | C | C | C |
| Castro Solorza, Nicolás Eduardo | NicoCSE | C | L | L | C |
| Cochachi Chagua, Sebastian Josue | sebastiancochachi02-cmd | L | C | C | C |
| Pinedo Sanchez, Sebastián Martín | smp1107 | L | C | C | C |

#### 5.2.1.3 Sprint Backlog 1

El objetivo del presente Sprint fue el diseño y desarrollo de la landing page del sistema Aquanetix, enfocándose en la comunicación efectiva de la propuesta de valor, la presentación de funcionalidades clave y la facilitación del contacto con potenciales usuarios.

Durante este Sprint, el equipo trabajó de manera colaborativa en la construcción de las diferentes secciones de la landing page, asegurando una experiencia de usuario clara, intuitiva y alineada con los objetivos del sistema.

<div align="center">
  <img src="../assets/Jira/Sprint1_1.png">
  <img src="../assets/Jira/Sprint1_2.png">
  <img src="../assets/Jira/Sprint1_3.png">
  <img src="../assets/Jira/Sprint1_4.png">
</div>

Enlace a la herramienta utilizada: https://shorturl.at/xs1Pv

A continuación, se detallan las User Stories priorizadas y las tareas asociadas:

| US Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
|------|------|--------|------------|------------|-------------------|-------------|--------|
| US-35 | Product value visualization | T-01 | Landing page structure | Diseño e implementación de la estructura general y sección principal (hero) de la landing page | 6 | Sebastián Pinedo | Done |
| US-36 | System features visualization | T-02 | Features section development | Diseño y desarrollo de la sección de funcionalidades destacando las capacidades del sistema | 5 | Sebastián Cochachi | Done |
| US-37 | Contact information access | T-03 | Contact and CTA section | Implementación de sección de contacto y botones de llamada a la acción | 4 | Nicolás Castro | Done |
| US-35 | Product value visualization | T-04 | Content definition and UX writing | Definición del contenido textual y estructura comunicativa de la landing | 4 | Leonardo Cabrera | Done |
| US-36 | System features visualization | T-05 | Visual design elements | Diseño de elementos visuales y apoyo gráfico para mejorar la experiencia de usuario | 4 | Renzo Bojórquez | In-Process |

#### 5.2.1.4 Development Evidence for Sprint Review

| Repository | Branch | Commit Ids | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
| aquanetix-repo | develop | 4f01889ae5953aba422050a86048518fc2e68577 | docs: add epics for requirements |  | 18/04/2026 |
| aquanetix-repo | develop | 80782311c16b14e26ad36489823096a0602afeb2 | docs: add landing page UI design |  | 20/04/2026 |
| aquanetix-repo | develop | 056333d1b065eda419cb3e109ebf525a4c3749cc | docs: add C4 model diagrams |  | 21/04/2026 |
| aquanetix-repo | develop | 73157436b4d739e7e78aa21fb0a791de3101dc81 | fix: update repository links |  | 21/04/2026 |
| aquanetix-repo | develop | 68a41d56032b2c50eb7a681cc9581219c6923cd7 | docs: add web app mockups |  | 22/04/2026 |

#### 5.2.1.5 Execution Evidence for Sprint Review

En esta sección se presentan evidencias de la ejecución de la landing page desarrollada durante el Sprint.

Las siguientes capturas muestran la interacción del usuario con las diferentes secciones de la landing page, permitiendo validar la estructura de información, la propuesta de valor y la navegación definida para el sistema Aquanetix.

**Figura 1. Sección principal de la landing page**

<div align="center">
  <img src="../assets/LandingPage/Landing1.png">
</div>
La figura muestra la sección principal de la landing page, donde se presenta la propuesta de valor del sistema Aquanetix junto con un llamado a la acción dirigido al usuario.


**Figura 2. Sección informativa de la landing page**

<div align="center">
  <img src="../assets/LandingPage/Landing2.png">
</div>

En esta sección se describe el problema abordado y la solución propuesta por el sistema, permitiendo al usuario comprender el propósito y beneficios del servicio.

**Figura 3. Sección de funcionalidades**

<div align="center">
  <img src="../assets/LandingPage/Landing3.png">
</div>

La figura muestra las principales funcionalidades del sistema, destacando las capacidades de monitoreo, gestión de alertas y análisis de datos.

**Figura 4. Sección final y llamado a la acción**

<div align="center">
  <img src="../assets/LandingPage/Landing4.png">
</div>

En esta sección final se incluye un llamado a la acción que invita al usuario a interactuar con el sistema, junto con información adicional relevante.

#### 5.2.1.6 Services Documentation Evidence for Sprint Review

En el alcance del presente Sprint, no se han implementado servicios web ni endpoints documentados con OpenAPI, debido a que el desarrollo del proyecto se ha centrado principalmente en la construcción de la landing page estática y en el diseño del prototipo de la aplicación.
Por lo tanto, en esta fase no se cuenta con documentación de Web Services, ya que estos serán considerados en Sprints posteriores, donde se abordará la implementación técnica del sistema y la integración de servicios backend.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Esta seccion se ha decidido omitir debido que, para este avance, solamente se ha enfocado en el diseño de Landing Page. En futuros entregables se procedera a brindar una informacion mas detallada de la aplicacion.

#### 5.2.1.8. Team Collaboration Insights during Sprint

Para el desarrollo de este primer sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.
<p align = "left">
   <img src="../assets/insights/Team Collaboration Insights.jpg">
</p>

### 5.2.2. Sprint 2
El segundo sprint de nuestro proyecto estuvo enfocado en el desarrollo de funcionalidades relacionadas al monitoreo inteligente de la red hídrica, la gestión de alertas automáticas y la administración de parámetros operativos dentro del sistema. Durante este periodo, el equipo priorizó la implementación de módulos backend orientados al procesamiento de datos de sensores, validación de condiciones críticas y generación de información operativa para supervisores y operadores técnicos.

#### 5.2.2.1. Sprint Planning 2.

En esta sección se especifican los aspectos principales del Sprint Planning Meeting. El segundo sprint de nuestro proyecto posee una gran importancia en lo que refiere al proceso de desarrollo ágil y la construcción de la lógica de negocio en el backend. A lo largo de este periodo, se ha dado un enfoque con mayor énfasis en la implementación de las características fundamentales de monitoreo químico y la gestión de acceso, así como en las funcionalidades de mayor prioridad en nuestra planificación de inicio, asegurando que el equipo entregue valor tangible a los usuarios de la plataforma.

| Campo / Sección | Detalle |
| :--- | :--- |
| Sprint # | Sprint 2 |
| Date | 2026-05-10 |
| Time | 9:00 PM |
| Location | Google meet |
| Prepared By | Castro Solorza, Nicolas Eduardo |
| Attendees (to planning meeting) | Pinedo Sánchez, Sebastián Martín / Castro Solorza, Nicolás Eduardo / Cochachi Chagua, Sebastián Josué / Cabrera Novoa, Leonardo Moisés / Bojórquez Bustinza, Renzo Alejandro |
| Sprint 2  Review Summary | Durante el Sprint 2 se lograron desplegar los cimientos de la arquitectura frontend y los endpoints iniciales pertenecientes a los bounded context identificados. El Product Owner validó positivamente la estructura inicial, pero resaltó que para entregar verdadero valor al negocio es prioritario enfocarse ahora en el flujo de suscripciones que habilita los tableros, y en el motor de reglas de los sensores químicos para la detección temprana de anomalías. |
| Sprint 2  Retrospective Summary | El equipo identificó como un gran acierto la comunicación constante en los Daily Stand-ups. Sin embargo, como oportunidad de mejora, se evidenció la necesidad de aplicar de forma más estricta las buenas prácticas de programación (uso de DTOs, Inyección de Dependencias y manejo de excepciones) desde la planificación de las tareas, para evitar bloqueos técnicos y mantener un flujo de trabajo continuo. |
| Sprint 2 Goal |Nuestro enfoque está en implementar un control de acceso automatizado por suscripciones y configurar los rangos de seguridad para los sensores químicos (pH) en la API del frontend.
||Creemos que esto entrega una experiencia de inicio ágil y capacidades de monitoreo proactivo para prevenir la corrosión de las tuberías a los operadores técnicos.
||Esto se confirmará cuando los operadores técnicos puedan adquirir con éxito una suscripción para desbloquear los endpoints protegidos del tablero, y el sistema evalúe correctamente las lecturas de los umbrales de pH, activando alertas de forma precisa sin fallos en el backend cuando los valores superen los límites permitidos. |
| Sprint 2 Velocity | Para este Sprint 2, evaluando el desempeño previo y la capacidad actual del equipo, se ha establecido un Velocity de 67 Story Points. |
| Sum of Story Points | 67 |

#### 5.2.2.2 Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (LACX), donde se definen los roles de cada integrante del equipo en los distintos aspectos considerados dentro del Sprint.

Los aspectos seleccionados corresponden a las principales áreas del proyecto Aquanetix, incluyendo diseño UX/UI, desarrollo de la web application, documentación y modelado del sistema.

| Team Member (Last Name, First Name) | GitHub Username | UX/UI Design | Web Application | Documentation | Modeling |
|------------------------------------|----------------|-------------|-------------|--------------|----------|
| Bojórquez Bustinza, Renzo Alejandro | DeterminedSoul7 | C | C | C | L |
| Cabrera Novoa, Leonardo Moisés | u202415820 | C | L | C | C |
| Castro Solorza, Nicolás Eduardo | NicoCSE | C | C | L | C |
| Cochachi Chagua, Sebastian Josue | sebastiancochachi02-cmd | L | C | C | C |
| Pinedo Sanchez, Sebastián Martín | smp1107 | L | C | C | C |


#### 5.2.2.3. Sprint Backlog 2

El objetivo de este sprint backlog 2 fue el designar tareas referente al frontend de nuestra web application del sistema Aquanetix en lo que refiere a diseño y funcionalidad. Mayormente el enfoque fue la maquetación de los paneles de control y la integración de la interfaz con las lógicas de estado, garantizando que el sistema refleje adecuadamente los datos de calidad de agua y las métricas operativas del usuario.

Durante este Sprint, el equipo trabajó de manera colaborativa en la construcción de las diferentes secciones de la web application, asegurando una muestra del como funciona la aplicacion que se está proponiendo.

<div align="center">
  <img src="../assets/Jira/Captura SB2.png">
  <img src="../assets/Jira/CapturaSB2_2.png">
  <img src="../assets/Jira/CapturaSB2_3.png">
  <img src="../assets/Jira/CapturaSB2_4.png">
</div>

Enlace a la herramienta utilizada: https://shorturl.at/xs1Pv

A continuación, se detallan las User Stories priorizadas y las tareas asociadas:

| US Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
|------|------|--------|------------|------------|-------------------|-------------|--------|
| US-38 | Detectar alertas críticas en tiempo real | T-01 | Implementar lógica de detección de alertas | Implementar lógica de detección de alertas | 6 | Sebastián Pinedo | Done |
| US-5 | Actualizar automáticamente el estado de los sensores | T-02 | Implementar actualización automática de estados | Implementar actualización automática de estados | 5 | Sebastián Cochachi | Done |
| US-11 | Generar alertas automáticas por valores fuera de rango | T-03 | Configurar generación automática de alertas | Configurar generación automática de alertas | 4 | Nicolás Castro | Done |
| US-12 | Clasificar alertas según nivel de riesgo | T-04 | Implementar lógica de clasificación automática de alertas por nivel de riesgo | Implementar lógica de clasificación automática de alertas por nivel de riesgo | 4 | Leonardo Cabrera | Done |




#### 5.2.2.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Ids | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
| WebApplication_Aquanetix | develop | 236860c843b3994a07d4343fea70ae5e2d23547c | feat: add environment configuration and mock data for sensors, alerts, and subscription |  | 11/05/2026 |
| WebApplication_Aquanetix | develop | b91719d0b7528d4590acb04b9cad82ace9ab4f44 | feat: add suscription view and global styles |  | 11/05/2026 |
| WebApplication_Aquanetix | develop | 42029d5820c7057a3c83a8f369ef244e052a8931 | feat: add monitoring api |  | 11/05/2026 |
| WebApplication_Aquanetix | develop | 14ad2b6af63d89a504668db6d7c9ee7ee666c404 | feat: set up global router with monitoring routes |  | 11/05/2026 |
| WebApplication_Aquanetix | develop | 711f56ed7ee0b2c4e00645e420774cdd44102c5b | feat: add shared layout and language switcher components |  | 11/05/2026 |

#### 5.2.2.5. Execution Evidence for Sprint Review

En esta sección se presentan evidencias de la ejecución de la web application desarrollada durante el Sprint.

Las siguientes capturas muestran la interacción del usuario con las diferentes secciones de la web application.

**Figura 1. Dashboard principal**

<div align="center">
  <img src="../assets/web_applications/Web-App-Cap1.jpg">
</div>

La figura muestra el dashboard principal de la web application Aquanetix, donde el usuario puede visualizar en tiempo real el estado general del sistema, incluyendo dispositivos activos, alertas críticas, volumen tratado y eficiencia operativa. Además, se presentan tablas y paneles informativos que facilitan el monitoreo y supervisión de los sensores conectados.

**Figura 2. Listado de dispositivos**

<div align="center">
  <img src="../assets/web_applications/Web-App-Cap2.jpg">
</div>

La figura muestra la sección de dispositivos de la aplicación web, donde se presenta una tabla con todos los sensores registrados en el sistema. El usuario puede visualizar información relevante como ubicación, tipo de sensor, valor actual y estado operativo, además de realizar acciones de consulta y edición sobre cada dispositivo.

**Figura 3. Registro de nuevo dispositivo**

<div align="center">
  <img src="../assets/web_applications/Web-App-Cap3.jpg">
</div>

La figura representa el formulario de registro de nuevos dispositivos dentro de la plataforma Aquanetix. El usuario puede ingresar información relacionada al sensor, como nombre, ubicación, tipo, unidad de medida y umbrales permitidos, facilitando la incorporación de nuevos dispositivos al sistema de monitoreo.

**Figura 4. Gestión de alertas**

<div align="center">
  <img src="../assets/web_applications/Web-App-Cap4.jpg">
</div>

La figura muestra el módulo de alertas de la aplicación web, en el cual el usuario puede visualizar y gestionar alertas activas generadas por los sensores del sistema. Cada alerta incluye información relacionada al dispositivo, nivel de prioridad y ubicación, permitiendo identificar rápidamente incidencias críticas dentro de la operación.

**Figura 5. Gestión de suscripción**

<div align="center">
  <img src="../assets/web_applications/Web-App-Cap5.jpg">
</div>

La figura presenta la sección de suscripción de la plataforma, donde el usuario puede consultar la información de su plan actual, visualizar el uso de recursos disponibles y acceder a datos de facturación. Asimismo, se incluyen opciones para cambiar o cancelar la suscripción según las necesidades del usuario.

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

En el alcance del presente Sprint 2, el equipo no ha implementado un Web Service propio con documentación OpenAPI/Swagger, dado que el backend formal en ASP.NET Core corresponde a un entregable posterior (AV2/TB2). Sin embargo, la Frontend Web Application integra dos servicios REST externos que actúan como fuente de datos simulada durante esta fase de desarrollo:

**Servicio 1 — MockAPI (Sensores y Alertas)**
URL base: `https://6a01f74d0d92f63dd2531d8e.mockapi.io/api/v1`

| Endpoint | Verbo HTTP | Descripción | Parámetros | Response ejemplo |
|----------|-----------|-------------|------------|-----------------|
| `/sensors` | GET | Obtiene todos los dispositivos IoT registrados | — | Array de objetos Sensor (id, name, location, type, currentValue, unit, status, minAlert, maxAlert, history) |
| `/sensors/{id}` | GET | Obtiene un dispositivo por ID | `id`: string | Objeto Sensor |
| `/sensors` | POST | Registra un nuevo dispositivo IoT | Body: objeto Sensor sin id | Objeto Sensor creado con id asignado |
| `/sensors/{id}` | PUT | Actualiza datos de un dispositivo | `id`: string · Body: objeto Sensor | Objeto Sensor actualizado |
| `/sensors/{id}` | DELETE | Elimina un dispositivo | `id`: string | Objeto eliminado |
| `/alerts` | GET | Obtiene todas las alertas del sistema | — | Array de objetos Alert (id, sensorName, location, type, severity, message, timestamp, status, value, threshold) |
| `/alerts` | POST | Crea una nueva alerta automática | Body: objeto Alert sin id | Objeto Alert creado |
| `/alerts/{id}` | PUT | Actualiza el estado de una alerta (ej. Resuelta) | `id`: string · Body: objeto Alert | Objeto Alert actualizado |
| `/alerts/{id}` | DELETE | Elimina una alerta | `id`: string | Objeto eliminado |

**Servicio 2 — MockAPI (Suscripción y Planes)**
URL base: `https://69fb530188a7af0ecca8fada.mockapi.io/api/v1`

| Endpoint | Verbo HTTP | Descripción | Parámetros | Response ejemplo |
|----------|-----------|-------------|------------|-----------------|
| `/subscription` | GET | Obtiene la suscripción activa de la empresa | — | Objeto con plan, tier, price, currency, billingCycle, features, usage |
| `/subscription/{id}` | PUT | Actualiza el plan de suscripción | `id`: string · Body: objeto Subscription | Objeto Subscription actualizado |
| `/plans` | GET | Obtiene los planes disponibles | — | Array de objetos Plan (id, name, tier, monthlyPrice, annualMonthlyPrice, maxSensors, highlight, features) |

La interacción con estos servicios se realiza a través de la infraestructura definida en las clases `BaseApi`, `BaseEndpoint` y `MonitoringApi`, siguiendo la arquitectura DDD implementada en la aplicación. Las variables de entorno `VITE_AQUANETIX_API_URL`, `VITE_SUBSCRIPTION_API_URL` y las rutas de cada endpoint están configuradas en el archivo `.env` del proyecto.


#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2, el equipo realizó el despliegue de la primera versión funcional de la **Frontend Web Application** de Aquanetix en Firebase Hosting, plataforma de hosting en la nube de Google. A continuación se describen los pasos realizados.

**1. Configuración del proyecto en Firebase**

Se creó el proyecto `aquanetix-deploy` en [console.firebase.google.com](https://console.firebase.google.com), habilitando el servicio Firebase Hosting. Se vinculó el proyecto local ejecutando:

```bash
firebase login
firebase init hosting
```

Durante la inicialización se configuró `dist/` como directorio público (output del build de Vite) y se habilitó el modo Single Page Application para que todas las rutas redirijan a `index.html`.

**2. Configuración del firebase.json**

Se configuró el archivo `firebase.json` con las reglas de reescritura necesarias para el routing de Vue Router, además de headers de caché optimizados:

```json
{
  "hosting": {
    "public": "dist",
    "ignore": ["firebase.json", "**/.*", "**/node_modules/**"],
    "headers": [
      {
        "source": "/index.html",
        "headers": [
          { "key": "Cache-Control", "value": "no-cache, no-store, must-revalidate" }
        ]
      },
      {
        "source": "/assets/**",
        "headers": [
          { "key": "Cache-Control", "value": "public, max-age=31536000, immutable" }
        ]
      }
    ],
    "rewrites": [{ "source": "**", "destination": "/index.html" }]
  }
}
```

**3. Build y despliegue**

Se generó el build de producción con Vite y se desplegó con los siguientes comandos:

```bash
npm run build
firebase deploy
```

**4. URL de la aplicación desplegada**

La aplicación quedó publicada y accesible en:

🔗 **[https://aquanetix-deploy.web.app](https://aquanetix-deploy.web.app)**

Al acceder a la URL raíz, el sistema redirige automáticamente a `/monitoring/dashboard`, donde se puede visualizar el Dashboard principal con los datos en tiempo real provenientes de las APIs externas configuradas.

**5. Configuración de variables de entorno**

Las variables de entorno necesarias para conectar con las APIs externas se configuraron localmente en el archivo `.env` (excluido del repositorio por seguridad):

```
VITE_AQUANETIX_API_URL=https://6a01f74d0d92f63dd2531d8e.mockapi.io/api/v1
VITE_SENSORS_ENDPOINT_PATH=/sensors
VITE_ALERTS_ENDPOINT_PATH=/alerts
VITE_SUBSCRIPTION_API_URL=https://69fb530188a7af0ecca8fada.mockapi.io/api/v1
VITE_SUBSCRIPTION_ENDPOINT_PATH=/subscription
VITE_PLANS_ENDPOINT_PATH=/plans
```

**6. Versiones desplegadas**

El panel de Firebase Hosting registra el historial de versiones del Sprint 2, evidenciando las iteraciones de despliegue realizadas durante el desarrollo:

| Versión | Fecha | Descripción |
|---------|-------|-------------|
| e6b1a0 | 11/05/2026 | Versión final Sprint 2 — i18n completo, cambio de plan, gestión de alertas |
| f270f5 | 11/05/2026 | Fix: routing SPA y caché headers |
| 0dbaf0 | 11/05/2026 | Feat: subscription change plan view |
| 2e3863 | 11/05/2026 | Feat: dashboard y sensor detail views |

#### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de este segundo sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.
<p align = "left">
   <img src="../assets/insights/team-insights.jpg">
</p>

### 5.2.2. Sprint 2

#### 5.2.2.3. Sprint Planning 3.

| Campo / Sección | Detalle |
| :--- | :--- |
| Sprint # | Sprint 3 |
| Date | 2026-06-14 |
| Time | 9:00 PM |
| Location | Google meet |
| Prepared By | Castro Solorza, Nicolas Eduardo |
| Attendees (to planning meeting) | Pinedo Sánchez, Sebastián Martín / Castro Solorza, Nicolás Eduardo / Cochachi Chagua, Sebastián Josué / Cabrera Novoa, Leonardo Moisés / Bojórquez Bustinza, Renzo Alejandro |
| Sprint 3  Review Summary | Durante el sprint 3, se logro desplegar la arquitectura backend de la aplicacion web, y crear los endpoints relacionados a los bounded context identificados. Asimismo, se corrigieron varias observaciones identificadas tanto en la Landing Page como en la aplicacion frontend. El Product Owner aprobo la estructura inicial, mas recomendo poner un mayor enfasis en la interaccion de backend con el frontend. |
| Sprint 3  Retrospective Summary | El equipo identifico como acierto verificar la funcionalidad de los endpoints antes de subirlos al repositorio. Sin embargo, como oportunidad de mejora, se identifico implementar el uso de GitFlow en nuestro proyecto para trabajar de manera mas ordenada.|
| Sprint 3 Goal |Nuestro enfoque esta en habilitar la integracion completa de los modulos de Dashboard, Devices, Monitoring, Subscription y Service Design.
||Creemos que esto proporciona autonomia en la gestion de planes y una visibilidad operativa fiable en tiempo real para las empresas prestadoras de servicios de agua y gestoras de residuos solidos.
||Esto se confirmará cuando los clientes puedan actualizar y ver los datos logisticos, como sus dispositivos conectados y alertas, obtenidos dinamicamente de la base de datos, sin depender de datos codificados.|
| Sprint 3 Velocity |Para este Sprint 3, evaluando el desempennio previo, capacidad actual del equipo, y circunstancias actuales de tiempo, se establecio un Velocity de 112 Story Points.|
| Sum of Story Points | 112 |
