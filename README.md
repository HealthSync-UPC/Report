<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2025-20</strong><br>
    <strong>Desarrollo de Soluciones IoT - 3428</strong><br>
    <strong>Profesor: Leon Baca, Marco Antonio</strong><br>
</p>

</p>

<p align="center">
    <strong>Startup: HealthSync</strong><br>
    <strong>Producto: MediTrack</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Ayquipa Ubaldo, Abraham Israel</td>
            <td>U202218475</td>
        </tr>
        <tr>
            <td>Cruz Ticona, Aaron Alejandro</td>
            <td>U202213502</td>
        </tr>
        <tr>
            <td>Durand Vera, Gianfranco Angel</td>
            <td>U20201f640</td>
        </tr>
        <tr>
            <td>Luza Carhuamaca, Jose Adrian</td>
            <td>U202213404</td>
        </tr>
        <tr>
            <td>Ticona Panduro, Estrella del Pilar</td>
            <td>U202210659</td>
        </tr>
    </table>
</div>


<b><center>Septiembre, 2025</center></b>

<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificaciones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>



# Project Report Collaboration Insights

<br><br>

# Contenido
[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capitulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
- [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Product Backlog](#33-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
        - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
        - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
        - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
        - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
        - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
        - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
        - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context--bounded-context-name)
        - [4.2.X.1. Domain Layer](#42x1-domain-layer)
        - [4.2.X.2. Interface Layer](#42x2-interface-layer)
        - [4.2.X.3. Application Layer](#42x3-application-layer)
        - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
        - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
        - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)

[Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems](#521-organization-systems)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Applications Wireframes](#541-applications-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    - [5.4.2. Applications Mock-ups](#542-applications-mock-ups)
    - [5.4.3. Applications User Flow Diagrams](#543-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

[Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.X. Sprint n](#62x-sprint-n)
    - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
    - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
    - [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
    - [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
    - [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
    - [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
    - [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
    - [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
    - [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

[Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome  
ABET – EAC - Student Outcome 5

**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
  <tbody>
    <tr>
      <td><b>Trabaja en equipo para proporcionar liderazgo en forma conjunta.</b></td>
      <td>
        <p><b>Abraham Ayquipa Ubaldo</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Aaron Cruz Ticona</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Gianfranco Durand Vera</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Jose Luza Carhuamaca</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Estrella Ticona Panduro</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
      </td>
      <td>
        <p><b>TB1:</b> [Conclusiones]</p>
        <p><b>TP1:</b> [Conclusiones]</p>
        <p><b>TB2:</b> [Conclusiones]</p>
        <p><b>TF:</b> [Conclusiones]</p>
      </td>
    </tr>
    <tr>
      <td><b>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</b></td>
      <td>
        <p><b>Abraham Ayquipa Ubaldo</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Aaron Cruz Ticona</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Gianfranco Durand Vera</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Jose Luza Carhuamaca</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
        <br>
        <p><b>Estrella Ticona Panduro</b></p>
        <p><b>TB1:</b> [Acciones]</p>
        <p><b>TP1:</b> [Acciones]</p>
        <p><b>TB2:</b> [Acciones]</p>
        <p><b>TF:</b> [Acciones]</p>
      </td>
      <td>
        <p><b>TB1:</b> [Conclusiones]</p>
        <p><b>TP1:</b> [Conclusiones]</p>
        <p><b>TB2:</b> [Conclusiones]</p>
        <p><b>TF:</b> [Conclusiones]</p>
      </td>
    </tr>
  </tbody>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b></b></p>
      <p></p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b></b></p>
      <p></p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b></b></p>
      <p></p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b></b></p>
      <p></p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b></b></p>
      <p></p>
    </td>
  </tr>
</table>

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
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories

<!-- ========================================= -->
<!-- Epic 1: Autenticación y Gestión de Usuarios -->
<!-- ========================================= -->

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Registro de institución (hospital/clinica)</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">6h</span></th>
    <th>ID<br><span style="font-weight: 200">HU001</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> administrador institucional,<br>
        <strong>Quiero</strong> registrar mi organización,<br>
        <strong>Para</strong> habilitar espacios y usuarios propios en la plataforma
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Registro institucional exitoso</strong><br>
        <strong>Dado</strong> que proporciono datos válidos de la institución,<br>
        <strong>Cuando</strong> envío el formulario,<br>
        <strong>Entonces</strong> se crea la cuenta y recibo un correo de confirmación.<br><br>
        <strong>Escenario 2: Datos incompletos o inválidos</strong><br>
        <strong>Dado</strong> que dejo campos obligatorios vacíos o erróneos,<br>
        <strong>Cuando</strong> intento registrar la institución,<br>
        <strong>Entonces</strong> el sistema muestra mensajes de error específicos.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Registro de usuario</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU002</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> nuevo usuario,<br>
        <strong>Quiero</strong> registrarme con mis datos personales y correo electrónico,<br>
        <strong>Para</strong> acceder a la plataforma
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Registro exitoso</strong><br>
        <strong>Dado</strong> que el usuario quiere unirse a la plataforma,<br>
        <strong>Cuando</strong> complete el formulario con datos válidos,<br>
        <strong>Entonces</strong> se crea su cuenta y recibe un correo de verificación.<br><br>
        <strong>Escenario 2: Correo ya registrado</strong><br>
        <strong>Dado</strong> que el correo ya existe en el sistema,<br>
        <strong>Cuando</strong> intento registrarme,<br>
        <strong>Entonces</strong> el sistema muestra un mensaje indicando que el correo ya está en uso.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Inicio de sesión</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU003</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> usuario registrado,<br>
        <strong>Quiero</strong> iniciar sesión con mi correo y contraseña,<br>
        <strong>Para</strong> acceder a mi cuenta de forma segura
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Inicio exitoso</strong><br>
        <strong>Dado</strong> que tengo credenciales correctas,<br>
        <strong>Cuando</strong> las ingreso y presiono “Iniciar sesión”,<br>
        <strong>Entonces</strong> accedo a mi dashboard.<br><br>
        <strong>Escenario 2: Inicio fallido</strong><br>
        <strong>Dado</strong> que ingreso credenciales incorrectas,<br>
        <strong>Cuando</strong> intento iniciar sesión,<br>
        <strong>Entonces</strong> recibo el mensaje “usuario o contraseña inválida”.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Cerrar sesión</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">2h</span></th>
    <th>ID<br><span style="font-weight: 200">HU004</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> usuario autenticado,<br>
        <strong>Quiero</strong> finalizar mi sesión,<br>
        <strong>Para</strong> proteger el acceso a mis datos
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Cierre de sesión exitoso</strong><br>
        <strong>Dado</strong> que tengo una sesión activa,<br>
        <strong>Cuando</strong> selecciono "Cerrar sesión",<br>
        <strong>Entonces</strong> el sistema finaliza la sesión y redirige al login.<br><br>
        <strong>Escenario 2: Sin sesión activa</strong><br>
        <strong>Dado</strong> que no tengo sesión,<br>
        <strong>Cuando</strong> accedo a la URL de cerrar sesión,<br>
        <strong>Entonces</strong> el sistema muestra la pantalla de inicio de sesión.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Recuperación de contraseña</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">3h</span></th>
    <th>ID<br><span style="font-weight: 200">HU005</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> usuario registrado,<br>
        <strong>Quiero</strong> recuperar mi contraseña mediante mi correo,<br>
        <strong>Para</strong> restablecer el acceso en caso de olvido
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Solicitud de recuperación</strong><br>
        <strong>Dado</strong> que olvidé mi contraseña,<br>
        <strong>Cuando</strong> ingreso mi correo en “Recuperar contraseña”,<br>
        <strong>Entonces</strong> recibo un enlace de restablecimiento.<br><br>
        <strong>Escenario 2: Correo inexistente</strong><br>
        <strong>Dado</strong> que ingreso un correo no registrado,<br>
        <strong>Cuando</strong> solicito recuperación,<br>
        <strong>Entonces</strong> el sistema informa que no existe una cuenta asociada.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Cambio de contraseña</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">2h</span></th>
    <th>ID<br><span style="font-weight: 200">HU006</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> usuario autenticado,<br>
        <strong>Quiero</strong> cambiar mi contraseña desde mi perfil,<br>
        <strong>Para</strong> mantener mi cuenta segura
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Cambio exitoso</strong><br>
        <strong>Dado</strong> que accedo a mi perfil,<br>
        <strong>Cuando</strong> introduzco mi contraseña actual y la nueva válida,<br>
        <strong>Entonces</strong> el sistema actualiza la contraseña y confirma el cambio.<br><br>
        <strong>Escenario 2: Error de validación</strong><br>
        <strong>Dado</strong> que ingreso la contraseña actual incorrecta,<br>
        <strong>Cuando</strong> intento guardar,<br>
        <strong>Entonces</strong> el sistema muestra un mensaje de error.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Gestión de perfil de usuario</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">3h</span></th>
    <th>ID<br><span style="font-weight: 200">HU007</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> usuario autenticado,<br>
        <strong>Quiero</strong> ver y editar mi información de perfil,<br>
        <strong>Para</strong> mantener mis datos actualizados
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Visualización de perfil</strong><br>
        <strong>Dado</strong> que he iniciado sesión,<br>
        <strong>Cuando</strong> accedo a “Mi perfil”,<br>
        <strong>Entonces</strong> veo mi información registrada.<br><br>
        <strong>Escenario 2: Edición de perfil</strong><br>
        <strong>Dado</strong> que deseo actualizar mis datos,<br>
        <strong>Cuando</strong> hago clic en “Editar” y guardo,<br>
        <strong>Entonces</strong> la nueva información se muestra correctamente.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Roles y permisos (RBAC)</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU008</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> administrador institucional,<br>
        <strong>Quiero</strong> asignar roles (farmacia, clínica, admin, auditor),<br>
        <strong>Para</strong> controlar permisos de acceso
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Asignación exitosa</strong><br>
        <strong>Dado</strong> que el usuario está registrado,<br>
        <strong>Cuando</strong> le asigno un rol,<br>
        <strong>Entonces</strong> obtiene permisos correspondientes de inmediato.<br><br>
        <strong>Escenario 2: Rol inexistente</strong><br>
        <strong>Dado</strong> que intento asignar un rol no definido,<br>
        <strong>Cuando</strong> confirmo la acción,<br>
        <strong>Entonces</strong> el sistema muestra error de “rol inválido”.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Políticas de sesión (expiración e inactividad)</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">3h</span></th>
    <th>ID<br><span style="font-weight: 200">HU009</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> responsable TI,<br>
        <strong>Quiero</strong> configurar expiración de sesión por inactividad,<br>
        <strong>Para</strong> reducir riesgos de acceso no autorizado
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: Sesión expirada</strong><br>
        <strong>Dado</strong> que el usuario estuvo inactivo por N minutos,<br>
        <strong>Cuando</strong> intenta acceder a una vista protegida,<br>
        <strong>Entonces</strong> se redirige a inicio de sesión con mensaje de expiración.<br><br>
        <strong>Escenario 2: Tiempo configurable</strong><br>
        <strong>Dado</strong> que TI actualiza el tiempo de inactividad,<br>
        <strong>Cuando</strong> guarda la configuración,<br>
        <strong>Entonces</strong> el nuevo tiempo aplica para sesiones futuras.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Segundo factor de autenticación (2FA OTP)</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU010</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br>
        <strong>Como</strong> usuario con permisos críticos,<br>
        <strong>Quiero</strong> habilitar 2FA mediante OTP,<br>
        <strong>Para</strong> reforzar la seguridad de acceso
    </td>
  </tr>
  <tr>
    <td colspan="4">
        <strong>Escenario 1: OTP válido</strong><br>
        <strong>Dado</strong> que el 2FA está activado,<br>
        <strong>Cuando</strong> ingreso el OTP correcto,<br>
        <strong>Entonces</strong> el sistema permite el acceso.<br><br>
        <strong>Escenario 2: OTP inválido o múltiples fallos</strong><br>
        <strong>Dado</strong> que ingreso un OTP incorrecto repetidas veces,<br>
        <strong>Cuando</strong> excedo el límite,<br>
        <strong>Entonces</strong> la cuenta se bloquea temporalmente y se notifica al usuario.
    </td>
  </tr>
</table>

<!-- ========================================= -->
<!-- Epic 2: Dispositivos IoT (provisión y salud) -->
<!-- ========================================= -->

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Alta / provisión de dispositivo IoT</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU011</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> TI,<br>
        <strong>Quiero</strong> registrar un dispositivo (ID, clave, tipo),<br>
        <strong>Para</strong> vincularlo a la plataforma y comenzar a operar
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Provisión exitosa</strong><br>
        <strong>Dado</strong> que el ID es único y las credenciales son válidas,<br>
        <strong>Cuando</strong> completo el alta,<br>
        <strong>Entonces</strong> el dispositivo queda registrado y listo para asignación.<br><br>
        <strong>Escenario 2: ID duplicado</strong><br>
        <strong>Dado</strong> que el ID ya existe,<br>
        <strong>Cuando</strong> intento registrar el dispositivo,<br>
        <strong>Entonces</strong> el sistema rechaza la operación con un mensaje claro.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Asignar dispositivo a ubicación</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU012</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> asociar cada dispositivo a una cámara/área,<br>
        <strong>Para</strong> contextualizar correctamente las lecturas
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Asignación visible</strong><br>
        <strong>Dado</strong> que selecciono un dispositivo y una ubicación,<br>
        <strong>Cuando</strong> confirmo la asignación,<br>
        <strong>Entonces</strong> el panel muestra el dispositivo bajo esa área.<br><br>
        <strong>Escenario 2: Reasignación bloqueada por alerta</strong><br>
        <strong>Dado</strong> que el dispositivo tiene alertas abiertas,<br>
        <strong>Cuando</strong> intento reasignarlo,<br>
        <strong>Entonces</strong> el sistema impide la acción e indica cerrar alertas primero.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Monitoreo de salud del dispositivo</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU013</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> TI,<br>
        <strong>Quiero</strong> ver señal, último ping y estado del dispositivo,<br>
        <strong>Para</strong> anticipar fallas y mantener disponibilidad
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Estado en línea/mudo</strong><br>
        <strong>Dado</strong> que el dispositivo reporta heartbeats,<br>
        <strong>Cuando</strong> el último ping está dentro del umbral,<br>
        <strong>Entonces</strong> se muestra “en línea”; de lo contrario “mudo”.<br><br>
        <strong>Escenario 2: Alerta por inactividad</strong><br>
        <strong>Dado</strong> que no hay ping por más de N minutos,<br>
        <strong>Cuando</strong> se supera el umbral,<br>
        <strong>Entonces</strong> se genera una alerta de dispositivo inactivo.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Actualización OTA de firmware</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">8h</span></th>
    <th>ID<br><span style="font-weight: 200">HU014</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> TI,<br>
        <strong>Quiero</strong> actualizar firmware de forma remota (OTA),<br>
        <strong>Para</strong> corregir fallos y aplicar mejoras
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: OTA exitosa</strong><br>
        <strong>Dado</strong> que selecciono una versión disponible,<br>
        <strong>Cuando</strong> ejecuto la actualización,<br>
        <strong>Entonces</strong> el dispositivo reinicia y reporta la nueva versión.<br><br>
        <strong>Escenario 2: Fallo de checksum/rollback</strong><br>
        <strong>Dado</strong> que la imagen no pasa la verificación,<br>
        <strong>Cuando</strong> el dispositivo detecta el fallo,<br>
        <strong>Entonces</strong> revierte a la versión anterior y notifica el error.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Buffer local (store-and-forward)</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">6h</span></th>
    <th>ID<br><span style="font-weight: 200">HU015</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> TI,<br>
        <strong>Quiero</strong> que el nodo almacene lecturas cuando no hay red,<br>
        <strong>Para</strong> evitar pérdida de datos y reenviarlos al reconectar
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Reenvío al reconectar</strong><br>
        <strong>Dado</strong> que hubo un corte de conectividad,<br>
        <strong>Cuando</strong> el enlace se restablece,<br>
        <strong>Entonces</strong> el nodo reenvía lecturas pendientes en orden.<br><br>
        <strong>Escenario 2: Marcas de tiempo preservadas</strong><br>
        <strong>Dado</strong> que se almacenaron lecturas en buffer,<br>
        <strong>Cuando</strong> se procesan en el backend,<br>
        <strong>Entonces</strong> conservan su timestamp original.
    </td>
  </tr>
</table>

<!-- ========================================= -->
<!-- Epic 3: Monitoreo y Alertas -->
<!-- ========================================= -->

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Configurar umbrales por ubicación/ítem</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU016</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> definir rangos de T°/HR por cámara e ítem,<br>
        <strong>Para</strong> generar alertas precisas según contexto
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Guardado de umbrales</strong><br>
        <strong>Dado</strong> que ingreso límites válidos,<br>
        <strong>Cuando</strong> guardo la configuración,<br>
        <strong>Entonces</strong> el sistema aplica los nuevos umbrales.<br><br>
        <strong>Escenario 2: Historial de cambios</strong><br>
        <strong>Dado</strong> que modifico un umbral,<br>
        <strong>Cuando</strong> se guarda,<br>
        <strong>Entonces</strong> se registra quién y cuándo hizo el cambio.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Alertas por tiempo fuera de rango</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU017</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> generar alertas si T°/HR está fuera de rango por más de N minutos,<br>
        <strong>Para</strong> evitar falsos positivos y reaccionar a tiempo
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Ventana de tolerancia</strong><br>
        <strong>Dado</strong> que la T° sale de rango,<br>
        <strong>Cuando</strong> el evento supera N minutos,<br>
        <strong>Entonces</strong> se crea una alerta.<br><br>
        <strong>Escenario 2: Vuelve a rango antes de N</strong><br>
        <strong>Dado</strong> que la T° regresó al rango,<br>
        <strong>Cuando</strong> lo hace antes del umbral,<br>
        <strong>Entonces</strong> no se genera alerta.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Preferencias de notificación (web/email/SMS/WhatsApp)</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU018</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> usuario,<br>
        <strong>Quiero</strong> elegir canales y ventanas horarias de notificación,<br>
        <strong>Para</strong> recibir alertas de forma oportuna sin ruido
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Envío por canal elegido</strong><br>
        <strong>Dado</strong> que seleccioné email y WhatsApp,<br>
        <strong>Cuando</strong> se emite una alerta,<br>
        <strong>Entonces</strong> recibo notificación por esos canales.<br><br>
        <strong>Escenario 2: Modo silencio</strong><br>
        <strong>Dado</strong> que configuré horario silencioso,<br>
        <strong>Cuando</strong> se genera una alerta en ese periodo,<br>
        <strong>Entonces</strong> no se envía notificación (salvo críticas si así se definió).
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Acknowledgement y cierre con evidencia</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU019</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> jefe de farmacia,<br>
        <strong>Quiero</strong> exigir ACK y cierre con foto/nota,<br>
        <strong>Para</strong> garantizar trazabilidad en auditorías
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Cierre con evidencia</strong><br>
        <strong>Dado</strong> que existe una alerta activa,<br>
        <strong>Cuando</strong> intento cerrarla,<br>
        <strong>Entonces</strong> el sistema requiere adjuntar evidencia y comentario.<br><br>
        <strong>Escenario 2: Auditoría de cierre</strong><br>
        <strong>Dado</strong> que la alerta fue cerrada,<br>
        <strong>Cuando</strong> consulto el detalle,<br>
        <strong>Entonces</strong> veo quién cerró, cuándo y la evidencia asociada.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Escalamiento por SLA</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU020</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> administrador,<br>
        <strong>Quiero</strong> escalar alertas no atendidas en X minutos,<br>
        <strong>Para</strong> asegurar tiempos de respuesta (MTTA) bajos
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Escalamiento activo</strong><br>
        <strong>Dado</strong> que una alerta sigue sin ACK,<br>
        <strong>Cuando</strong> se cumple el SLA configurado,<br>
        <strong>Entonces</strong> se notifica al siguiente rol en la cadena.<br><br>
        <strong>Escenario 2: Evitar duplicados</strong><br>
        <strong>Dado</strong> que la alerta ya fue aceptada,<br>
        <strong>Cuando</strong> llega el tiempo de escalamiento,<br>
        <strong>Entonces</strong> el sistema no envía notificación duplicada.
    </td>
  </tr>
</table>

<table>
  <thead>
    <th>Title<br><span style="font-weight: 200">Dashboard principal (KPIs y mapa de riesgo)</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">6h</span></th>
    <th>ID<br><span style="font-weight: 200">HU021</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> usuario,<br>
        <strong>Quiero</strong> visualizar un panel con estado por áreas, KPIs y últimas alertas,<br>
        <strong>Para</strong> priorizar acciones rápidamente
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Semáforos por área</strong><br>
        <strong>Dado</strong> que existen umbrales definidos,<br>
        <strong>Cuando</strong> accedo al panel,<br>
        <strong>Entonces</strong> veo tarjetas en verde/amarillo/rojo según cumplimiento.<br><br>
        <strong>Escenario 2: Sin datos</strong><br>
        <strong>Dado</strong> que aún no hay lecturas,<br>
        <strong>Cuando</strong> visualizo el panel,<br>
        <strong>Entonces</strong> se muestra estado vacío y recomendaciones de configuración.
    </td>
  </tr>
</table>

<!-- ========================================= -->
<!-- Epic 4: Inventario, Lotes y FEFO -->
<!-- ========================================= -->

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Registro de ítems, lotes y vencimientos</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">6h</span></th>
    <th>ID<br><span style="font-weight: 200">HU022</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> registrar ítems, lotes y fechas de vencimiento,<br>
        <strong>Para</strong> gestionar FEFO correctamente
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Alta y edición</strong><br>
        <strong>Dado</strong> que ingreso datos válidos,<br>
        <strong>Cuando</strong> creo o edito un ítem/lote,<br>
        <strong>Entonces</strong> se guarda con validaciones de formato y duplicidad.<br><br>
        <strong>Escenario 2: Bloqueo por movimientos</strong><br>
        <strong>Dado</strong> que un lote tiene movimientos asociados,<br>
        <strong>Cuando</strong> intento eliminarlo,<br>
        <strong>Entonces</strong> el sistema impide la eliminación y sugiere un ajuste.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Alertas de vencimientos (30/7/1 días)</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU023</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> recibir alertas de próximos a vencer,<br>
        <strong>Para</strong> rotar stock a tiempo y reducir mermas
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Listado y avisos</strong><br>
        <strong>Dado</strong> que hay lotes por vencer en 30/7/1 días,<br>
        <strong>Cuando</strong> consulto “Próximos a vencer”,<br>
        <strong>Entonces</strong> veo el listado y se envían notificaciones a responsables.<br><br>
        <strong>Escenario 2: Sin próximos a vencer</strong><br>
        <strong>Dado</strong> que no hay lotes dentro del rango,<br>
        <strong>Cuando</strong> abro la vista,<br>
        <strong>Entonces</strong> el sistema muestra un mensaje “sin ítems próximos a vencer”.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Mínimos/máximos y punto de reorden</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU024</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> logística,<br>
        <strong>Quiero</strong> configurar min/max y punto de reorden por ítem/ubicación,<br>
        <strong>Para</strong> activar reposición oportuna
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Alerta por mínimo</strong><br>
        <strong>Dado</strong> que el stock cae al mínimo,<br>
        <strong>Cuando</strong> se alcanza el umbral,<br>
        <strong>Entonces</strong> se genera una alerta de reposición.<br><br>
        <strong>Escenario 2: Sugerencia de cantidad</strong><br>
        <strong>Dado</strong> el histórico de consumo,<br>
        <strong>Cuando</strong> se crea la solicitud,<br>
        <strong>Entonces</strong> el sistema sugiere una cantidad de compra.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Sugerencia FEFO en salida</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">4h</span></th>
    <th>ID<br><span style="font-weight: 200">HU025</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> enfermería/quirófano,<br>
        <strong>Quiero</strong> que el sistema sugiera el lote más próximo a vencer,<br>
        <strong>Para</strong> cumplir FEFO al retirar insumos
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Orden FEFO</strong><br>
        <strong>Dado</strong> que hay varios lotes disponibles,<br>
        <strong>Cuando</strong> selecciono un ítem para salida,<br>
        <strong>Entonces</strong> se listan por fecha de vencimiento ascendente.<br><br>
        <strong>Escenario 2: Advertencia por no FEFO</strong><br>
        <strong>Dado</strong> que elijo un lote que no es el más próximo a vencer,<br>
        <strong>Cuando</strong> intento confirmar,<br>
        <strong>Entonces</strong> el sistema muestra una advertencia y permite justificar.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Recepción con evidencia de cadena de frío</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU026</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> logística,<br>
        <strong>Quiero</strong> registrar recepción con fotos y T° de transporte,<br>
        <strong>Para</strong> asegurar condiciones de cadena de frío
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Recepción con evidencia</strong><br>
        <strong>Dado</strong> que arriban insumos de frío,<br>
        <strong>Cuando</strong> registro la recepción,<br>
        <strong>Entonces</strong> adjunto fotos y T° y el sistema valida la obligatoriedad.<br><br>
        <strong>Escenario 2: Falta de evidencia</strong><br>
        <strong>Dado</strong> que no adjunto evidencia requerida,<br>
        <strong>Cuando</strong> intento finalizar,<br>
        <strong>Entonces</strong> el sistema rechaza el registro e indica los faltantes.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Conteo cíclico y ajuste de stock</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU027</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> farmacia,<br>
        <strong>Quiero</strong> realizar conteos cíclicos y ajustes auditables,<br>
        <strong>Para</strong> mantener precisión del inventario
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Diferencias justificadas</strong><br>
        <strong>Dado</strong> que el conteo difiere del sistema,<br>
        <strong>Cuando</strong> registro un ajuste,<br>
        <strong>Entonces</strong> debo ingresar motivo y responsable.<br><br>
        <strong>Escenario 2: Bitácora de ajustes</strong><br>
        <strong>Dado</strong> que se han realizado ajustes,<br>
        <strong>Cuando</strong> consulto la bitácora,<br>
        <strong>Entonces</strong> veo usuario, fecha y detalle de cada ajuste.
    </td>
  </tr>
</table>

<!-- ========================================= -->
<!-- Epic 5: Reportes, Integración y Auditoría -->
<!-- ========================================= -->

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Reporte semanal de excursiones y mermas</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU028</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> calidad,<br>
        <strong>Quiero</strong> un reporte semanal con % fuera de rango y mermas en S/.,<br>
        <strong>Para</strong> auditorías y mejora continua
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Filtros y exportación</strong><br>
        <strong>Dado</strong> que existen datos registrados,<br>
        <strong>Cuando</strong> aplico filtros por área/periodo,<br>
        <strong>Entonces</strong> obtengo el reporte y puedo exportar a CSV/PDF.<br><br>
        <strong>Escenario 2: Sin datos en el rango</strong><br>
        <strong>Dado</strong> que no hay eventos en el periodo,<br>
        <strong>Cuando</strong> genero el reporte,<br>
        <strong>Entonces</strong> se muestra un mensaje indicando ausencia de datos.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Import/Export de maestros y movimientos</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">6h</span></th>
    <th>ID<br><span style="font-weight: 200">HU029</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> integración/ERP,<br>
        <strong>Quiero</strong> importar catálogo y exportar movimientos,<br>
        <strong>Para</strong> conciliar datos con sistemas externos
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Importación válida</strong><br>
        <strong>Dado</strong> que cargo un archivo con formato correcto,<br>
        <strong>Cuando</strong> ejecuto la importación,<br>
        <strong>Entonces</strong> el sistema crea/actualiza registros y muestra un resumen.<br><br>
        <strong>Escenario 2: Errores de formato</strong><br>
        <strong>Dado</strong> que el archivo tiene filas inválidas,<br>
        <strong>Cuando</strong> intento importarlo,<br>
        <strong>Entonces</strong> se genera un reporte de errores descargable.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Bitácora de auditoría completa</span></th>
    <th>Priority<br><span style="font-weight: 200">Alta</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU030</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> auditor,<br>
        <strong>Quiero</strong> ver quién cambió umbrales, cerró alertas y editó lotes,<br>
        <strong>Para</strong> garantizar trazabilidad y cumplimiento
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Registro detallado</strong><br>
        <strong>Dado</strong> que se realizan acciones en el sistema,<br>
        <strong>Cuando</strong> consulto la auditoría,<br>
        <strong>Entonces</strong> veo usuario, acción, fecha/hora y IP.<br><br>
        <strong>Escenario 2: Exportación de auditoría</strong><br>
        <strong>Dado</strong> que necesito evidencias,<br>
        <strong>Cuando</strong> exporto la bitácora,<br>
        <strong>Entonces</strong> obtengo un archivo para inspección.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Gestión de calibración de sensores</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU031</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> ingeniería clínica,<br>
        <strong>Quiero</strong> registrar certificados y alertas de vencimiento de calibración,<br>
        <strong>Para</strong> asegurar precisión de medición
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Alerta de calibración próxima a vencer</strong><br>
        <strong>Dado</strong> que un sensor está por vencer su calibración,<br>
        <strong>Cuando</strong> faltan X días,<br>
        <strong>Entonces</strong> se genera una alerta preventiva.<br><br>
        <strong>Escenario 2: Bloqueo configurable por calibración vencida</strong><br>
        <strong>Dado</strong> que el certificado venció,<br>
        <strong>Cuando</strong> el bloqueo está habilitado,<br>
        <strong>Entonces</strong> el sistema impide usar datos de ese sensor hasta regularizar.
    </td>
  </tr>
</table>

<table >
  <thead>
    <th>Title<br><span style="font-weight: 200">Reporte de cumplimiento normativo (GDP/guías)</span></th>
    <th>Priority<br><span style="font-weight: 200">Media</span></th>
    <th>Estimate<br><span style="font-weight: 200">5h</span></th>
    <th>ID<br><span style="font-weight: 200">HU032</span></th>
  </thead>
  <tr>
    <td colspan="4">User Story:<br><strong>Como</strong> calidad,<br>
        <strong>Quiero</strong> generar un informe con evidencias de cadena de frío y acciones correctivas,<br>
        <strong>Para</strong> presentar en inspecciones regulatorias
    </td>
  </tr>
  <tr>
      <td colspan="4">
        <strong>Escenario 1: Informe completo</strong><br>
        <strong>Dado</strong> que existen excursiones y cierres con evidencia,<br>
        <strong>Cuando</strong> genero el informe por periodo/área,<br>
        <strong>Entonces</strong> se compilan excursiones, acciones y calibraciones con firma digital.<br><br>
        <strong>Escenario 2: Datos insuficientes</strong><br>
        <strong>Dado</strong> que faltan evidencias o calibraciones vigentes,<br>
        <strong>Cuando</strong> intento generar el informe,<br>
        <strong>Entonces</strong> el sistema indica los requisitos faltantes.
    </td>
  </tr>
</table>

<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 18%" />
<col style="width: 30%" />
<col style="width: 30%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr>
  <td colspan="5" style="padding: 15px; ">
    <strong>Epic 1: Autenticación y Gestión de Usuarios</strong>
  </td>
</tr>

<tr>
  <td>E1-HU001</td>
  <td>Registro de institución (hospital/clinica)</td>
  <td>
    <strong>Como</strong> administrador institucional,<br>
    <strong>Quiero</strong> registrar mi organización,<br>
    <strong>Para</strong> habilitar espacios y usuarios propios en la plataforma
  </td>
  <td>
    <strong>Escenario 1: Registro institucional exitoso</strong><br>
    <strong>Dado</strong> que proporciono datos válidos de la institución,<br>
    <strong>Cuando</strong> envío el formulario,<br>
    <strong>Entonces</strong> se crea la cuenta y recibo un correo de confirmación.<br><br>
    <strong>Escenario 2: Datos incompletos o inválidos</strong><br>
    <strong>Dado</strong> que dejo campos obligatorios vacíos o con formato incorrecto,<br>
    <strong>Cuando</strong> intento registrar la institución,<br>
    <strong>Entonces</strong> el sistema muestra mensajes de error específicos.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU002</td>
  <td>Registro de usuario</td>
  <td>
    <strong>Como</strong> nuevo usuario,<br>
    <strong>Quiero</strong> registrarme con mis datos personales y correo electrónico,<br>
    <strong>Para</strong> acceder a la plataforma
  </td>
  <td>
    <strong>Escenario 1: Registro exitoso</strong><br>
    <strong>Dado</strong> que el usuario quiere unirse a la plataforma,<br>
    <strong>Cuando</strong> completa el formulario con datos válidos,<br>
    <strong>Entonces</strong> se crea su cuenta y recibe un correo de verificación.<br><br>
    <strong>Escenario 2: Correo ya registrado</strong><br>
    <strong>Dado</strong> que el correo ya existe en el sistema,<br>
    <strong>Cuando</strong> intento registrarme,<br>
    <strong>Entonces</strong> el sistema indica que el correo está en uso.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU003</td>
  <td>Inicio de sesión</td>
  <td>
    <strong>Como</strong> usuario registrado,<br>
    <strong>Quiero</strong> iniciar sesión con mi correo y contraseña,<br>
    <strong>Para</strong> acceder a mi cuenta de forma segura
  </td>
  <td>
    <strong>Escenario 1: Inicio exitoso</strong><br>
    <strong>Dado</strong> que tengo credenciales correctas,<br>
    <strong>Cuando</strong> las ingreso y presiono "Iniciar sesión",<br>
    <strong>Entonces</strong> accedo a mi dashboard.<br><br>
    <strong>Escenario 2: Inicio fallido</strong><br>
    <strong>Dado</strong> que ingreso credenciales incorrectas,<br>
    <strong>Cuando</strong> intento iniciar sesión,<br>
    <strong>Entonces</strong> veo el mensaje "usuario o contraseña inválida".
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU004</td>
  <td>Cerrar sesión</td>
  <td>
    <strong>Como</strong> usuario autenticado,<br>
    <strong>Quiero</strong> finalizar mi sesión,<br>
    <strong>Para</strong> proteger el acceso a mis datos
  </td>
  <td>
    <strong>Escenario 1: Cierre exitoso</strong><br>
    <strong>Dado</strong> que tengo una sesión activa,<br>
    <strong>Cuando</strong> selecciono "Cerrar sesión",<br>
    <strong>Entonces</strong> el sistema finaliza la sesión y redirige al login.<br><br>
    <strong>Escenario 2: Sin sesión activa</strong><br>
    <strong>Dado</strong> que no tengo sesión,<br>
    <strong>Cuando</strong> accedo a la URL de cerrar sesión,<br>
    <strong>Entonces</strong> se muestra la pantalla de inicio de sesión.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU005</td>
  <td>Recuperación de contraseña</td>
  <td>
    <strong>Como</strong> usuario registrado,<br>
    <strong>Quiero</strong> recuperar mi contraseña mediante mi correo,<br>
    <strong>Para</strong> restablecer el acceso en caso de olvido
  </td>
  <td>
    <strong>Escenario 1: Solicitud de recuperación</strong><br>
    <strong>Dado</strong> que olvidé mi contraseña,<br>
    <strong>Cuando</strong> ingreso mi correo en "Recuperar contraseña",<br>
    <strong>Entonces</strong> recibo un enlace de restablecimiento.<br><br>
    <strong>Escenario 2: Correo inexistente</strong><br>
    <strong>Dado</strong> que ingreso un correo no registrado,<br>
    <strong>Cuando</strong> solicito recuperación,<br>
    <strong>Entonces</strong> el sistema informa que no existe una cuenta asociada.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU006</td>
  <td>Cambio de contraseña</td>
  <td>
    <strong>Como</strong> usuario autenticado,<br>
    <strong>Quiero</strong> cambiar mi contraseña desde mi perfil,<br>
    <strong>Para</strong> mantener mi cuenta segura
  </td>
  <td>
    <strong>Escenario 1: Cambio exitoso</strong><br>
    <strong>Dado</strong> que accedo a mi perfil,<br>
    <strong>Cuando</strong> introduzco mi contraseña actual y la nueva válida,<br>
    <strong>Entonces</strong> el sistema confirma el cambio.<br><br>
    <strong>Escenario 2: Error de validación</strong><br>
    <strong>Dado</strong> que ingreso la contraseña actual incorrecta,<br>
    <strong>Cuando</strong> intento guardar,<br>
    <strong>Entonces</strong> el sistema muestra un mensaje de error.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU007</td>
  <td>Gestión de perfil de usuario</td>
  <td>
    <strong>Como</strong> usuario autenticado,<br>
    <strong>Quiero</strong> ver y editar mi información de perfil,<br>
    <strong>Para</strong> mantener mis datos actualizados
  </td>
  <td>
    <strong>Escenario 1: Visualización de perfil</strong><br>
    <strong>Dado</strong> que he iniciado sesión,<br>
    <strong>Cuando</strong> accedo a "Mi perfil",<br>
    <strong>Entonces</strong> veo mi información registrada.<br><br>
    <strong>Escenario 2: Edición de perfil</strong><br>
    <strong>Dado</strong> que deseo actualizar mis datos,<br>
    <strong>Cuando</strong> guardo los cambios,<br>
    <strong>Entonces</strong> la nueva información se muestra correctamente.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU008</td>
  <td>Roles y permisos (RBAC)</td>
  <td>
    <strong>Como</strong> administrador institucional,<br>
    <strong>Quiero</strong> asignar roles (farmacia, clínica, admin, auditor),<br>
    <strong>Para</strong> controlar permisos de acceso
  </td>
  <td>
    <strong>Escenario 1: Asignación exitosa</strong><br>
    <strong>Dado</strong> que el usuario está registrado,<br>
    <strong>Cuando</strong> le asigno un rol,<br>
    <strong>Entonces</strong> obtiene los permisos correspondientes.<br><br>
    <strong>Escenario 2: Rol inexistente</strong><br>
    <strong>Dado</strong> que intento asignar un rol no definido,<br>
    <strong>Cuando</strong> confirmo la acción,<br>
    <strong>Entonces</strong> el sistema muestra "rol inválido".
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU009</td>
  <td>Políticas de sesión (expiración e inactividad)</td>
  <td>
    <strong>Como</strong> responsable TI,<br>
    <strong>Quiero</strong> configurar expiración de sesión por inactividad,<br>
    <strong>Para</strong> reducir riesgos de acceso no autorizado
  </td>
  <td>
    <strong>Escenario 1: Sesión expirada</strong><br>
    <strong>Dado</strong> que el usuario estuvo inactivo por N minutos,<br>
    <strong>Cuando</strong> intenta acceder a una vista protegida,<br>
    <strong>Entonces</strong> se redirige al inicio de sesión con mensaje de expiración.<br><br>
    <strong>Escenario 2: Tiempo configurable</strong><br>
    <strong>Dado</strong> que TI actualiza el umbral de inactividad,<br>
    <strong>Cuando</strong> guarda la configuración,<br>
    <strong>Entonces</strong> el nuevo tiempo aplica para sesiones futuras.
  </td>
  <td>1</td>
</tr>

<tr>
  <td>E1-HU010</td>
  <td>Segundo factor de autenticación (2FA OTP)</td>
  <td>
    <strong>Como</strong> usuario con permisos críticos,<br>
    <strong>Quiero</strong> habilitar 2FA mediante OTP,<br>
    <strong>Para</strong> reforzar la seguridad de acceso
  </td>
  <td>
    <strong>Escenario 1: OTP válido</strong><br>
    <strong>Dado</strong> que el 2FA está activado,<br>
    <strong>Cuando</strong> ingreso el OTP correcto,<br>
    <strong>Entonces</strong> el sistema permite el acceso.<br><br>
    <strong>Escenario 2: OTP inválido o múltiples fallos</strong><br>
    <strong>Dado</strong> que ingreso un OTP incorrecto repetidas veces,<br>
    <strong>Cuando</strong> excedo el límite,<br>
    <strong>Entonces</strong> la cuenta se bloquea temporalmente y se notifica al usuario.
  </td>
  <td>1</td>
</tr>

</tbody>
</table>


<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 18%" />
<col style="width: 30%" />
<col style="width: 30%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr>
  <td colspan="5" style="padding: 15px; ">
    <strong>Epic 2: Dispositivos IoT (provisión y salud)</strong>
  </td>
</tr>

<tr>
  <td>E2-HU011</td>
  <td>Alta / provisión de dispositivo IoT</td>
  <td>
    <strong>Como</strong> TI,<br>
    <strong>Quiero</strong> registrar un dispositivo (ID, clave, tipo),<br>
    <strong>Para</strong> vincularlo y comenzar a operar
  </td>
  <td>
    <strong>Escenario 1: Provisión exitosa</strong><br>
    <strong>Dado</strong> que el ID es único y las credenciales son válidas,<br>
    <strong>Cuando</strong> completo el alta,<br>
    <strong>Entonces</strong> el dispositivo queda listo para asignación.<br><br>
    <strong>Escenario 2: ID duplicado</strong><br>
    <strong>Dado</strong> que el ID ya existe,<br>
    <strong>Cuando</strong> intento registrar el dispositivo,<br>
    <strong>Entonces</strong> el sistema rechaza la operación con mensaje claro.
  </td>
  <td>2</td>
</tr>

<tr>
  <td>E2-HU012</td>
  <td>Asignar dispositivo a ubicación</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> asociar cada dispositivo a una cámara/área,<br>
    <strong>Para</strong> contextualizar correctamente las lecturas
  </td>
  <td>
    <strong>Escenario 1: Asignación visible</strong><br>
    <strong>Dado</strong> que selecciono un dispositivo y una ubicación,<br>
    <strong>Cuando</strong> confirmo la asignación,<br>
    <strong>Entonces</strong> el panel muestra el dispositivo bajo esa área.<br><br>
    <strong>Escenario 2: Reasignación bloqueada por alerta</strong><br>
    <strong>Dado</strong> que el dispositivo tiene alertas abiertas,<br>
    <strong>Cuando</strong> intento reasignarlo,<br>
    <strong>Entonces</strong> el sistema impide la acción e indica cerrar alertas primero.
  </td>
  <td>2</td>
</tr>

<tr>
  <td>E2-HU013</td>
  <td>Monitoreo de salud del dispositivo</td>
  <td>
    <strong>Como</strong> TI,<br>
    <strong>Quiero</strong> ver señal, último ping y estado del dispositivo,<br>
    <strong>Para</strong> anticipar fallas y mantener disponibilidad
  </td>
  <td>
    <strong>Escenario 1: Estado en línea/mudo</strong><br>
    <strong>Dado</strong> que el dispositivo reporta heartbeats,<br>
    <strong>Cuando</strong> el último ping está dentro del umbral,<br>
    <strong>Entonces</strong> se muestra "en línea"; de lo contrario "mudo".<br><br>
    <strong>Escenario 2: Alerta por inactividad</strong><br>
    <strong>Dado</strong> que no hay ping por más de N minutos,<br>
    <strong>Cuando</strong> se supera el umbral,<br>
    <strong>Entonces</strong> se genera una alerta de dispositivo inactivo.
  </td>
  <td>2</td>
</tr>

<tr>
  <td>E2-HU014</td>
  <td>Actualización OTA de firmware</td>
  <td>
    <strong>Como</strong> TI,<br>
    <strong>Quiero</strong> actualizar firmware de forma remota (OTA),<br>
    <strong>Para</strong> corregir fallos y aplicar mejoras
  </td>
  <td>
    <strong>Escenario 1: OTA exitosa</strong><br>
    <strong>Dado</strong> que selecciono una versión disponible,<br>
    <strong>Cuando</strong> ejecuto la actualización,<br>
    <strong>Entonces</strong> el dispositivo reinicia y reporta la nueva versión.<br><br>
    <strong>Escenario 2: Fallo de checksum/rollback</strong><br>
    <strong>Dado</strong> que la imagen no pasa la verificación,<br>
    <strong>Cuando</strong> el dispositivo detecta el fallo,<br>
    <strong>Entonces</strong> revierte a la versión anterior y notifica el error.
  </td>
  <td>2</td>
</tr>

<tr>
  <td>E2-HU015</td>
  <td>Buffer local (store-and-forward)</td>
  <td>
    <strong>Como</strong> TI,<br>
    <strong>Quiero</strong> que el nodo almacene lecturas cuando no hay red,<br>
    <strong>Para</strong> evitar pérdida de datos y reenviarlos al reconectar
  </td>
  <td>
    <strong>Escenario 1: Reenvío al reconectar</strong><br>
    <strong>Dado</strong> que hubo un corte de conectividad,<br>
    <strong>Cuando</strong> el enlace se restablece,<br>
    <strong>Entonces</strong> el nodo reenvía lecturas pendientes en orden.<br><br>
    <strong>Escenario 2: Marcas de tiempo preservadas</strong><br>
    <strong>Dado</strong> que se almacenaron lecturas en buffer,<br>
    <strong>Cuando</strong> se procesan en el backend,<br>
    <strong>Entonces</strong> conservan su timestamp original.
  </td>
  <td>2</td>
</tr>

</tbody>
</table>


<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 18%" />
<col style="width: 30%" />
<col style="width: 30%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr>
  <td colspan="5" style="padding: 15px; ">
    <strong>Epic 3: Monitoreo y Alertas</strong>
  </td>
</tr>

<tr>
  <td>E3-HU016</td>
  <td>Configurar umbrales por ubicación/ítem</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> definir rangos de T°/HR por cámara e ítem,<br>
    <strong>Para</strong> generar alertas precisas según contexto
  </td>
  <td>
    <strong>Escenario 1: Guardado de umbrales</strong><br>
    <strong>Dado</strong> que ingreso límites válidos,<br>
    <strong>Cuando</strong> guardo la configuración,<br>
    <strong>Entonces</strong> el sistema aplica los nuevos umbrales.<br><br>
    <strong>Escenario 2: Historial de cambios</strong><br>
    <strong>Dado</strong> que modifico un umbral,<br>
    <strong>Cuando</strong> se guarda,<br>
    <strong>Entonces</strong> se registra quién y cuándo hizo el cambio.
  </td>
  <td>3</td>
</tr>

<tr>
  <td>E3-HU017</td>
  <td>Alertas por tiempo fuera de rango</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> generar alertas si T°/HR está fuera de rango por más de N minutos,<br>
    <strong>Para</strong> evitar falsos positivos y reaccionar a tiempo
  </td>
  <td>
    <strong>Escenario 1: Ventana de tolerancia</strong><br>
    <strong>Dado</strong> que la T° sale de rango,<br>
    <strong>Cuando</strong> el evento supera N minutos,<br>
    <strong>Entonces</strong> se crea una alerta.<br><br>
    <strong>Escenario 2: Vuelve a rango antes de N</strong><br>
    <strong>Dado</strong> que la T° regresó al rango,<br>
    <strong>Cuando</strong> ocurre antes del umbral,<br>
    <strong>Entonces</strong> no se genera alerta.
  </td>
  <td>3</td>
</tr>

<tr>
  <td>E3-HU018</td>
  <td>Preferencias de notificación (web/email/SMS/WhatsApp)</td>
  <td>
    <strong>Como</strong> usuario,<br>
    <strong>Quiero</strong> elegir canales y ventanas horarias de notificación,<br>
    <strong>Para</strong> recibir alertas oportunas sin ruido
  </td>
  <td>
    <strong>Escenario 1: Envío por canal elegido</strong><br>
    <strong>Dado</strong> que seleccioné email y WhatsApp,<br>
    <strong>Cuando</strong> se emite una alerta,<br>
    <strong>Entonces</strong> recibo notificación por esos canales.<br><br>
    <strong>Escenario 2: Modo silencio</strong><br>
    <strong>Dado</strong> que configuré horario silencioso,<br>
    <strong>Cuando</strong> se genera una alerta en ese periodo,<br>
    <strong>Entonces</strong> no se envía notificación (salvo críticas si así se definió).
  </td>
  <td>3</td>
</tr>

<tr>
  <td>E3-HU019</td>
  <td>Acknowledgement y cierre con evidencia</td>
  <td>
    <strong>Como</strong> jefe de farmacia,<br>
    <strong>Quiero</strong> exigir ACK y cierre con foto/nota,<br>
    <strong>Para</strong> garantizar trazabilidad en auditorías
  </td>
  <td>
    <strong>Escenario 1: Cierre con evidencia</strong><br>
    <strong>Dado</strong> que existe una alerta activa,<br>
    <strong>Cuando</strong> intento cerrarla,<br>
    <strong>Entonces</strong> el sistema requiere adjuntar evidencia y comentario.<br><br>
    <strong>Escenario 2: Auditoría de cierre</strong><br>
    <strong>Dado</strong> que la alerta fue cerrada,<br>
    <strong>Cuando</strong> consulto el detalle,<br>
    <strong>Entonces</strong> veo quién cerró, cuándo y la evidencia asociada.
  </td>
  <td>3</td>
</tr>

<tr>
  <td>E3-HU020</td>
  <td>Escalamiento por SLA</td>
  <td>
    <strong>Como</strong> administrador,<br>
    <strong>Quiero</strong> escalar alertas no atendidas en X minutos,<br>
    <strong>Para</strong> asegurar tiempos de respuesta bajos
  </td>
  <td>
    <strong>Escenario 1: Escalamiento activo</strong><br>
    <strong>Dado</strong> que una alerta sigue sin ACK,<br>
    <strong>Cuando</strong> se cumple el SLA configurado,<br>
    <strong>Entonces</strong> se notifica al siguiente rol en la cadena.<br><br>
    <strong>Escenario 2: Evitar duplicados</strong><br>
    <strong>Dado</strong> que la alerta ya fue aceptada,<br>
    <strong>Cuando</strong> llega el tiempo de escalamiento,<br>
    <strong>Entonces</strong> el sistema no envía notificación duplicada.
  </td>
  <td>3</td>
</tr>

<tr>
  <td>E3-HU021</td>
  <td>Dashboard principal (KPIs y mapa de riesgo)</td>
  <td>
    <strong>Como</strong> usuario,<br>
    <strong>Quiero</strong> visualizar un panel con estado por áreas, KPIs y últimas alertas,<br>
    <strong>Para</strong> priorizar acciones rápidamente
  </td>
  <td>
    <strong>Escenario 1: Semáforos por área</strong><br>
    <strong>Dado</strong> que existen umbrales definidos,<br>
    <strong>Cuando</strong> accedo al panel,<br>
    <strong>Entonces</strong> veo tarjetas en verde/amarillo/rojo según cumplimiento.<br><br>
    <strong>Escenario 2: Sin datos</strong><br>
    <strong>Dado</strong> que aún no hay lecturas,<br>
    <strong>Cuando</strong> visualizo el panel,<br>
    <strong>Entonces</strong> se muestra estado vacío y recomendaciones de configuración.
  </td>
  <td>3</td>
</tr>

</tbody>
</table>


<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 18%" />
<col style="width: 30%" />
<col style="width: 30%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr>
  <td colspan="5" style="padding: 15px; ">
    <strong>Epic 4: Inventario, Lotes y FEFO</strong>
  </td>
</tr>

<tr>
  <td>E4-HU022</td>
  <td>Registro de ítems, lotes y vencimientos</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> registrar ítems, lotes y fechas de vencimiento,<br>
    <strong>Para</strong> gestionar FEFO correctamente
  </td>
  <td>
    <strong>Escenario 1: Alta y edición</strong><br>
    <strong>Dado</strong> que ingreso datos válidos,<br>
    <strong>Cuando</strong> creo o edito un ítem/lote,<br>
    <strong>Entonces</strong> se guarda con validaciones de formato y duplicidad.<br><br>
    <strong>Escenario 2: Bloqueo por movimientos</strong><br>
    <strong>Dado</strong> que un lote tiene movimientos asociados,<br>
    <strong>Cuando</strong> intento eliminarlo,<br>
    <strong>Entonces</strong> el sistema impide la eliminación y sugiere un ajuste.
  </td>
  <td>4</td>
</tr>

<tr>
  <td>E4-HU023</td>
  <td>Alertas de vencimientos (30/7/1 días)</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> recibir alertas de próximos a vencer,<br>
    <strong>Para</strong> rotar stock a tiempo y reducir mermas
  </td>
  <td>
    <strong>Escenario 1: Listado y avisos</strong><br>
    <strong>Dado</strong> que hay lotes por vencer en 30/7/1 días,<br>
    <strong>Cuando</strong> consulto "Próximos a vencer",<br>
    <strong>Entonces</strong> veo el listado y se envían notificaciones a responsables.<br><br>
    <strong>Escenario 2: Sin próximos a vencer</strong><br>
    <strong>Dado</strong> que no hay lotes dentro del rango,<br>
    <strong>Cuando</strong> abro la vista,<br>
    <strong>Entonces</strong> el sistema muestra "sin ítems próximos a vencer".
  </td>
  <td>4</td>
</tr>

<tr>
  <td>E4-HU024</td>
  <td>Mínimos/máximos y punto de reorden</td>
  <td>
    <strong>Como</strong> logística,<br>
    <strong>Quiero</strong> configurar min/max y punto de reorden por ítem/ubicación,<br>
    <strong>Para</strong> activar reposición oportuna
  </td>
  <td>
    <strong>Escenario 1: Alerta por mínimo</strong><br>
    <strong>Dado</strong> que el stock cae al mínimo,<br>
    <strong>Cuando</strong> se alcanza el umbral,<br>
    <strong>Entonces</strong> se genera una alerta de reposición.<br><br>
    <strong>Escenario 2: Sugerencia de cantidad</strong><br>
    <strong>Dado</strong> el histórico de consumo,<br>
    <strong>Cuando</strong> se crea la solicitud,<br>
    <strong>Entonces</strong> el sistema sugiere una cantidad de compra.
  </td>
  <td>4</td>
</tr>

<tr>
  <td>E4-HU025</td>
  <td>Sugerencia FEFO en salida</td>
  <td>
    <strong>Como</strong> enfermería/quirófano,<br>
    <strong>Quiero</strong> que el sistema sugiera el lote más próximo a vencer,<br>
    <strong>Para</strong> cumplir FEFO al retirar insumos
  </td>
  <td>
    <strong>Escenario 1: Orden FEFO</strong><br>
    <strong>Dado</strong> que hay varios lotes disponibles,<br>
    <strong>Cuando</strong> selecciono un ítem para salida,<br>
    <strong>Entonces</strong> se listan por fecha de vencimiento ascendente.<br><br>
    <strong>Escenario 2: Advertencia por no FEFO</strong><br>
    <strong>Dado</strong> que elijo un lote que no es el más próximo a vencer,<br>
    <strong>Cuando</strong> intento confirmar,<br>
    <strong>Entonces</strong> el sistema muestra advertencia y permite justificar.
  </td>
  <td>4</td>
</tr>

<tr>
  <td>E4-HU026</td>
  <td>Recepción con evidencia de cadena de frío</td>
  <td>
    <strong>Como</strong> logística,<br>
    <strong>Quiero</strong> registrar recepción con fotos y T° de transporte,<br>
    <strong>Para</strong> asegurar condiciones de cadena de frío
  </td>
  <td>
    <strong>Escenario 1: Recepción con evidencia</strong><br>
    <strong>Dado</strong> que arriban insumos de frío,<br>
    <strong>Cuando</strong> registro la recepción,<br>
    <strong>Entonces</strong> adjunto fotos y T° y el sistema valida la obligatoriedad.<br><br>
    <strong>Escenario 2: Falta de evidencia</strong><br>
    <strong>Dado</strong> que no adjunto evidencia requerida,<br>
    <strong>Cuando</strong> intento finalizar,<br>
    <strong>Entonces</strong> el sistema rechaza el registro e indica los faltantes.
  </td>
  <td>4</td>
</tr>

<tr>
  <td>E4-HU027</td>
  <td>Conteo cíclico y ajuste de stock</td>
  <td>
    <strong>Como</strong> farmacia,<br>
    <strong>Quiero</strong> realizar conteos cíclicos y ajustes auditables,<br>
    <strong>Para</strong> mantener precisión del inventario
  </td>
  <td>
    <strong>Escenario 1: Diferencias justificadas</strong><br>
    <strong>Dado</strong> que el conteo difiere del sistema,<br>
    <strong>Cuando</strong> registro un ajuste,<br>
    <strong>Entonces</strong> debo ingresar motivo y responsable.<br><br>
    <strong>Escenario 2: Bitácora de ajustes</strong><br>
    <strong>Dado</strong> que se han realizado ajustes,<br>
    <strong>Cuando</strong> consulto la bitácora,<br>
    <strong>Entonces</strong> veo usuario, fecha y detalle de cada ajuste.
  </td>
  <td>4</td>
</tr>

</tbody>
</table>


<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 18%" />
<col style="width: 30%" />
<col style="width: 30%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr>
  <td colspan="5" style="padding: 15px; ">
    <strong>Epic 5: Reportes, Integración y Auditoría</strong>
  </td>
</tr>

<tr>
  <td>E5-HU028</td>
  <td>Reporte semanal de excursiones y mermas</td>
  <td>
    <strong>Como</strong> calidad,<br>
    <strong>Quiero</strong> un reporte semanal con % fuera de rango y mermas en S/.,<br>
    <strong>Para</strong> auditorías y mejora continua
  </td>
  <td>
    <strong>Escenario 1: Filtros y exportación</strong><br>
    <strong>Dado</strong> que existen datos registrados,<br>
    <strong>Cuando</strong> aplico filtros por área/periodo,<br>
    <strong>Entonces</strong> obtengo el reporte y puedo exportar a CSV/PDF.<br><br>
    <strong>Escenario 2: Sin datos en el rango</strong><br>
    <strong>Dado</strong> que no hay eventos en el periodo,<br>
    <strong>Cuando</strong> genero el reporte,<br>
    <strong>Entonces</strong> se muestra un mensaje indicando ausencia de datos.
  </td>
  <td>5</td>
</tr>

<tr>
  <td>E5-HU029</td>
  <td>Import/Export de maestros y movimientos</td>
  <td>
    <strong>Como</strong> integración/ERP,<br>
    <strong>Quiero</strong> importar catálogo y exportar movimientos,<br>
    <strong>Para</strong> conciliar datos con sistemas externos
  </td>
  <td>
    <strong>Escenario 1: Importación válida</strong><br>
    <strong>Dado</strong> que cargo un archivo con formato correcto,<br>
    <strong>Cuando</strong> ejecuto la importación,<br>
    <strong>Entonces</strong> el sistema crea/actualiza registros y muestra un resumen.<br><br>
    <strong>Escenario 2: Errores de formato</strong><br>
    <strong>Dado</strong> que el archivo tiene filas inválidas,<br>
    <strong>Cuando</strong> intento importarlo,<br>
    <strong>Entonces</strong> se genera un reporte de errores descargable.
  </td>
  <td>5</td>
</tr>

<tr>
  <td>E5-HU030</td>
  <td>Bitácora de auditoría completa</td>
  <td>
    <strong>Como</strong> auditor,<br>
    <strong>Quiero</strong> ver quién cambió umbrales, cerró alertas y editó lotes,<br>
    <strong>Para</strong> garantizar trazabilidad y cumplimiento
  </td>
  <td>
    <strong>Escenario 1: Registro detallado</strong><br>
    <strong>Dado</strong> que se realizan acciones en el sistema,<br>
    <strong>Cuando</strong> consulto la auditoría,<br>
    <strong>Entonces</strong> veo usuario, acción, fecha/hora e IP.<br><br>
    <strong>Escenario 2: Exportación de auditoría</strong><br>
    <strong>Dado</strong> que necesito evidencias,<br>
    <strong>Cuando</strong> exporto la bitácora,<br>
    <strong>Entonces</strong> obtengo un archivo para inspección.
  </td>
  <td>5</td>
</tr>

<tr>
  <td>E5-HU031</td>
  <td>Gestión de calibración de sensores</td>
  <td>
    <strong>Como</strong> ingeniería clínica,<br>
    <strong>Quiero</strong> registrar certificados y alertas de vencimiento de calibración,<br>
    <strong>Para</strong> asegurar precisión de medición
  </td>
  <td>
    <strong>Escenario 1: Alerta de calibración próxima a vencer</strong><br>
    <strong>Dado</strong> que un sensor está por vencer su calibración,<br>
    <strong>Cuando</strong> faltan X días,<br>
    <strong>Entonces</strong> se genera una alerta preventiva.<br><br>
    <strong>Escenario 2: Bloqueo configurable</strong><br>
    <strong>Dado</strong> que el certificado venció,<br>
    <strong>Cuando</strong> el bloqueo está habilitado,<br>
    <strong>Entonces</strong> el sistema impide usar datos de ese sensor hasta regularizar.
  </td>
  <td>5</td>
</tr>

<tr>
  <td>E5-HU032</td>
  <td>Reporte de cumplimiento normativo (GDP/guías)</td>
  <td>
    <strong>Como</strong> calidad,<br>
    <strong>Quiero</strong> generar un informe con evidencias de cadena de frío y acciones correctivas,<br>
    <strong>Para</strong> presentar en inspecciones regulatorias
  </td>
  <td>
    <strong>Escenario 1: Informe completo</strong><br>
    <strong>Dado</strong> que existen excursiones, cierres con evidencia y calibraciones vigentes,<br>
    <strong>Cuando</strong> genero el informe por periodo/área,<br>
    <strong>Entonces</strong> se compilan hallazgos y acciones con firma digital.<br><br>
    <strong>Escenario 2: Datos insuficientes</strong><br>
    <strong>Dado</strong> que faltan evidencias o calibraciones,<br>
    <strong>Cuando</strong> intento generar el informe,<br>
    <strong>Entonces</strong> el sistema indica los requisitos faltantes.
  </td>
  <td>5</td>
</tr>

</tbody>
</table>


## 3.1. Impact Mapping 

## 3.3. Product Backlog
## 3.4. Product Backlog
| Orden | User Story / Technical Story Id | Título                                                   | Descripción                                                                                                                                                       | Story Points |
| ----- | ------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1     | E1-HU001                        | Registro de institución (hospital/clinica)               | Como administrador institucional, quiero registrar mi organización para habilitar espacios y usuarios propios en la plataforma.                                   | 5            |
| 2     | E1-HU002                        | Registro de usuario                                      | Como nuevo usuario, quiero registrarme con mis datos personales y correo para acceder a la plataforma.                                                             | 5            |
| 3     | E1-HU003                        | Inicio de sesión                                         | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña para acceder de forma segura.                                                            | 3            |
| 4     | E1-HU004                        | Cerrar sesión                                            | Como usuario autenticado, quiero poder cerrar sesión para proteger el acceso a mis datos.                                                                          | 1            |
| 5     | E1-HU007                        | Gestión de perfil de usuario                             | Como usuario autenticado, quiero ver y editar mi información de perfil para mantener mis datos actualizados.                                                      | 2            |
| 6     | E1-HU005                        | Recuperación de contraseña                               | Como usuario registrado, quiero recuperar mi contraseña vía correo para restablecer el acceso a mi cuenta.                                                         | 2            |
| 7     | E1-HU006                        | Cambio de contraseña                                     | Como usuario autenticado, quiero cambiar mi contraseña desde mi perfil para mantener mi cuenta segura.                                                             | 1            |
| 8     | E1-HU008                        | Roles y permisos (RBAC)                                  | Como administrador institucional, quiero asignar roles (farmacia, clínica, admin, auditor) para controlar permisos de acceso.                                     | 5            |
| 9     | E1-HU009                        | Políticas de sesión (expiración e inactividad)           | Como responsable TI, quiero configurar la expiración por inactividad para reducir riesgos de acceso no autorizado.                                                 | 3            |
| 10    | E1-HU010                        | Segundo factor de autenticación (2FA OTP)                | Como usuario con permisos críticos, quiero habilitar 2FA para reforzar la seguridad de acceso.                                                                     | 5            |
| 11    | E2-HU011                        | Alta / provisión de dispositivo IoT                      | Como TI, quiero registrar un dispositivo (ID, clave, tipo) para vincularlo y comenzar a operar.                                                                    | 5            |
| 12    | E2-HU012                        | Asignar dispositivo a ubicación                          | Como farmacia, quiero asociar cada dispositivo a una cámara/área para contextualizar correctamente las lecturas.                                                   | 3            |
| 13    | E2-HU013                        | Monitoreo de salud del dispositivo                       | Como TI, quiero ver señal, último ping y estado del dispositivo para anticipar fallas y mantener disponibilidad.                                                   | 5            |
| 14    | E2-HU015                        | Buffer local (store-and-forward)                         | Como TI, quiero que el nodo almacene lecturas cuando no hay red para evitar pérdida de datos y reenviarlas al reconectar.                                         | 8            |
| 15    | E2-HU014                        | Actualización OTA de firmware                            | Como TI, quiero actualizar firmware de forma remota (OTA) para corregir fallos y aplicar mejoras.                                                                  | 8            |
| 16    | E3-HU016                        | Configurar umbrales por ubicación/ítem                   | Como farmacia, quiero definir rangos de T°/HR por cámara e ítem para generar alertas precisas según contexto.                                                      | 3            |
| 17    | E3-HU017                        | Alertas por tiempo fuera de rango                        | Como farmacia, quiero alertas si T°/HR está fuera de rango por más de N minutos para evitar falsos positivos y reaccionar a tiempo.                               | 5            |
| 18    | E3-HU018                        | Preferencias de notificación (web/email/SMS/WhatsApp)    | Como usuario, quiero elegir canales y ventanas horarias de notificación para recibir alertas oportunas sin ruido.                                                  | 3            |
| 19    | E3-HU020                        | Escalamiento por SLA                                     | Como administrador, quiero escalar alertas no atendidas en X minutos para asegurar tiempos de respuesta bajos.                                                     | 5            |
| 20    | E3-HU019                        | Acknowledgement y cierre con evidencia                    | Como jefe de farmacia, quiero exigir ACK y cierre con foto/nota para garantizar trazabilidad en auditorías.                                                        | 5            |
| 21    | E3-HU021                        | Dashboard principal (KPIs y mapa de riesgo)              | Como usuario, quiero visualizar un panel con estado por áreas, KPIs y últimas alertas para priorizar acciones rápidamente.                                         | 5            |
| 22    | E4-HU022                        | Registro de ítems, lotes y vencimientos                  | Como farmacia, quiero registrar ítems, lotes y fechas de vencimiento para gestionar FEFO correctamente.                                                            | 5            |
| 23    | E4-HU024                        | Mínimos/máximos y punto de reorden                       | Como logística, quiero configurar min/max y punto de reorden por ítem/ubicación para activar reposición oportuna.                                                  | 5            |
| 24    | E4-HU023                        | Alertas de vencimientos (30/7/1 días)                    | Como farmacia, quiero recibir alertas de próximos a vencer para rotar stock a tiempo y reducir mermas.                                                             | 3            |
| 25    | E4-HU026                        | Recepción con evidencia de cadena de frío                | Como logística, quiero registrar recepción con fotos y T° de transporte para asegurar condiciones de cadena de frío.                                               | 5            |
| 26    | E4-HU025                        | Sugerencia FEFO en salida                                | Como enfermería/quirófano, quiero que el sistema sugiera el lote más próximo a vencer para cumplir FEFO al retirar insumos.                                        | 5            |
| 27    | E4-HU027                        | Conteo cíclico y ajuste de stock                         | Como farmacia, quiero realizar conteos cíclicos y ajustes auditables para mantener precisión del inventario.                                                        | 5            |
| 28    | E5-HU030                        | Bitácora de auditoría completa                           | Como auditor, quiero ver quién cambió umbrales, cerró alertas y editó lotes para garantizar trazabilidad y cumplimiento.                                           | 5            |
| 29    | E5-HU029                        | Import/Export de maestros y movimientos                  | Como integración/ERP, quiero importar catálogo y exportar movimientos para conciliar datos con sistemas externos.                                                  | 5            |
| 30    | E5-HU028                        | Reporte semanal de excursiones y mermas                  | Como calidad, quiero un reporte semanal con % fuera de rango y mermas en S/. para auditorías y mejora continua.                                                    | 3            |
| 31    | E5-HU031                        | Gestión de calibración de sensores                       | Como ingeniería clínica, quiero registrar certificados y alertas de vencimiento de calibración para asegurar precisión de medición.                                | 5            |
| 32    | E5-HU032                        | Reporte de cumplimiento normativo (GDP/guías)            | Como calidad, quiero generar un informe con evidencias de cadena de frío y acciones correctivas para presentar en inspecciones regulatorias.                       | 8            |


# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.3. Software Architecture Container Level Diagrams
#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines
### 5.1.1. General Style Guidelines
### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture
### 5.2.1. Organization Systems
### 5.2.2. Labeling Systems
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems
### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design
### 5.3.1. Landing Page Wireframe
### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design
### 5.4.1. Applications Wireframes
### 5.4.2. Applications Wireflow Diagrams
### 5.4.3. Applications Mock-ups
### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation
### 6.2.X. Sprint n
#### 6.2.X.1. Sprint Planning n
#### 6.2.X.2. Aspect Leaders and Collaborators
#### 6.2.X.3. Sprint Backlog n
#### 6.2.X.4. Development Evidence for Sprint Review
#### 6.2.X.5. Testing Suite Evidence for Sprint Review
#### 6.2.X.6. Execution Evidence for Sprint Review
#### 6.2.X.7. Services Documentation Evidence for Sprint Review
#### 6.2.X.8. Software Deployment Evidence for Sprint Review
#### 6.2.X.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
### 6.3.2. Registro de Entrevistas
### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

# Anexos