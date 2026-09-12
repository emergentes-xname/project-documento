<h2 style="text-align:center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"
       alt="logo-upc" width="200" height="200"
       style="display:block; margin:0 auto;">
</h2>

<h1 style="text-align:center">Universidad Peruana de Ciencias Aplicadas</h1>

<h3 style="text-align:center; margin-top:18px; margin-bottom:18px;">
  Ingeniería de Software
  <br><br>
  Ciclo: 2026-20
  <br><br>
  Curso: Arquitecturas De Software Emergentes
  <br><br>
  Sección: 9056
  <br><br>
  Profesor: Enrique Alejandro Valdivia Verde
  <br><br>
  Informe del Trabajo Final
  <br><br>
  Startup: HampCoders New Generation
  <br><br>
  Producto: ElectroLonk
</h3>

<table style="margin: 0 auto; width: auto; display: table; border-collapse: collapse; font-size: 12pt;">
  <thead>
    <tr>
      <th style="border:1px solid #000; padding:6px 12px; text-align:center;">Alumno</th>
      <th style="border:1px solid #000; padding:6px 12px; text-align:center;">Código</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="border:1px solid #000; padding:6px 12px; text-align:center;">Cesar Augusto Arostegui Alzamora</td><td style="border:1px solid #000; padding:6px 12px; text-align:center;">u202114548</td></tr>
    <tr><td style="border:1px solid #000; padding:6px 12px; text-align:center;">********************************</td><td style="border:1px solid #000; padding:6px 12px; text-align:center;">**********</td></tr>
  </tbody>
</table>

<div style="text-align:center; margin-top:18px;"> Diciembre 2026 </div>

<hr>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe  
---

<div align="center">

| Versión | Fecha       | Autor(es)                                                                 | Descripción de modificación |
|---------|-------------|---------------------------------------------------------------------------|------------------------------|

</div>

# Project Report Collaboration Insights  


## Evidencia de colaboración en GitHub


---

# Contenido
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.1. Software Architecture Context Level Diagrams](#431-software-architecture-context-level-diagrams)
    - [4.3.2. Software Architecture Container Level Diagrams](#432-software-architecture-container-level-diagrams)
    - [4.3.3. Software Architecture Deployment Diagrams](#433-software-architecture-deployment-diagrams)
- [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.X. Bounded Context: \<Bounded Context Name\>](#5x-bounded-context-bounded-context-name)
    - [5.X.1. Domain Layer](#5x1-domain-layer)
    - [5.X.2. Interface Layer](#5x2-interface-layer)
    - [5.X.3. Application Layer](#5x3-application-layer)
    - [5.X.4. Infrastructure Layer](#5x4-infrastructure-layer)
    - [5.X.6. Bounded Context Software Architecture Component Level Diagrams](#5x6-bounded-context-software-architecture-component-level-diagrams)
    - [5.X.7. Bounded Context Software Architecture Code Level Diagrams](#5x7-bounded-context-software-architecture-code-level-diagrams)
      - [5.X.7.1. Bounded Context Domain Layer Class Diagrams](#5x71-bounded-context-domain-layer-class-diagrams)
      - [5.X.7.2. Bounded Context Database Design Diagram](#5x72-bounded-context-database-design-diagram)
- [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.2. Labeling Systems](#622-labeling-systems)
    - [6.2.3. Searching Systems](#623-searching-systems)
    - [6.2.4. SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
    - [6.2.5. Navigation Systems](#625-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.2. Applications Mock-ups](#642-applications-mock-ups)
    - [6.4.3. Applications User Flow Diagrams](#643-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
- [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.X. Sprint n](#72x-sprint-n)
      - [7.2.X.1. Sprint Planning n](#72x1-sprint-planning-n)
      - [7.2.X.2. Sprint Backlog n](#72x2-sprint-backlog-n)
      - [7.2.X.3. Development Evidence for Sprint Review](#72x3-development-evidence-for-sprint-review)
      - [7.2.X.4. Testing Suite Evidence for Sprint Review](#72x4-testing-suite-evidence-for-sprint-review)
      - [7.2.X.5. Execution Evidence for Sprint Review](#72x5-execution-evidence-for-sprint-review)
      - [7.2.X.6. Services Documentation Evidence for Sprint Review](#72x6-services-documentation-evidence-for-sprint-review)
      - [7.2.X.7. Software Deployment Evidence for Sprint Review](#72x7-software-deployment-evidence-for-sprint-review)
      - [7.2.X.8. Team Collaboration Insights during Sprint](#72x8-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)
    - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)
  - [7.4. Video About-the-Product](#74-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.** |  |  |
| **Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería..** |  |  |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Hampcoders es una startup enfocada en el desarrollo de soluciones tecnológicas innovadoras que integran Internet de las Cosas (IoT) y desarrollo de software para el sector de la restauración y retail en Lima Metropolitana. La empresa nace con la visión de transformar la gestión operativa y de seguridad en entornos comerciales de alto tráfico.

Nuestra propuesta de valor se centra en ElectroLink, un ecosistema inteligente que combina hardware y software para monitorear en tiempo real la infraestructura eléctrica de cadenas de comida rápida, previniendo accidentes laborales y optimizando el consumo energético. Nos posicionamos como un aliado estratégico escalable que ayuda a las franquicias a reducir costos por paradas no programadas y a cumplir rigurosamente con los estándares de seguridad industrial.

### 1.1.2. Perfiles de integrantes del equipo

|   Código   |     Apellidos      |     Nombres     |                                                                                                                                                                         Perfil Académico y Profesional                                                                                                                                                                          | Perfil                                               |
|:----------:|:------------------:|:---------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|------------------------------------------------------|
| u202317450 |   Choy Robles    | Vanessa May Lang | Estudiante de Ingeniería de Software con experiencia en distintos lenguajes de programación, diseño UX/UI y trabajo bajo metodologías ágiles como Scrum. Aporto al equipo una visión orientada tanto a la funcionalidad como a la experiencia del usuario, contribuyendo en el desarrollo y mejora continua del producto. Me caracterizo por mi responsabilidad, cumplimiento de plazos y participación activa en el trabajo colaborativo. | ![vanessa-choy.png](assets/cap1/vanessa-choy.png)         |
| U20231A816 | Valverde Portuguez | Natalia Ximena  | Estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuento con conocimientos de Marketing y estoy interesada en el UX Design y base de datos con sql. Experiencia en trabajos de creación de startups en el ámbito laboral, lo que fortalece mis capacidades tanto en trabajos grupales e individuales para las bases de un proyecto. | ![natalia-valverde.png](assets/cap1/natalia-valverde.png) |  
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El sector de comida rápida en Lima Metropolitana opera bajo un ritmo constante de alta exigencia operacional donde la maquinaria pesada de cocina (freidoras, hornos, congeladores) funciona de forma ininterrumpida. Según reportes técnicos del Organismo Supervisor de la Inversión en Energía y Minería (OSINERGMIN), la falta de sistemas de monitoreo técnico preventivo expone a las cadenas a fallas críticas e incidentes de seguridad de alta severidad.

Esta problemática cobró relevancia pública tras el trágico accidente eléctrico registrado en un local de la cadena McDonald's en el distrito de Pueblo Libre, documentado por medios nacionales como RPP Noticias (2019), donde dos jóvenes trabajadores perdieron la vida a causa de una descarga eléctrica proveniente de una máquina con mantenimiento deficiente. Este evento evidenció vacíos en la supervisión de la infraestructura eléctrica y la urgencia de contar con herramientas tecnológicas que permitan detectar fugas de corriente o anomalías antes de que desencadenen fatalidades.

Para definir de forma estructurada el problema planteado, se aplica la técnica 5 "W"s y 2 "H"s:

**Who (Quiénes):** Operarios de cocina, personal de limpieza y administradores de tiendas de cadenas de comida rápida en Lima Metropolitana.

**What (Qué):** Riesgo elevado de accidentes eléctricos por falta de mantenimiento predictivo, sumado al sobrecosto por consumo energético ineficiente y fallas inesperadas de maquinaria.

**Where (Dónde):** En los locales comerciales y áreas operativas de cocina de cadenas de comida rápida ubicadas en Lima Metropolitana.

**When (Cuándo):** Durante el horario de atención operacional continuo y los procesos de mantenimiento/limpieza diaria de los equipos.

**Why (Por qué):** Ausencia de sistemas automatizados en tiempo real que alerten sobre fluctuaciones, fugas de energía o fallas a tierra, dependiendo actualmente de inspecciones manuales y reactivas.

**How (Cómo):** Se implementa la solución ElectroLink, mediante sensores inteligentes conectables a los tableros y equipos eléctricos, integrados a una plataforma de alertas preventivas y un dashboard analítico para la toma de decisiones.

**How Much (Cuánto):** Pérdidas económicas por multas administrativas, clausuras temporales o definitivas de locales, indemnizaciones legales, reemplazo prematuro de equipos y sobrecostos del 15% al 25% en la facturación eléctrica mensual por ineficiencias de red según el Ministerio de Energía y Minas (MINEM).

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Domain:** Seguridad industrial y gestión de energía basada en IoT para franquicias gastronómicas.  

**Customer Segments:** Gerentes de operaciones y administradores de locales de cadenas de comida rápida en Lima Metropolitana.  

**Pain Points:**
- Imposibilidad de detectar fallas eléctricas no visibles en el equipo de cocina hasta que ocurre un accidente o una avería total.  - Altas planillas de pago por consumo eléctrico sin visibilidad del equipo específico que genera el consumo anómalo.  
- Temor a sanciones e inspecciones de entes fiscalizadores (SUNAFIL, INDECI, OSINERGMIN).

**Gap:** Las soluciones actuales de mantenimiento son manuales, costosas y reactivas, sin integración con alertas preventivas en tiempo real dirigidas al personal en tienda.  

**Vision/Strategy:** Crear la plataforma ElectroLink, combinando sensores IoT de fácil instalación con alertas inmediatas al personal operativo y analítica centralizada para la administración.  

**Initial Segment:** Cadenas de comida rápida en Lima Metropolitana con más de 5 locales operativos.

**Declaración del Problema (Problem Statement):**

El servicio de monitoreo de infraestructura en las cadenas de comida rápida en Lima Metropolitana está pensado para atender fallas eléctricas de forma reactiva. Hemos detectado que la falta de supervisión continua e inteligente impide a los administradores anticiparse a fallas en equipos de cocina y fugas de energía, lo cual expone al personal a riesgos de electrocución y genera gastos innecesarios.

*¿Cómo podríamos proporcionar una herramienta de monitoreo IoT en tiempo real que prevenga accidentes laborales, optimice el consumo energético y garantice la continuidad operacional en las tiendas de comida rápida de Lima Metropolitana?*

#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes** 

- **Creemos que nuestros usuarios necesitan una solución que les permita** monitorear la salud de su red eléctrica y consumo de maquinaria pesada de cocina en tiempo real, previniendo accidentes laborales (fugas a tierra/electrocución) y fallas críticas antes de que ocurran, ya que actualmente solo reaccionan cuando el equipo se avería o inspeccionan manualmente.
  
- **Estas necesidades se pueden resolver mediante** el desarrollo de una plataforma IoT compuesta por sensores integrados a tableros/maquinaria en cocina, alertas audibles/visibles inmediatas en tienda y un dashboard analítico centralizado para la gestión operativa.
  
- **Nuestros clientes iniciales son** gerentes de operaciones, administradores de tienda y Jefes de Seguridad y Salud en el Trabajo (SST) de cadenas y franquicias de comida rápida en Lima Metropolitana con más de 5 locales operativos.
  
- **El valor #1 que los clientes quieren de nuestro servicio es** garantizar la seguridad de su personal operativo evitando fatalidades por descargas eléctricas y previniendo la paralización de la cocina en horas de alto flujo de ventas.
  
- **El cliente también puede obtener estos beneficios adicionales** como reducción en la facturación eléctrica mensual por corrección de ineficiencias de red, cumplimiento normativo ante fiscalizaciones (SUNAFIL, OSINERGMIN) y prolongación de la vida útil de sus equipos industriales.
  
- **Vamos a adquirir la mayoría de los clientes a través de** venta directa B2B a casas matrices de franquicias gastronómicas, alianzas con la Sociedad Nacional de Industrias (sector restaurantes) y demostraciones en vivo del ahorro energético y mitigación de riesgos.
  
- **Haremos dinero a través de** un modelo de suscripción Software as a Service (SaaS) mensual por local monitoreado, sumado al costo de venta/instalación de los kits de sensores IoT.
  
- **Nuestra competencia de mercado serán** empresas tradicionales de mantenimiento eléctrico correctivo/preventivo y sistemas genéricos de gestión de instalaciones (facility management) que no ofrecen alertas IoT en tiempo real focalizadas en cocina.
  
- **Los venceremos debido a** nuestra especializada arquitectura IoT preventiva centrada en la seguridad del trabajador en cocina, alertas inmediatas para personal no técnico y analítica de consumo por máquina en una sola plataforma integrada.
  
- **Nuestro mayor riesgo de producto es** que las cadenas perciban la instalación de los sensores como una interrupción en su operación o duden de la precisión del sistema frente a entornos de grasa/calor extremo en cocina.
  
- **Resolveremos esto a través de** pruebas piloto gratuitas en cocinas de prueba, sensores con protección industrial adecuados para gastronomía y demostraciones cuantificables del retorno de inversión por prevención de fallas.
  
- **Qué otras suposiciones tenemos que, de probarse falsas, pueden causar que nuestro proyecto fracase:**
  - Creemos que los administradores de comida rápida priorizarán la prevención de riesgos y la eficiencia energética sobre la compra de mantenimiento correctivo tradicional.
  - Creemos que los operarios de cocina acatarán las alertas del sistema y detendrán el uso de una máquina si se reporta una anomalía o fuga de corriente.
  - Creemos que la instalación del hardware IoT en los tableros eléctricos no interferirá con la continuidad del servicio del restaurante.

**User Outcomes** 

- **¿Quién será el usuario?**
  - **Usuarios administradores:** Gerentes de Operaciones, Jefes de SST y Administradores de Local de comida rápida.
  - **Usuarios operativos:** Personal de cocina, cajeros y brigadistas de seguridad en tienda.
    
- **¿Dónde encaja nuestro producto en su trabajo o vida?**
  - Para los **administradores**, se integra en la supervisión técnica remota de la red de tiendas, permitiéndoles auditar consumos, planificar mantenimientos y mitigar riesgos legales.
  - Para los **operarios de cocina**, se integra en su rutina diaria de preparación de alimentos como un guardián de seguridad que les notifica en pantalla o mediante alertas locales si un equipo representa un peligro inminente.
    
- **¿Qué problemas busca resolver nuestro producto?**
  - Invisibilidad de fallas invisibles y fugas a tierra en maquinaria pesada de cocina.
  - Alto riesgo de electrocución o accidentes fatales del personal de cocina.
  - Costos excesivos en la factura de luz por equipos ineficientes o sobrecargados.
  - Pérdida de ventas por apagones locales o averías en horas de mayor demanda.

- **¿Cuándo y cómo es usado nuestro producto?**
  - **Cuándo:**
    - De forma ininterrumpida (24/7) en segundo plano para la captura de datos de red.
    - Al instante de detectar un sobrevoltaje, fuga de energía o sobrecalentamiento.
    - Durante las revisiones semanales de gestión de costos de la administración.
  - **Cómo:**
    - A través del Dashboard Web de analítica para la administración centralizada.
    - Mediante notificaciones push, SMS y señalizadores locales en la cocina ante emergencias.
      
- **¿Qué características son importantes?**
  - Monitoreo en tiempo real del voltaje, amperaje y temperatura de equipos clave.
  - Módulo de alerta temprana de fugas de corriente con protocolo de apagado seguro.
  - Dashboard de consumo energético con desglose de costos aproximados por máquina.
  - Historial de eventos y reporte de salud técnica para fiscalizaciones de seguridad.
  
- **¿Cómo debe comportarse y verse nuestro producto?**
  - **Interfaz administrativa:** Visualización de métricas clara, ejecutiva y enfocada en indicadores de riesgo y costo.
  - **Interfaz operativa/tienda:** Interfaz extremadamente simple, con códigos de colores intuitivos (Verde/Amarillo/Rojo) e instructivos de acción rápida ante emergencias.
  - **Comportamiento:** Respuesta inmediata (latencia mínima) en el envío de alertas críticas para prevenir riesgos de electrocución.

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hipótesis 1: Sobre el Monitoreo Preventivo y la Seguridad Laboral.**
  **Creemos que** la implementación de sensores IoT y alertas en tiempo real reduzca los accidentes laborales por descargas eléctricas y prevenga fallas críticas en los equipos de cocina.
  **Sabremos que** estamos en lo cierto **cuando veamos** los siguientes comentarios del mercado: una reducción del 80% en las incidencias por sobrecalentamiento o fugas de corriente y un aumento del 40% en solicitudes de mantenimiento preventivo programado antes de que ocurra una falla crítica en un periodo de 6 meses.
  
- **Hipótesis 2: Sobre la Eficiencia Energética y Reducción de Costos.**
  **Creemos que** proporcionar a los administradores un dashboard analítico con el desglose del consumo eléctrico en tiempo real por cada máquina incrementará la adopción de medidas de ahorro energético.
  **Sabremos que** hemos tenido éxito **cuando veamos** una disminución de al menos un 12% en el costo total de la facturación eléctrica mensual en el 70% de los locales monitoreados durante su primer trimestre de uso.

- **Hipótesis 3: Sobre la Valoración Operativa y Continuidad del Servicio.**
  **Creemos que** los gerentes de operaciones preferirán ElectroLink porque las alertas locales e informes técnicos previenen la paralización imprevista de las cocinas en horas pico de venta.
  **Sabremos que** esto es cierto **cuando veamos** una reducción del 50% en paradas no programadas por fallas eléctricas y una tasa de renovación de suscripciones del 85% por parte de las cadenas de comida rápida tras el periodo de prueba piloto.
  
- **Hipótesis 4: Sobre el Cumplimiento Normativo y Auditorías.**
  **Creemos que** ofrecer un historial descargable de auditorías y eventos de seguridad facilitará el cumplimiento de las normativas de Seguridad y Salud en el Trabajo (SST).
  **Sabremos que** hemos tenido éxito **cuando veamos** que el 90% de los administradores de tienda descarguen y presenten estos reportes en sus inspecciones internas y fiscalizaciones oficiales (SUNAFIL e INDECI).

#### 1.2.2.4. Lean UX Canvas

![Lean-UX-Canvas](assets/cap1/lean-ux-canvas.png)


## 1.3. Segmentos objetivo

**Segmento objetivo #1: Trabajadores del Local (Staff Operativo y de Limpieza)**

- **Descripción:** Jóvenes operarios encargados de la cocina, atención en caja, despacho de pedidos y tareas de mantenimiento/limpieza de turnos en restaurantes de comida rápida en Lima Metropolitana.
  
- **Aspectos demográficos:**
  - Sexo: Masculino y Femenino.
  - Edades: Entre 18 y 28 años (muchos combinan estudios universitarios/técnicos con trabajo a tiempo parcial o completo).
  - Nivel socioeconómico: C y B.
    
- **Aspectos geográficos:** Residentes en Lima Metropolitana, que desempeñan sus labores en locales de comida rápida situados en avenidas principales, patios de comidas en centros comerciales o locales de vía pública.

- **Aspectos psicográficos:**
  - Realizan sus labores en entornos de alta velocidad y presión constante.
  - Poseen pocos o nulos conocimientos técnicos sobre electricidad o mantenimiento industrial.
  - Buscan garantías de seguridad para desempeñar sus labores sin poner en peligro su integridad física al manipular agua, mopas o artefactos de alto voltaje.

- **Necesidades clave:**
  - Conocer de manera clara e inmediata si un equipo es seguro de tocar o limpiar (por ejemplo, antes del baldeado o trapeado de la cocina).
  - Contar con una vía simple de notificación para reportar anomalías o ruidos extraños en los equipos sin descuidar sus tareas de atención.
  - Disponer de entornos laborales seguros donde no corran riesgos de electrocución o quemaduras.

- **Sustento estadístico:** El sector de comida rápida en Lima Metropolitana es uno de los mayores empleadores de jóvenes técnicos y universitarios en el país. De acuerdo con informes y registros de la Superintendencia Nacional de Fiscalización Laboral (SUNAFIL), las deficiencias en las condiciones de seguridad e higiene industrial en cocinas comerciales constituyen uno de los principales motivos de inspección, siendo las fallas mecánicas y descargas eléctricas en zonas operativas los eventos con mayor potencial de lesiones graves o fatalidades.

**Segmento objetivo #2: Manager del Local (Administrador / Jefe de Tienda)**

- **Descripción:** Profesional a cargo de la gestión de la tienda, responsable del cumplimiento de las metas de venta, la seguridad e higiene (SST), el control de costos operativos y el mantenimiento técnico de la infraestructura.
  
- **Aspectos demográficos:**
  - Cargos: Store Manager, Administrador de Local, Supervisor de Turno, Jefe de SST.
  - Edades: Entre 25 y 50 años.
  - Nivel socioeconómico: B y A.

- **Aspectos geográficos:** Encargados de establecimientos de comida rápida en Lima Metropolitana.

- **Aspectos psicográficos:**
  - Orientados al cumplimiento estricto de KPIs de servicio, presupuestos de mantenimiento y normativas legales/laborales (SUNAFIL, OSINERGMIN, INDECI e Inspecciones Municipales).
  - Buscan evitar a toda costa contingencias que afecten la imagen de la marca, clausuras temporales/definitivas o demandas legales por negligencia.
  - Valoran los datos centralizados para coordinar de forma preventiva con los equipos de mantenimiento corporativo.
  
- **Necesidades clave:**
  - Garantizar un ambiente de trabajo 100% seguro contra riesgos eléctricos para todo su personal.
  - Disponer de visibilidad del consumo energético por máquina para controlar costos y reducir la factura de energía.
  - Programar mantenimientos predictivos evitando que las cocinas, congeladoras o freidoras se malogren en horas de alta demanda o generen mermas de insumos.
  
- **Sustento estadístico:** En Lima Metropolitana operan más de 1,200 locales pertenecientes a cadenas y franquicias de comida rápida (hamburgueserías, pollerías, pizzerías). Según reportes del sector retail y gastronómico, los costos asociados a servicios básicos y mantenimiento técnico representan entre el 15% y 20% de los gastos operativos mensuales de cada tienda, donde las ineficiencias de red pueden elevar la facturación hasta un 25% si no se detectan anomalías a tiempo. 

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. Empathy Mapping

### 2.3.4. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)

#### 4.1.2.2. Quality Attribute Scenarios

#### 4.1.2.3. Constraints

### 4.1.3. Architectural Drivers Backlog

### 4.1.4. Architectural Design Decisions

### 4.1.5. Quality Attribute Scenario Refinements

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

### 4.2.2. Candidate Context Discovery

### 4.2.3. Domain Message Flows Modeling

### 4.2.4. Bounded Context Canvases

### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

### 4.3.1. Software Architecture Context Level Diagrams

### 4.3.2. Software Architecture Container Level Diagrams

### 4.3.3. Software Architecture Deployment Diagrams

# Capítulo V: Tactical-Level Software Design

## 5.X. Bounded Context: <Bounded Context Name>

### 5.X.1. Domain Layer

### 5.X.2. Interface Layer

### 5.X.3. Application Layer

### 5.X.4. Infrastructure Layer

### 5.X.6. Bounded Context Software Architecture Component Level Diagrams

### 5.X.7. Bounded Context Software Architecture Code Level Diagrams

#### 5.X.7.1. Bounded Context Domain Layer Class Diagrams

#### 5.X.7.2. Bounded Context Database Design Diagram

# Capítulo VI: Solution UX Design

## 6.1. Style Guidelines

### 6.1.1. General Style Guidelines

### 6.1.2. Web, Mobile & Devices Style Guidelines

## 6.2. Information Architecture

### 6.2.2. Labeling Systems

### 6.2.3. Searching Systems

### 6.2.4. SEO Tags and Meta Tags

### 6.2.5. Navigation Systems

## 6.3. Landing Page UI Design

### 6.3.1. Landing Page Wireframe

### 6.3.2. Landing Page Mock-up

## 6.4. Applications UX/UI Design

### 6.4.1. Applications Wireframes

### 6.4.2. Applications Wireflow Diagrams

### 6.4.2. Applications Mock-ups

### 6.4.3. Applications User Flow Diagrams

## 6.5. Applications Prototyping

# Capítulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

### 7.1.2. Source Code Management

### 7.1.3. Source Code Style Guide & Conventions

### 7.1.4. Software Deployment Configuration

## 7.2. Solution Implementation

### 7.2.X. Sprint n

#### 7.2.X.1. Sprint Planning n

#### 7.2.X.2. Sprint Backlog n

#### 7.2.X.3. Development Evidence for Sprint Review

#### 7.2.X.4. Testing Suite Evidence for Sprint Review

#### 7.2.X.5. Execution Evidence for Sprint Review

#### 7.2.X.6. Services Documentation Evidence for Sprint Review

#### 7.2.X.7. Software Deployment Evidence for Sprint Review

#### 7.2.X.8. Team Collaboration Insights during Sprint

## 7.3. Validation Interviews

### 7.3.1. Diseño de Entrevistas

### 7.3.2. Registro de Entrevistas

### 7.3.3. Evaluaciones según heurísticas

## 7.4. Video About-the-Product

# Conclusiones

# Conclusiones y recomendaciones

# Video About-the-Team

