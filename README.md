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

### To-Be Scenario Mapping - Segmento 1: Trabajadores del Local (Staff Operativo y de Limpieza)

| Fases | Fase 1: Inicio de Turno y Verificación | Fase 2: Operación Diaria de Equipos | Fase 3: Detección y Notificación de Anomalía | Fase 4: Protocolo de Limpieza Segura | Fase 5: Cierre de Turno y Reporte |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Doing** | Revisa el panel táctil/señalizador local en cocina antes de encender freidoras y hornos. | Trabaja en la preparación de alimentos observando los indicadores visuales en verde. | Escucha una alerta auditiva local y ve que la pantalla cambia a indicador Rojo "Fuga Detectada". | Consulta el estado del equipo en la pantalla local antes de trapear o baldear la zona de cocina. | Presiona el botón de reporte rápido de fin de turno para confirmar equipos seguros. |
| **Thinking** | "Es genial poder ver con una luz verde si los equipos están seguros antes de empezar a trabajar." | "Puedo concentrarme en sacar los pedidos rápido sin miedo a tocar una máquina en mal estado." | "El sistema me avisa de inmediato que hay peligro; debo alejarme y reportar según el protocolo." | "No debo preocuparme por un shock eléctrico al trapear la cocina porque la pantalla me confirma la seguridad." | "Terminé mi turno tranquilo sabiendo que dejé todo reportado sin trámites complicados." |
| **Feeling** | Confianza y tranquilidad. | Seguridad y concentración. | Alerta pero respaldado por la señalización clara. | Alivio y protección. | Satisfacción y seguridad laboral. |

### To-Be Scenario Mapping - Segmento 2: Manager del Local (Administrador / Jefe de Tienda)

| Fases | Fase 1: Supervisión Inicial del Dashboard | Fase 2: Monitoreo Continuo de Consumo | Fase 3: Gestión Inmediata de Alerta Crítica | Fase 4: Coordinación de Mantenimiento | Fase 5: Auditoría y Cierre Mensual |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Doing** | Abre el Dashboard Web de ElectroLink al inicio de la jornada para verificar el estado de la red. | Revisa la gráfica de consumo en kWh y Soles por máquina para identificar ineficiencias. | Recibe una alerta push/SMS sobre sobrecalentamiento en un congelador clave. | Revisa la recomendación del sistema y agenda revisión técnica en horario fuera de pico. | Exporta el reporte consolidado en PDF para la inspección interna y cumplimiento de SST. |
| **Thinking** | "Tengo visibilidad completa de toda la tienda desde mi laptop sin tener que revisar tablero por tablero." | "Veo claramente qué freidora está consumiendo más energía de lo normal este mes." | "La alerta me llegó a tiempo; puedo actuar antes de que la máquina se queme o cause un accidente." | "Puedo programar la reparación técnica sin interrumpir el flujo de ventas de la hora pico." | "Tengo toda la documentación lista y sustentada para presentar ante fiscalizaciones oficiales." |
| **Feeling** | Control y certidumbre. | Claridad y capacidad de optimización. | Urgencia gestionada con efectividad. | Proactividad y alivio. | Respaldo, cumplimiento y profesionalismo. |

---

## 3.2. User Stories

| Epic / User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **EP01** | **Gestión de Seguridad Operativa en Tienda** | Módulo orientado a proteger la integridad física del staff operativo mediante monitoreo y señalización local. | N/A (Epic) | N/A |
| **US01** | Visualización de Semáforo Operativo | Como Trabajador del Local, deseo ver una señalización de colores (Verde/Amarillo/Rojo) en el panel de cocina, para saber de forma inmediata si un equipo es seguro de manipular o trapear a su alrededor. | **Dado** que el trabajador se encuentra en el área de cocina, **cuando** el sensor registra una fuga de corriente o sobrecalentamiento, **entonces** la pantalla muestra el indicador en Rojo y despliega el mensaje "NO TOCAR". | EP01 |
| **US02** | Botón de Reporte Rápido de Falla | Como Trabajador del Local, deseo presionar un botón de reporte en la pantalla local, para notificar al Manager sobre anomalías o ruidos en una máquina sin pausar la atención al cliente. | **Dado** que un equipo emite un ruido inusual, **cuando** el operario presiona "Reportar Falla", **entonces** el sistema envía una alerta inmediata al Dashboard del Manager con la máquina y hora registrada. | EP01 |
| **US03** | Alarma Sonora de Emergencia | Como Trabajador del Local, deseo escuchar una alerta auditiva local, para evacuar o alejarme de inmediato del equipo de cocina si ocurre una fuga a tierra crítica. | **Dado** que ocurre una fuga de corriente crítica, **cuando** el sensor la detecta en tiempo real, **entonces** el sistema activa la bocina local y parpadea la pantalla en rojo con el instructivo de seguridad. | EP01 |
| **US04** | Confirmación de Equipo Apagado | Como Trabajador del Local, deseo consultar en pantalla la confirmación de desenergización, para realizar el baldeado o trapeado del piso con total seguridad. | **Dado** que se va a iniciar la limpieza, **cuando** el trabajador selecciona "Verificar Limpieza", **entonces** la pantalla confirma que el circuito eléctrico del área está aislado y es seguro trapear. | EP01 |
| **US05** | Consulta de Protocolo de Apagado | Como Trabajador del Local, deseo visualizar los pasos de apagado seguro en pantalla, para cortar la energía de una máquina en emergencia sin correr riesgos. | **Dado** que se activa una alerta de peligro, **cuando** el trabajador mira la pantalla local, **entonces** el sistema lista 3 pasos simples numerados para ejecutar el corte de energía seguro. | EP01 |
| **US06** | Registro de Incidencia de Turno | Como Trabajador del Local, deseo confirmar la entrega de turno mediante un check rápido, para dejar constancia del estado de los equipos al siguiente grupo de trabajo. | **Dado** que finaliza el turno, **cuando** el operario presiona "Cerrar Turno Operativo", **entonces** el sistema registra el estado de las máquinas y envía un resumen al Manager. | EP01 |
| **US07** | Guía Rápida de Primeros Auxilios Eléctricos | Como Trabajador del Local, deseo consultar un botón de ayuda rápida en pantalla, para conocer las acciones inmediatas en caso de contacto accidental de un compañero con corriente. | **Dado** que ocurre un incidente, **cuando** el trabajador presiona "Ayuda / Emergencia", **entonces** la pantalla despliega gráficos con las instrucciones de aislamiento y socorro. | EP01 |
| **US08** | Alerta Visual de Humedad en Zona de Cocina | Como Trabajador del Local, deseo ver una advertencia en la interfaz cuando se detecte humedad excesiva cerca a tableros, para evitar conectar equipos en superficies mojadas. | **Dado** que el sensor ambiental detecta agua cerca al tablero, **cuando** el operario se aproxima, **entonces** el panel muestra una advertencia amarilla de "Superficie Húmeda". | EP01 |
| **EP02** | **Monitoreo Técnico y Alertas para la Administración** | Módulo central para la gestión preventiva, supervisión de red y notificaciones ejecutivas. | N/A (Epic) | N/A |
| **US09** | Dashboard de Red en Tiempo Real | Como Manager del Local, deseo visualizar un Dashboard centralizado con el estado de la red eléctrica, para identificar qué equipos presentan ineficiencias o riesgos antes de una falla en hora pico. | **Dado** que el Manager ingresa a la plataforma web, **cuando** carga la vista principal, **entonces** el sistema despliega el estado de salud técnica, voltaje y temperatura de todos los equipos del local. | EP02 |
| **US10** | Alertas Push y SMS de Emergencia | Como Manager del Local, deseo recibir alertas automáticas por SMS y notificación Push, para tomar acciones inmediatas ante sobrevoltajes o fugas de energía. | **Dado** que se sobrepasa el límite seguro de amperaje en un equipo, **cuando** el sensor registra el evento, **entonces** el sistema envía un mensaje SMS y notificación al teléfono del Manager. | EP02 |
| **US11** | Configuración de Umbrales Térmicos | Como Manager del Local, deseo personalizar los límites tolerables de temperatura y amperaje por equipo, para adaptar las alertas a la maquinaria antigua o nueva. | **Dado** que el Manager edita la ficha de una freidora, **cuando** ingresa los límites máximos permitidos y guarda, **entonces** el sistema actualiza la lógica de disparo de alertas para dicho equipo. | EP02 |
| **US12** | Historial Filtrable de Alertas | Como Manager del Local, deseo filtrar las alertas por fecha, nivel de severidad y equipo, para analizar los patrones de fallas más recurrentes en la cocina. | **Dado** que el Manager accede al historial de eventos, **cuando** selecciona el filtro "Severidad Alta" y "Últimos 30 días", **entonces** el sistema muestra únicamente las alertas críticas registradas en ese periodo. | EP02 |
| **US13** | Asignación de Tareas de Revisión | Como Manager del Local, deseo asignar una alerta no crítica al técnico de mantenimiento, para programar su revisión antes de que se convierta en una avería total. | **Dado** que se genera una alerta amarilla, **cuando** el Manager selecciona "Asignar a Técnico", **entonces** el sistema notifica al técnico designado con el detalle del equipo y nivel de urgencia. | EP02 |
| **US14** | Estado de Conectividad de Sensores | Como Manager del Local, deseo ver un indicador de estado de conexión de cada sensor IoT, para asegurar que toda la cocina esté siendo monitoreada sin puntos ciegos. | **Dado** que un sensor pierde conexión a la red local, **entonces** el Dashboard muestra el icono del equipo en gris e informa "Sensor Desconectado". | EP02 |
| **US15** | Panel de Mantenimiento Preventivo | Como Manager del Local, deseo recibir recomendaciones automáticas de mantenimiento predictivo, para programar revisiones sin congelar la cocina en horas pico. | **Dado** que el sistema detecta desgaste en las resistencias de un horno, **cuando** la probabilidad de falla es alta, **entonces** sugiere agendar mantenimiento en las próximas 48 horas. | EP02 |
| **US16** | Registro de Turnos del Personal Operativo | Como Manager del Local, deseo visualizar qué trabajador estuvo a cargo de la cocina durante una alerta, para realizar el seguimiento operativo correspondiente. | **Dado** que se registra una falla operativa, **cuando** el Manager consulta el detalle del evento, **entonces** el sistema muestra el turno y nombre del trabajador responsable en ese horario. | EP02 |
| **EP03** | **Gestión Energética y Costos Operativos** | Módulo para la visualización, desglose y optimización del consumo eléctrico en el local. | N/A (Epic) | N/A |
| **US17** | Desglose de Consumo por Equipo | Como Manager del Local, deseo consultar el consumo eléctrico en kWh y Soles (PEN) desglosado por máquina, para identificar cuáles elevan la factura mensual. | **Dado** que el Manager entra al módulo de energía, **cuando** selecciona un rango de fechas, **entonces** el sistema muestra una gráfica interactiva con el gasto en PEN por cada equipo de cocina. | EP03 |
| **US18** | Comparativa de Consumo Histórico | Como Manager del Local, deseo comparar el gasto energético del mes actual con el del mes anterior, para evaluar si las medidas de ahorro implementadas funcionaron. | **Dado** que el Manager selecciona "Comparar Periodos", **cuando** elige "Mes Actual vs Mes Anterior", **entonces** el sistema muestra la variación porcentual de consumo y costo. | EP03 |
| **US19** | Detección de Consumo Anómalo Fuera de Horario | Como Manager del Local, deseo recibir un reporte de consumos registrados durante la madrugada o local cerrado, para detectar máquinas dejadas encendidas por error. | **Dado** que la tienda está fuera de horario comercial, **cuando** un equipo registra un consumo superior al modo de espera (standby), **entonces** el sistema envía una alerta de "Consumo Inusual Fuera de Horario". | EP03 |
| **US20** | Proyección de Factura Eléctrica | Como Manager del Local, deseo ver una proyección del costo total de la factura eléctrica al cierre del mes, para ajustar los presupuestos operacionales del local. | **Dado** que transcurren los primeros 15 días del mes, **cuando** el Manager consulta la proyección, **entonces** el sistema estima el monto total final en PEN aplicando la tarifa eléctrica vigente. | EP03 |
| **US21** | Exportación de Reportes de Eficiencia | Como Manager del Local, deseo descargar en Excel/PDF el reporte de consumo energético, para presentarlo en la reunión de revisión de costos con la gerencia general. | **Dado** que el Manager está en la vista de reportes, **cuando** hace clic en "Exportar Excel", **entonces** se descarga la hoja de cálculo con el desglose diario por circuito y equipo. | EP03 |
| **US22** | Metas de Ahorro Energético por Tienda | Como Manager del Local, deseo fijar un tope de consumo mensual en kWh, para recibir alertas cuando la tienda esté próxima a superar el presupuesto energético. | **Dado** que el Manager ingresa un límite de 3000 kWh, **cuando** el consumo acumulado alcanza el 85%, **entonces** el sistema envía una notificación de advertencia de presupuesto. | EP03 |
| **EP04** | **Cumplimiento Normativo y Reportes de Seguridad** | Módulo para la generación de evidencias técnicas exigidas por entes reguladores (SUNAFIL, OSINERGMIN, INDECI). | N/A (Epic) | N/A |
| **US23** | Generación de Reporte SST en PDF | Como Manager del Local, deseo descargar un PDF del historial de eventos de seguridad eléctrica, para presentar evidencias formales ante inspecciones de SUNAFIL o INDECI. | **Dado** que se realiza una auditoría oficial, **cuando** el Manager presiona "Exportar Reporte SST", **entonces** el sistema genera un documento PDF con registro cronológico de alertas resueltas. | EP04 |
| **US24** | Checklist Digital de Inspección Eléctrica | Como Manager del Local, deseo completar un checklist digital semanal de la red, para registrar el cumplimiento de los estándares de seguridad industrial. | **Dado** que inicia la semana, **cuando** el Manager completa las preguntas del checklist en la plataforma, **entonces** el sistema guarda el registro asociado a la fecha y usuario. | EP04 |
| **US25** | Registro de Mantenimientos Realizados | Como Manager del Local, deseo adjuntar la constancia de mantenimiento emitida por el técnico, para mantener la trazabilidad de reparaciones ante auditorías. | **Dado** que concluye una reparación, **cuando** el Manager sube el comprobante escaneado a la ficha del equipo, **entonces** el sistema actualiza la fecha del último mantenimiento efectuado. | EP04 |
| **US26** | Certificado de Salud Técnica del Local | Como Manager del Local, deseo consultar el nivel de cumplimiento normativo del local (0% a 100%), para corregir observaciones antes de una inspección municipal. | **Dado** que el Manager revisa el módulo de cumplimiento, **cuando** carga la página, **entonces** el sistema muestra el porcentaje global de salud técnica de la infraestructura del local. | EP04 |
| **US27** | Recordatorio de Renovación de Mantenimiento | Como Manager del Local, deseo recibir alertas cuando venza el periodo de garantía o mantenimiento de un equipo, para evitar operar con maquinaria sin certificación. | **Dado** que faltan 7 días para el vencimiento de revisión de una congeladora, **cuando** el Manager ingresa a la app, **entonces** el sistema muestra una notificación en el panel de tareas. | EP04 |
| **EP05** | **Configuración de Perfiles y Control de Acceso** | Módulo administrativo para la personalización de usuarios y acceso a datos del local. | N/A (Epic) | N/A |
| **US28** | Creación de Cuentas para Trabajadores | Como Manager del Local, deseo registrar las cuentas de los operarios de cocina en el sistema, para que puedan identificarse al iniciar sus turnos en el panel local. | **Dado** que se contrata un nuevo trabajador, **cuando** el Manager ingresa su nombre y DNI, **entonces** el sistema genera un código PIN de 4 dígitos para su acceso rápido en tienda. | EP05 |
| **US29** | Configuración de Notificaciones Preferidas | Como Manager del Local, deseo elegir si recibir alertas por WhatsApp, SMS o correo, para ajustar los canales de comunicación según mi disponibilidad de señal. | **Dado** que el Manager entra a su perfil, **cuando** selecciona "WhatsApp" como canal primario, **entonces** el sistema envía las alertas críticas prioritariamente a su número registrado. | EP05 |
| **US30** | Autenticación Segura en Plataforma Web | Como Manager del Local, deseo iniciar sesión con correo y contraseña encriptada, para proteger la información financiera y operativa de mi local. | **Dado** que el Manager ingresa sus credenciales válidas en la página de login, **cuando** presiona "Ingresar", **entonces** el sistema le otorga acceso al Dashboard administrativo. | EP05 |
| **US31** | Recuperación de Contraseña de Administrador | Como Manager del Local, deseo solicitar la restauración de mi clave por correo, para recuperar el acceso a la plataforma si la olvido. | **Dado** que el Manager presiona "Olvidé mi contraseña", **cuando** ingresa su correo corporativo, **entonces** el sistema envía un enlace seguro de restablecimiento con validez de 15 minutos. | EP05 |
| **US32** | Personalización de Mapa de Cocina | Como Manager del Local, deseo organizar visualmente los iconos de los equipos según la distribución real de mi cocina, para ubicar rápidamente la máquina en falla. | **Dado** que el Manager está en la vista de configuración, **cuando** arrastra el icono "Freidora 1" a la zona izquierda, **entonces** la plataforma guarda el diseño espacial del local. | EP05 |
| **US33** | Registro de Firma Digital de Conformidad | Como Manager del Local, deseo registrar mi firma digital en la plataforma, para validar automáticamente los reportes descargables de inspección SST. | **Dado** que el Manager adjunta su firma en formato imagen, **cuando** se genera un reporte PDF, **entonces** el sistema incluye la firma al pie del documento normativo. | EP05 |
| **US34** | Visualización de Logs de Actividad en Tienda | Como Manager del Local, deseo revisar la bitácora de acciones realizadas en el panel local, para verificar quién atendió una alerta o registró un reporte rápido. | **Dado** que el Manager consulta la sección de auditoría, **cuando** filtra por fecha, **entonces** el sistema lista la hora, usuario y acción ejecutada en el panel de la cocina. | EP05 |
| **US35** | Bloqueo Temporal de Teclado Local por Limpieza | Como Trabajador del Local, deseo activar la función "Modo Limpieza" en el panel táctil, para trapear la pantalla sin accionar botones por error. | **Dado** que el trabajador va a trapear el panel, **cuando** mantiene presionado el botón "Limpieza" por 3 segundos, **entonces** la pantalla inhabilita los toques táctiles durante 30 segundos. | EP01 |

---

## 3.3. Impact Mapping

[ImpactMapping](assets/cap3/ImpactMapping.png) 


## 3.4. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
| :---: | :---: | :--- | :--- | :---: |
| **1** | **US01** | Visualización de Semáforo Operativo | Como Trabajador del Local, deseo ver una señalización de colores (Verde/Amarillo/Rojo) en el panel de cocina, para saber de forma inmediata si un equipo es seguro de manipular o trapear a su alrededor. | 3 |
| **2** | **US03** | Alarma Sonora de Emergencia | Como Trabajador del Local, deseo escuchar una alerta auditiva local, para evacuar o alejarme de inmediato del equipo de cocina si ocurre una fuga a tierra crítica. | 3 |
| **3** | **US10** | Alertas Push y SMS de Emergencia | Como Manager del Local, deseo recibir alertas automáticas por SMS y notificación Push, para tomar acciones inmediatas ante sobrevoltajes o fugas de energía. | 3 |
| **4** | **US30** | Autenticación Segura en Plataforma Web | Como Manager del Local, deseo iniciar sesión con correo y contraseña encriptada, para proteger la información financiera y operativa de mi local. | 3 |
| **5** | **US09** | Dashboard de Red en Tiempo Real | Como Manager del Local, deseo visualizar un Dashboard centralizado con el estado de la red eléctrica, para identificar qué equipos presentan ineficiencias o riesgos antes de una falla en hora pico. | 5 |
| **6** | **US02** | Botón de Reporte Rápido de Falla | Como Trabajador del Local, deseo presionar un botón de reporte en la pantalla local, para notificar al Manager sobre anomalías o ruidos en una máquina sin pausar la atención al cliente. | 2 |
| **7** | **US04** | Confirmación de Equipo Apagado | Como Trabajador del Local, deseo consultar en pantalla la confirmación de desenergización, para realizar el baldeado o trapeado del piso con total seguridad. | 2 |
| **8** | **US05** | Consulta de Protocolo de Apagado | Como Trabajador del Local, deseo visualizar los pasos de apagado seguro en pantalla, para cortar la energía de una máquina en emergencia sin correr riesgos. | 2 |
| **9** | **US17** | Desglose de Consumo por Equipo | Como Manager del Local, deseo consultar el consumo eléctrico en kWh y Soles (PEN) desglosado por máquina, para identificar cuáles elevan la factura mensual. | 8 |
| **10** | **US11** | Configuración de Umbrales Térmicos | Como Manager del Local, deseo personalizar los límites tolerables de temperatura y amperaje por equipo, para adaptar las alertas a la maquinaria antigua o nueva. | 3 |
| **11** | **US14** | Estado de Conectividad de Sensores | Como Manager del Local, deseo ver un indicador de estado de conexión de cada sensor IoT, para asegurar que toda la cocina esté siendo monitoreada sin puntos ciegos. | 2 |
| **12** | **US23** | Generación de Reporte SST en PDF | Como Manager del Local, deseo descargar un PDF del historial de eventos de seguridad eléctrica, para presentar evidencias formales ante inspecciones de SUNAFIL o INDECI. | 5 |
| **13** | **US15** | Panel de Mantenimiento Preventivo | Como Manager del Local, deseo recibir recomendaciones automáticas de mantenimiento predictivo, para programar revisiones sin congelar la cocina en horas pico. | 8 |
| **14** | **US08** | Alerta Visual de Humedad en Zona de Cocina | Como Trabajador del Local, deseo ver una advertencia en la interfaz cuando se detecte humedad excesiva cerca a tableros, para evitar conectar equipos en superficies mojadas. | 2 |
| **15** | **US28** | Creación de Cuentas para Trabajadores | Como Manager del Local, deseo registrar las cuentas de los operarios de cocina en el sistema, para que puedan identificarse al iniciar sus turnos en el panel local. | 3 |
| **16** | **US12** | Historial Filtrable de Alertas | Como Manager del Local, deseo filtrar las alertas por fecha, nivel de severidad y equipo, para analizar los patrones de fallas más recurrentes en la cocina. | 3 |
| **17** | **US19** | Detección de Consumo Anómalo Fuera de Horario | Como Manager del Local, deseo recibir un reporte de consumos registrados durante la madrugada o local cerrado, para detectar máquinas dejadas encendidas por error. | 3 |
| **18** | **US18** | Comparativa de Consumo Histórico | Como Manager del Local, deseo comparar el gasto energético del mes actual con el del mes anterior, para evaluar si las medidas de ahorro implementadas funcionaron. | 5 |
| **19** | **US20** | Proyección de Factura Eléctrica | Como Manager del Local, deseo ver una proyección del costo total de la factura eléctrica al cierre del mes, para ajustar los presupuestos operacionales del local. | 5 |
| **20** | **US13** | Asignación de Tareas de Revisión | Como Manager del Local, deseo asignar una alerta no crítica al técnico de mantenimiento, para programar su revisión antes de que se convierta en una avería total. | 3 |
| **21** | **US06** | Registro de Incidencia de Turno | Como Trabajador del Local, deseo confirmar la entrega de turno mediante un check rápido, para dejar constancia del estado de los equipos al siguiente grupo de trabajo. | 2 |
| **22** | **US21** | Exportación de Reportes de Eficiencia | Como Manager del Local, deseo descargar en Excel/PDF el reporte de consumo energético, para presentarlo en la reunión de revisión de costos con la gerencia general. | 3 |
| **23** | **US24** | Checklist Digital de Inspección Eléctrica | Como Manager del Local, deseo completar un checklist digital semanal de la red, para registrar el cumplimiento de los estándares de seguridad industrial. | 3 |
| **24** | **US25** | Registro de Mantenimientos Realizados | Como Manager del Local, deseo adjuntar la constancia de mantenimiento emitida por el técnico, para mantener la trazabilidad de reparaciones ante auditorías. | 2 |
| **25** | **US26** | Certificado de Salud Técnica del Local | Como Manager del Local, deseo consultar el nivel de cumplimiento normativo del local (0% a 100%), para corregir observaciones antes de una inspección municipal. | 3 |
| **26** | **US07** | Guía Rápida de Primeros Auxilios Eléctricos | Como Trabajador del Local, deseo consultar un botón de ayuda rápida en pantalla, para conocer las acciones inmediatas en caso de contacto accidental de un compañero con corriente. | 2 |
| **27** | **US22** | Metas de Ahorro Energético por Tienda | Como Manager del Local, deseo fijar un tope de consumo mensual en kWh, para recibir alertas cuando la tienda esté próxima a superar el presupuesto energético. | 3 |
| **28** | **US27** | Recordatorio de Renovación de Mantenimiento | Como Manager del Local, deseo recibir alertas cuando venza el periodo de garantía o mantenimiento de un equipo, para evitar operar con maquinaria sin certificación. | 2 |
| **29** | **US29** | Configuración de Notificaciones Preferidas | Como Manager del Local, deseo elegir si recibir alertas por WhatsApp, SMS o correo, para ajustar los canales de comunicación según mi disponibilidad de señal. | 2 |
| **30** | **US31** | Recuperación de Contraseña de Administrador | Como Manager del Local, deseo solicitar la restauración de mi clave por correo, para recuperar el acceso a la plataforma si la olvido. | 2 |
| **31** | **US32** | Personalización de Mapa de Cocina | Como Manager del Local, deseo organizar visualmente los iconos de los equipos según la distribución real de mi cocina, para ubicar rápidamente la máquina en falla. | 5 |
| **32** | **US33** | Registro de Firma Digital de Conformidad | Como Manager del Local, deseo registrar mi firma digital en la plataforma, para validar automáticamente los reportes descargables de inspección SST. | 2 |
| **33** | **US34** | Visualización de Logs de Actividad en Tienda | Como Manager del Local, deseo revisar la bitácora de acciones realizadas en el panel local, para verificar quién atendió una alerta o registró un reporte rápido. | 3 |
| **34** | **US16** | Registro de Turnos del Personal Operativo | Como Manager del Local, deseo visualizar qué trabajador estuvo a cargo de la cocina durante una alerta, para realizar el seguimiento operativo correspondiente. | 2 |
| **35** | **US35** | Bloqueo Temporal de Teclado Local por Limpieza | Como Trabajador del Local, deseo activar la función "Modo Limpieza" en el panel táctil, para trapear la pantalla sin accionar botones por error. | 1 |

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

