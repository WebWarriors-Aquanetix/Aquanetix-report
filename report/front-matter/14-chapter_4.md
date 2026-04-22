# Capítulo IV: Product Design

## 4.1. Style Guidelines:
Se considera un **Style Guideline** al conjunto de reglas y estándares que definen el cómo se debe redactar, diseñar y/o presentar diversas interfaces web, documentos, software u otros productos creativos, con el fin de asegurar una coherencia visual de un proyecto. A continuación se procederá a describir de forma más detallada los parámetros implementados en nuestra propuesta. 
### 4.1.1. General Style Guidelines
#### Branding
La identidad de Aquanetix se basa en el principio de "Ingeniería Hídrica Circular". Buscamos proyectar una imagen de tecnología de vanguardia aplicada directamente a la regeneración de un recurso natural. El logo es la materialización de este concepto: la fusión de la gota (naturaleza) y el nodo (tecnología/IoT).

Principios de Diseño:

> * Tecno-Naturaleza: Los componentes visuales deben equilibrar lo orgánico (formas fluidas del agua) con lo geométrico (precisión de los datos).
> * Claridad Operativa: La interfaz debe priorizar la legibilidad de métricas críticas sobre la ornamentación.
> * Transparencia: Reflejar la honestidad académica de la UPC en la presentación de datos.

#### Tipografía
La tipografía debe reflejar la solidez de una solución corporativa/municipal.
> * Encabezados (Manrope): Se utilizará en pesos Bold (700) y SemiBold (600). Su estructura geométrica y moderna da una imagen de startup sólida.
> * Cuerpo de Texto y Labels (Inter): Se utilizará para toda la lectura de datos, tablas y etiquetas. Es la fuente estándar en interfaces de alta densidad por su claridad en tamaños pequeños.
 <div align="center"><img src="/report/assets/LandingPage/tipografía.jpg" width ="400" height="700"></div>

#### Colores
La paleta utilizada para el sitio web le da un mayor protagonismo a los azules vibrantes:
> * Azul cobalto (#007BFF): El color que representa la identidad de la app, usado para botones principales, navegación y estados de "Agua Limpia".
> * Verde esmeralda (#10B981): Acentos de éxito, sostenibilidad, recuperación y estados "Activo/Óptimo".
> * Verde bosque (#064E3B): Fondos de secciones oscuras, iconos de naturaleza y estados de "Eco-impacto".
> * Blanco pizarrón (#F1F5F9): Fondos de la aplicación (UI), tarjetas de datos y separación de secciones.
<div align="center"><img src="/report/assets/LandingPage/paleta de colores.jpg" width ="400" height="700"></div>

#### Principios de espaciado
Utilizaremos un sistema de espaciado basado en una rejilla de 8px (base 8). Esto garantiza que todos los componentes (gráficos de sensores, menús, tarjetas) tengan una relación matemática limpia. El espacio negativo debe ser amplio para reducir la "carga cognitiva" en dashboards complejos.

#### Tono de comunicación
Los tonos de comunicación serán mayormente serios, con un toque de entusiasmo. Queremos priorizar la precisión técnica y la confianza municipal, a la vez que queremos transmitir que el cambio es posible mediante la tecnología.

### 4.1.2. Web Style Guidelines:

Para la interfaz web de Aquanetix, el diseño se fundamenta en una estructura modular basada en contenedores limpios, priorizando la rápida lectura de grandes volúmenes de datos operativos. Los paneles de control principales utilizarán una disposición en cuadrícula para permitir a los supervisores visualizar métricas complejas de manera estructurada. Además, se aplicarán bordes sutilmente redondeados junto con sombras difuminadas para generar jerarquía visual. De este modo, aseguramos mantener la atención del usuario enfocada estrictamente en los indicadores críticos, como el porcentaje de llenado de lixiviados o las alertas de sobreconsumo, previniendo la fatiga visual durante jornadas extensas de monitoreo.
Por otro lado, respecto a la interactividad de la plataforma, los componentes están diseñados para ofrecer retroalimentación inmediata, cambiando de estado visualmente al recibir clics o desplazamientos del cursor. Resulta indispensable que toda la interfaz responda fluidamente a distintos tamaños de pantalla mediante principios de diseño adaptable (responsive design). Así, garantizamos una experiencia de uso coherente tanto para un gerente que exporta reportes de huella hídrica desde una computadora de escritorio en la oficina, como para un operario que ingresa registros en tiempo real desde su teléfono móvil en medio del patio de maniobras.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

En Aquanetix, la información se agrupa para evitar la fatiga cognitiva frente a la densidad de datos IoT:
> * Esquema Jerárquico: La navegación fluye de lo general a lo particular, iniciando en un Dashboard Global de la red hídrica y profundizando hasta el detalle de sensores individuales.
> * Estructura Híbrida: Se combina la organización temática por parámetros (pH, flujo, gases) con un registro cronológico para el historial de alertas y eventos.

### 4.2.2. Labeling Systems

El sistema de etiquetado utiliza terminología familiar para gestores de operaciones y sostenibilidad:
> * Etiquetas de Navegación: Términos directos como "Inicio", "Solución", "Beneficios" y "Acceso al Dashboard".
> * Etiquetas de Datos: Métricas bajo estándares industriales como "Nivel de pH", "Caudal (m³/s)" y "Concentración de Gases (ppm)".
> * Etiquetas de Estado: Sistema semántico de urgencia: Crítico (Rojo), Advertencia (Ámbar) y Óptimo (Verde).

### 4.2.3. SEO Tags and Meta Tags
Para garantizar el posicionamiento de la Landing Page y la relevancia en búsquedas corporativas:

> * Indexado y Crawling: Uso de etiquetas meta name="robots" content="index, follow" para permitir que los buscadores rastreen la solución.
> * Meta Title: "Aquanetix | Inteligencia Hídrica para un Perú Sostenible" (Optimizado para captar interés institucional).
> * Meta Description: "Sistema de monitoreo IoT y gestión automatizada para la recuperación de recursos hídricos. Reduzca costos operativos y optimice la sostenibilidad de su flota".
> * Palabras clave: Gestión hídrica Perú, monitoreo IoT agua, recuperación de agua industrial, Aquanetix, WebWarriors UPC.

### 4.2.4. Searching Systems
Diseñados para encontrar métricas críticas en menos de tres clics:

> * Barra Global (Omnisearch): Con función de auto-completado para IDs de sensores o zonas críticas. (Por definir)
> * Filtros Avanzados: Segmentación por temporalidad (rangos de fechas), ubicación (zonas de la planta) y nivel de riesgo de las alertas.
> * Visualización de Resultados: Resaltado de términos (highlighting) y estados de "Cero resultados".

### 4.2.5. Navigation Systems
Garantizan que el usuario siempre mantenga el control sobre su ubicación en el sistema:

> * Navegación Global (Header): Barra persistente con acceso rápido al Dashboard y secciones principales de la landing.
> * Navegación Local (Sidebar): Menú lateral en el Dashboard para transitar entre Alertas, Mantenimiento y Reportes.
> * Breadcrumbs: Rastro de navegación para auditorías profundas (ej. Dashboard > Zona Norte > Sensor pH-04).
> * Navegación de Salida (Footer): Enlaces a políticas de privacidad, términos de servicio y contacto con WebWarriors.

## 4.3. Landing Page UI Design
El planteamiento del diseño de la interfaz de usuario para nuestra landing page se considerará fundamental para el proyecto debido a que es una primera impresión hacia los usuarios del cómo se visualizará y qué objetivo presentará. Gracias a esto, nos permitira obtener la informacion necesaria para causar una gran impresión y mayor interés en la navegación de la página.
### 4.3.1. Landing Page Wireframe
El wireframe de la landing page de Aquanetix organiza los elementos principales para ofrecer una navegación clara e intuitiva. Incluye un encabezado con el logo y menú de navegación, seguido de una sección principal con la propuesta de valor y botones de acción. Posteriormente, se presentan secciones que describen el problema de la gestión hídrica, la solución propuesta y las funcionalidades del sistema. La versión mobile reorganiza estos elementos en una estructura vertical, priorizando la legibilidad y la interacción táctil. Finalmente, se incluye una llamada a la acción y un pie de página con enlaces informativos.
#### Web Browser Wireframe
<div align="center"><img src="/report/assets/LandingPage/Web Browser Wireframe.png" width ="100%"></div>

#### Mobile Browser Wireframe
<div align="center"><img src="/report/assets/LandingPage/Mobile Browser Wireframe.png" width ="100%"></div>

### 4.3.2. Landing Page Mock-up
El mockup de la landing page de Aquanetix presenta un diseño limpio y estructurado, basado en los wireframes definidos previamente. Se destacan la propuesta de valor, las funcionalidades del sistema y los beneficios mediante el uso de jerarquía visual, colores y componentes como botones y tarjetas informativas. La interfaz mantiene una organización clara tanto en desktop como en mobile, facilitando la navegación del usuario. El diseño está orientado a comunicar de manera efectiva la solución tecnológica y motivar la interacción mediante una llamada a la acción.
#### Web Browser Mock-up
<div align="center"><img src="/report/assets/LandingPage/Web Browser Mock-Up.png" width ="100%"></div>

#### Mobile Browser Mock-up
<div align="center"><img src="/report/assets/LandingPage/Moblie Browser Mock-Up.png" width ="100%"></div>

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups

## 4.5. Web Applications Prototyping

### 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
### 4.6.2. Software Architecture Context Diagram

Este diagrama representa el nivel más alto de abstracción, mostrando el sistema como un solo elemento y detallando sus interacciones con el mundo exterior.

<div align="center"><img src="/report/assets/c4_diagrams/Diagrama_Contexto_Aquanetix.png" width ="100%"></div>

> * Centro del Sistema: Aquanetix se posiciona como el núcleo que recolecta y procesa datos para la reutilización de agua en estado deficiente.
> * Usuarios (Actors): Se identifican al Prestador de servicios de agua y al Gestor de residuos sólidos, quienes interactúan con la plataforma para sus respectivas labores operativas.
> * Sistemas Externos: El ecosistema se integra con Sensores IoT (PH, Gas y Flujo) para la captura de datos, Stripe para la gestión de pagos, Google Maps para la logística de rutas y Google Notifications para el envío de alertas móviles.

### 4.6.3. Software Architecture Container Diagrams

El diagrama de contenedores desglosa el sistema en sus unidades de ejecución principales, especificando las decisiones tecnológicas adoptadas.

<div align="center"><img src="/report/assets/c4_diagrams/Diagrama_Contenedores_Aquanetix.png" width ="100%"></div>

> * Web Application: Desarrollada en Vue.js, es la interfaz responsiva donde los usuarios visualizan el dashboard y alertas.
> * Landing Page: Un sitio estático construido con HTML, CSS y JS destinado al marketing y captación de clientes.
> * API Application: Es el contenedor central desarrollado en ASP.NET Core API con C#. Este monolito modular expone los servicios que consumen las aplicaciones web y procesa la información de los sensores.
> * Database: Un contenedor de MySQL que actúa como motor de base de datos relacional para la persistencia de toda la información del sistema.

### 4.6.4. Software Architecture Components Diagrams

Este diagrama profundiza en el contenedor API Application, revelando cómo se organiza internamente la lógica de negocio basada en los Bounded Contexts identificados en el proceso de diseño.

<div align="center"><img src="/report/assets/c4_diagrams/Diagrama_Componentes_Aquanetix.png" width ="100%"></div>

> * Sensores IoT: Componente encargado de procesar la telemetría técnica recibida del hardware.
> * Análisis de Calidad: Componente que determina la potabilidad o toxicidad del agua recolectada.
> * Suscripción: Componente que gestiona los planes comerciales, pagos y el ciclo de vida de los usuarios de la plataforma.
> * Mantenimiento y Distribución: Componentes que coordinan las operaciones de campo y la logística de entrega de agua recuperada a los sectores con necesidad hídrica.
> * Distribución del agua: Componente que coordina la logística de entrega del recurso hídrico certificado y el cálculo de indicadores de impacto.

## 4.7. Software Object-Oriented Design
### 4.7.1 Class Diagrams

## 4.8. Database Design
