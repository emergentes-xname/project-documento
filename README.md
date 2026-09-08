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
    <tr><td style="border:1px solid #000; padding:6px 12px; text-align:center;">Vanessa May Lang Choy Robles</td><td style="border:1px solid #000; padding:6px 12px; text-align:center;">U202317450</td></tr>
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

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

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

### To-Be Scenario Map #1: Staff Operativo y de Limpieza (Operario de Cocina / Mantenimiento)
* **Escenario:** Identificación rápida de fallas térmicas/fugas y realización segura de la limpieza de cocina.

| Phases | Fase 1: Inicio de Turno y Monitoreo Preventivo | Fase 2: Detección y Alerta de Anomalía en Equipo | Fase 3: Reporte en 1-Clic vía QR | Fase 4: Limpieza y Mantenimiento Seguro |
| :--- | :--- | :--- | :--- | :--- |
| **Doing** | Revisa el indicador visual local/app de la estación antes de iniciar la operación. | Escucha la alerta sonora/visual del sensor en la freidora que detecta elevación anormal de corriente. | Escanea el código QR pegado en la máquina para enviar un reporte automático a gerencia. | Verifica en la app que la línea está desenergizada antes de proceder al baldeado/trapeado. |
| **Thinking** | *"Es genial saber que no hay riesgos de fuga antes de conectar los hornos."* | *"La alerta me avisó antes de que la máquina sacara chispas o salte la llave general."* | *"No tengo que dejar la cocina sola para ir a buscar al administrador a reportar."* | *"Puedo limpiar tranquilamente con agua sin miedo a una descarga eléctrica."* |
| **Feeling** | Tranquilo, enfocado, respaldado. | Alerta, precavido, informado en tiempo real. | Eficiente, satisfecho, empoderado. | Seguro, protegido, confiado. |

---

### To-Be Scenario Map #2: Manager del Local (Administrador / Jefe de Tienda)
* **Escenario:** Monitoreo del consumo energético por máquina, recepción de alertas tempranas y gestión de mantenimiento preventivo.

| Phases | Fase 1: Revisión del Dashboard Energético | Fase 2: Recepción de Alerta Preventiva IoT | Fase 3: Coordinación y Asignación de Técnico | Fase 4: Auditoría y Cierre de Incidencia |
| :--- | :--- | :--- | :--- | :--- |
| **Doing** | Revisa en el panel web/móvil la métrica de consumo por equipo y el estado de salud de tableros. | Recibe una notificación PUSH en la app sobre un pico de consumo anormal en la congeladora principal. | Asigna una orden de revisión preventiva desde la plataforma al proveedor certificado. | Valida la resolución técnica, revisa la factura digital y descarga el informe para SST/Sunafil. |
| **Thinking** | *"Tengo el control de los costos de energía de todo el local en una sola pantalla."* | *"Menos mal el sensor lo detectó a tiempo; si fallaba en hora punta perdíamos la mercadería."* | *"Es rápido coordinar con un proveedor verificado sin perder tiempo en llamadas."* | *"Tengo todo el historial documentado en caso de una inspección de seguridad laboral."* |
| **Feeling** | En control, seguro, estratégico. | Atento, respaldado por la automatización. | Eficiente, aliviado, productivo. | Cumplidor, satisfecho, tranquilo. |

---

## 3.2. User Stories

| Epic / User Story ID | Título | Descripción | Criterios de Aceptación (Gherkin) | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **EP01** | **Gestión de Landing Page e Información Informativa** | Epic que agrupa la experiencia de navegación pública del sitio web. | N/A | N/A |
| **EP02** | **Monitoreo IoT y Alertas de Seguridad en Tiempo Real** | Epic para la captura de mediciones energéticas y notificaciones del sistema. | N/A | N/A |
| **EP03** | **Gestión de Incidencias y Mantenimiento Preventivo** | Epic que cubre la creación de reportes, asignación y seguimiento de reparaciones. | N/A | N/A |
| **EP04** | **Gestión Multi-local, Analítica de Consumo y Reportes SST** | Epic para la administración de locales, indicadores financieros y auditorías. | N/A | N/A |
| **EP05** | **Servicios Web, Integraciones API e Infraestructura (Technical)** | Epic que cubre el soporte backend, autenticación y comunicación IoT. | N/A | N/A |
| **US01** | Visualización de propuesta de valor en Landing Page | Como visitante, deseo visualizar los beneficios de la solución IoT en el sitio web para comprender cómo previene riesgos eléctricos en restaurantes. | **Given** que un visitante ingresa a la página de inicio, **When** navega por la sección principal, **Then** el sistema muestra la propuesta de valor centrada en seguridad y ahorro energético. | EP01 |
| **US02** | Calculadora de ahorro energético para Managers | Como visitante del segmento Manager, deseo ingresar el número de equipos del local para estimar el ahorro mensual proyectado. | **Given** que el visitante ingresa la cantidad de máquinas y costo actual de luz, **When** presiona el botón calcular, **Then** el sistema procesa el cálculo estimado de ahorro y lo muestra en pantalla. | EP01 |
| **US03** | Formulario de solicitud de demo para cadenas | Como visitante del segmento Manager, deseo solicitar una demostración comercial ingresando mis datos de contacto. | **Given** que el usuario completa los campos obligatorios del formulario, **When** confirma el envío, **Then** el sistema valida los datos y registra la solicitud enviando una confirmación automática. | EP01 |
| **US04** | Sección de testimonios y casos de éxito | Como visitante, deseo consultar testimonios de restaurantes que usan la plataforma para validar su efectividad. | **Given** que el visitante navega a la sección de casos de éxito, **When** selecciona un testimonio, **Then** el sistema despliega el detalle de la métrica de reducción de fallas lograda. | EP01 |
| **US05** | Preguntas frecuentes sobre instalación IoT | Como visitante del segmento Staff Operativo, deseo leer las FAQ sobre seguridad de los sensores para despejar dudas sobre su uso. | **Given** que el visitante accede a la sección FAQ, **When** selecciona la categoría de instalación física, **Then** el sistema despliega las respuestas sobre certificaciones y protección contra agua. | EP01 |
| **US06** | Visualización de planes de suscripción | Como visitante del segmento Manager, deseo comparar los planes de suscripción para elegir el que se adapte a mi número de locales. | **Given** que el visitante consulta la tabla de precios, **When** conmuta entre facturación mensual y anual, **Then** el sistema actualiza los precios y los límites de sensores por plan. | EP01 |
| **US07** | Lectura de parámetros de corriente por sensor IoT | Como Manager del local, deseo visualizar el consumo de corriente en amperios por equipo para detectar sobrecargas en tiempo real. | **Given** que un sensor transmite datos de consumo, **When** el Manager consulta el estado del equipo, **Then** el sistema muestra el valor actual de amperaje y su nivel de normalidad. | EP02 |
| **US08** | Detección automática de fuga a tierra | Como Staff Operativo, deseo que la plataforma identifique fugas a tierra para no tocar equipos en riesgo. | **Given** que el sensor detecta una corriente de fuga superior a 30mA, **When** ocurre el evento, **Then** el sistema cambia el estado del equipo a "Peligro" inmediatamente. | EP02 |
| **US09** | Emisión de alerta PUSH por pico de energía | Como Manager del local, deseo recibir alertas instantáneas en el móvil cuando una máquina supere el umbral máximo de potencia. | **Given** que una freidora supera el límite de potencia configurado, **When** se detecta la anomalía, **Then** el sistema envía una notificación PUSH con el nombre del equipo y el pico registrado. | EP02 |
| **US10** | Indicador visual de seguridad pre-limpieza | Como Staff Operativo, deseo consultar un indicador de semáforo (Verde/Rojo) de la zona de cocina para saber si es seguro iniciar el trapeado. | **Given** que el operario selecciona la zona de cocina, **When** la lectura de fugas es cero, **Then** el sistema muestra el indicador en estado "Seguro / Verde". | EP02 |
| **US11** | Notificación de desconexión de sensor IoT | Como Manager del local, deseo ser notificado si un sensor pierde conectividad para garantizar el monitoreo continuo. | **Given** que un sensor deja de transmitir datos por más de 5 minutos, **When** transcurre la tolerancia, **Then** el sistema genera una alerta de "Dispositivo fuera de línea". | EP02 |
| **US12** | Histórico de lecturas de temperatura en tableros | Como Manager del local, deseo revisar la temperatura histórica de los tableros eléctricos para prevenir sobrecalentamientos. | **Given** que existen lecturas registradas en las últimas 24 horas, **When** el usuario selecciona un tablero, **Then** el sistema despliega el gráfico con la fluctuación térmica. | EP02 |
| **US13** | Reporte de anomalía mediante escaneo de código QR | Como Staff Operativo, deseo escanear el QR pegado en un equipo para reportar una falla eléctrica en menos de 10 segundos. | **Given** que el usuario escanea el código QR de una máquina, **When** selecciona el tipo de anomalía y confirma, **Then** el sistema crea un ticket de incidencia ligado a esa máquina. | EP03 |
| **US14** | Asignación de orden de trabajo a técnico verificado | Como Manager del local, deseo asignar una orden de reparación a un técnico certificado registrado en la red. | **Given** que existe una incidencia reportada, **When** el Manager selecciona un técnico disponible y confirma, **Then** el sistema notifica al técnico y cambia el estado a "Asignado". | EP03 |
| **US15** | Seguimiento en tiempo real de la llegada del técnico | Como Manager del local, deseo visualizar la estimación de tiempo de llegada del técnico para organizar la operación. | **Given** que una orden está en estado "En trayecto", **When** el Manager abre el detalle de la orden, **Then** el sistema despliega el tiempo estimado de arribo. | EP03 |
| **US16** | Registro de diagnóstico y repuestos utilizados | Como Manager del local, deseo que el técnico registre el informe del trabajo realizado para mantener la bitácora técnica. | **Given** que el técnico finaliza la reparación, **When** ingresa el diagnóstico y repuestos consumidos, **Then** el sistema guarda la información y actualiza la hoja de vida del equipo. | EP03 |
| **US17** | Cancelación o reprogramación de cita técnica | Como Manager del local, deseo reprogramar una visita técnica si ocurre un imprevisto en el restaurante. | **Given** una orden agendada, **When** el Manager modifica la fecha con al menos 2 horas de anticipación, **Then** el sistema actualiza la cita y notifica al proveedor. | EP03 |
| **US18** | Evaluación del servicio de mantenimiento prestado | Como Manager del local, deseo calificar al técnico al finalizar la atención para asegurar la calidad de la red. | **Given** que una orden de trabajo ha sido completada, **When** el Manager asigna una puntuación de 1 a 5 estrellas y un comentario, **Then** el sistema registra la calificación. | EP03 |
| **US19** | Cierre de incidencia con firma digital | Como Staff Operativo, deseo validar visualmente el funcionamiento del equipo y firmar la conformidad en la app. | **Given** que el trabajo concluyó, **When** el operario prueba el equipo y registra su firma digital, **Then** el sistema marca la incidencia como "Resuelta con conformidad". | EP03 |
| **US20** | Tablero de control multi-local de consumo | Como Manager del local, deseo consolidar el gasto eléctrico de múltiples locales para comparar eficiencias operativas. | **Given** que el usuario administra más de una sede, **When** accede al dashboard consolidado, **Then** el sistema presenta el comparativo de KWh consumidos por local. | EP04 |
| **US21** | Exportación de informes para auditorías SST / Sunafil | Como Manager del local, deseo exportar el registro de mantenimientos y revisiones eléctricas en formato PDF. | **Given** que el usuario selecciona un rango de fechas, **When** presiona exportar reporte SST, **Then** el sistema genera un archivo PDF normado listo para descarga. | EP04 |
| **US22** | Configuración de presupuestos de energía mensuales | Como Manager del local, deseo establecer un límite de costo energético proyectado para recibir alertas antes de sobrepasarlo. | **Given** que se define un tope presupuestal en Soles, **When** el acumulado mensual alcanza el 80%, **Then** el sistema emite una alerta preventiva de presupuesto. | EP04 |
| **US23** | Programación automática de mantenimientos preventivos | Como Manager del local, deseo programar alertas de mantenimiento según las horas de uso acumuladas de cada motor/máquina. | **Given** que un equipo alcanza 500 horas operativas registradas por el sensor, **When** se cumple el ciclo, **Then** el sistema genera automáticamente una sugerencia de mantenimiento. | EP04 |
| **US24** | Registro y control de activos eléctricos por local | Como Manager del local, deseo dar de alta nuevos equipos asociando su ficha técnica y foto. | **Given** que el usuario completa el formulario de activo, **When** guarda los cambios, **Then** el sistema genera un identificador único y su código QR correspondiente. | EP04 |
| **US25** | Generación de matriz de riesgos eléctricos por zona | Como Manager del local, deseo visualizar un mapa de calor del restaurante que identifique las áreas de mayor vulnerabilidad. | **Given** la acumulación de alertas en los últimos 30 días, **When** el usuario abre la matriz de riesgo, **Then** el sistema colorea en rojo las zonas con mayor índice de picos/fugas. | EP04 |
| **US26** | Autenticación y control de accesos por roles (RBAC) | Como Developer, deseo implementar autenticación basada en tokens JWT para proteger las peticiones de los distintos roles. | **Given** credenciales de usuario válidas, **When** se invoca el endpoint POST /api/v1/auth/login, **Then** el servidor retorna un HTTP 200 OK con un JWT firmado conteniendo las claims de rol. | EP05 |
| **US27** | Endpoint REST para ingesta de telemetría IoT | Como Developer, deseo exponer una API RESTful de alta concurrencia para la recepción de paquetes de datos de los sensores. | **Given** un payload JSON estructurado con datos de voltaje y corriente, **When** el sensor efectúa un POST a /api/v1/telemetry, **Then** la API responde HTTP 201 Created y persiste la lectura. | EP05 |
| **US28** | Procesamiento de mensajería IoT mediante broker MQTT | Como Developer, deseo integrar un broker MQTT para la gestión eficiente de mensajes en tiempo real enviada por hardware. | **Given** un dispositivo IoT publicando en el tópico /sensores/lecturas, **When** se emite un mensaje, **Then** el suscriptor del backend procesa el payload en menos de 200 milisegundos. | EP05 |
| **US29** | API REST de gestión de tickets de soporte | Como Developer, deseo proveer endpoints CRUD para la administración del ciclo de vida de los reportes de avería. | **Given** una solicitud HTTP GET a /api/v1/incidents con un token válido, **When** se procesa la consulta, **Then** la API responde HTTP 200 OK con el listado codificado en JSON. | EP05 |
| **US30** | Servicio de notificaciones Push distribuido | Como Developer, deseo implementar un microservicio de notificaciones Push integrado con Firebase Cloud Messaging (FCM). | **Given** un evento de alerta crítica generado por el motor de reglas, **When** el servicio se ejecuta, **Then** despacha el mensaje a las instancias de la app registradas con HTTP 200 OK. | EP05 |
| **US31** | Mecanismo de reintentos y buffering para desconexión IoT | Como Developer, deseo habilitar un buffer local en la pasarela de sensores para evitar pérdida de datos ante caídas de red. | **Given** que la conexión a internet del local se interrumpe, **When** los sensores generan lecturas, **Then** la pasarela almacena los datos localmente y los retransmite al restaurar el enlace. | EP05 |
| **US32** | Encriptación de datos en tránsito y reposo | Como Developer, deseo aplicar cifrado TLS 1.3 en las comunicaciones y AES-256 en la base de datos para asegurar las métricas. | **Given** que se transmite información de telemetría o credenciales, **When** se inicia el canal de comunicación, **Then** el servidor exige el handshake TLS 1.3 denegando algoritmos obsoletos. | EP05 |
| **US33** | Paginación y filtrado en endpoints de telemetría histórica | Como Developer, deseo implementar paginación basada en cursores para las consultas masivas de lecturas históricas. | **Given** una petición GET a /api/v1/telemetry/history con parámetros limit y cursor, **When** la API consulta la base de datos, **Then** devuelve un dataset optimizado HTTP 200 OK. | EP05 |
| **US34** | API de pasarela de pagos para suscripciones | Como Developer, deseo integrar una pasarela de pagos mediante API REST para procesar el cobro recurrente de la plataforma. | **Given** un intento de cobro mensual a la tarjeta registrada, **When** la API externa procesa la transacción con éxito, **Then** el backend actualiza el estado de la suscripción a "Activa". | EP05 |
| **US35** | Monitor de salud de la plataforma (Health Check Endpoint) | Como Developer, deseo contar con un endpoint de health check para monitorear la disponibilidad de la base de datos y servicios. | **Given** una petición GET a /api/v1/health, **When** todos los componentes dependientes están operativos, **Then** la API responde HTTP 200 OK con el estado "UP" de cada subsistema. | EP05 |

---


## 3.3. Impact Mapping
UXPRESSIA



## 3.4. Product Backlog

| # Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| :---: | :---: | :--- | :--- | :---: |
| **1** | **US01** | Visualización de propuesta de valor en Landing Page | Como visitante, deseo visualizar los beneficios de la solución IoT en el sitio web para comprender cómo previene riesgos eléctricos en restaurantes. | **2** |
| **2** | **US02** | Calculadora de ahorro energético para Managers | Como visitante del segmento Manager, deseo ingresar el número de equipos del local para estimar el ahorro mensual proyectado. | **3** |
| **3** | **US03** | Formulario de solicitud de demo para cadenas | Como visitante del segmento Manager, deseo solicitar una demostración comercial ingresando mis datos de contacto. | **2** |
| **4** | **US08** | Detección automática de fuga a tierra | Como Staff Operativo, deseo que la plataforma identifique fugas a tierra para no tocar equipos en riesgo. | **5** |
| **5** | **US10** | Indicador visual de seguridad pre-limpieza | Como Staff Operativo, deseo consultar un indicador de semáforo (Verde/Rojo) de la zona de cocina para saber si es seguro iniciar el trapeado. | **3** |
| **6** | **US09** | Emisión de alerta PUSH por pico de energía | Como Manager del local, deseo recibir alertas instantáneas en el móvil cuando una máquina supere el umbral máximo de potencia. | **5** |
| **7** | **US13** | Reporte de anomalía mediante escaneo de código QR | Como Staff Operativo, deseo escanear el QR pegado en un equipo para reportar una falla eléctrica en menos de 10 segundos. | **3** |
| **8** | **US07** | Lectura de parámetros de corriente por sensor IoT | Como Manager del local, deseo visualizar el consumo de corriente en amperios por equipo para detectar sobrecargas en tiempo real. | **5** |
| **9** | **US14** | Asignación de orden de trabajo a técnico verificado | Como Manager del local, deseo asignar una orden de reparación a un técnico certificado registrado en la red. | **5** |
| **10** | **US06** | Visualización de planes de suscripción | Como visitante del segmento Manager, deseo comparar los planes de suscripción para elegir el que se adapte a mi número de locales. | **2** |
| **11** | **US04** | Sección de testimonios y casos de éxito | Como visitante, deseo consultar testimonios de restaurantes que usan la plataforma para validar su efectividad. | **1** |
| **12** | **US05** | Preguntas frecuentes sobre instalación IoT | Como visitante del segmento Staff Operativo, deseo leer las FAQ sobre seguridad de los sensores para despejar dudas sobre su uso. | **1** |
| **13** | **US20** | Tablero de control multi-local de consumo | Como Manager del local, deseo consolidar el gasto eléctrico de múltiples locales para comparar eficiencias operativas. | **8** |
| **14** | **US21** | Exportación de informes para auditorías SST / Sunafil | Como Manager del local, deseo exportar el registro de mantenimientos y revisiones eléctricas en formato PDF. | **5** |
| **15** | **US15** | Seguimiento en tiempo real de la llegada del técnico | Como Manager del local, deseo visualizar la estimación de tiempo de llegada del técnico para organizar la operación. | **5** |
| **16** | **US16** | Registro de diagnóstico y repuestos utilizados | Como Manager del local, deseo que el técnico registre el informe del trabajo realizado para mantener la bitácora técnica. | **3** |
| **17** | **US23** | Programación automática de mantenimientos preventivos | Como Manager del local, deseo programar alertas de mantenimiento según las horas de uso acumuladas de cada motor/máquina. | **5** |
| **18** | **US22** | Configuración de presupuestos de energía mensuales | Como Manager del local, deseo establecer un límite de costo energético proyectado para recibir alertas antes de sobrepasarlo. | **3** |
| **19** | **US24** | Registro y control de activos eléctricos por local | Como Manager del local, deseo dar de alta nuevos equipos asociando su ficha técnica y foto. | **3** |
| **20** | **US25** | Generación de matriz de riesgos eléctricos por zona | Como Manager del local, deseo visualizar un mapa de calor del restaurante que identifique las áreas de mayor vulnerabilidad. | **8** |
| **21** | **US11** | Notificación de desconexión de sensor IoT | Como Manager del local, deseo ser notificado si un sensor pierde conectividad para garantizar el monitoreo continuo. | **3** |
| **22** | **US12** | Histórico de lecturas de temperatura en tableros | Como Manager del local, deseo revisar la temperatura histórica de los tableros eléctricos para prevenir sobrecalentamientos. | **3** |
| **23** | **US17** | Cancelación o reprogramación de cita técnica | Como Manager del local, deseo reprogramar una visita técnica si ocurre un imprevisto en el restaurante. | **2** |
| **24** | **US18** | Evaluación del servicio de mantenimiento prestado | Como Manager del local, deseo calificar al técnico al finalizar la atención para asegurar la calidad de la red. | **2** |
| **25** | **US19** | Cierre de incidencia con firma digital | Como Staff Operativo, deseo validar visualmente el funcionamiento del equipo y firmar la conformidad en la app. | **3** |
| **26** | **US26** | Autenticación y control de accesos por roles (RBAC) | Como Developer, deseo implementar autenticación basada en tokens JWT para proteger las peticiones de los distintos roles. | **3** |
| **27** | **US27** | Endpoint REST para ingesta de telemetría IoT | Como Developer, deseo exponer una API RESTful de alta concurrencia para la recepción de paquetes de datos de los sensores. | **5** |
| **28** | **US28** | Procesamiento de mensajería IoT mediante broker MQTT | Como Developer, deseo integrar un broker MQTT para la gestión eficiente de mensajes en tiempo real enviada por hardware. | **8** |
| **29** | **US29** | API REST de gestión de tickets de soporte | Como Developer, deseo proveer endpoints CRUD para la administración del ciclo de vida de los reportes de avería. | **3** |
| **30** | **US30** | Servicio de notificaciones Push distribuido | Como Developer, deseo implementar un microservicio de notificaciones Push integrado con Firebase Cloud Messaging (FCM). | **5** |
| **31** | **US31** | Mecanismo de reintentos y buffering para desconexión IoT | Como Developer, deseo habilitar un buffer local en la pasarela de sensores para evitar pérdida de datos ante caídas de red. | **5** |
| **32** | **US32** | Encriptación de datos en tránsito y reposo | Como Developer, deseo aplicar cifrado TLS 1.3 en las comunicaciones y AES-256 en la base de datos para asegurar las métricas. | **3** |
| **33** | **US33** | Paginación y filtrado en endpoints de telemetría histórica | Como Developer, deseo implementar paginación basada en cursores para las consultas masivas de lecturas históricas. | **3** |
| **34** | **US34** | API de pasarela de pagos para suscripciones | Como Developer, deseo integrar una pasarela de pagos mediante API REST para procesar el cobro recurrente de la plataforma. | **5** |
| **35** | **US35** | Monitor de salud de la plataforma (Health Check Endpoint) | Como Developer, deseo contar con un endpoint de health check para monitorear la disponibilidad de la base de datos y servicios. | **1** |

---

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

