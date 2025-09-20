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
En este capítulo, nos centraremos en los requerimientos que necesita cumplir nuestra solución para que sea viable, y los análisis necesarios.   

## 2.1. Competidores
1. **Zebra Technologies:** Líder en trazabilidad mediante RFID, códigos de barras y soluciones IoT aplicadas a la cadena de suministro médica.
2. **LogiTag Medical Solutions:** Proveedor de sistemas de RFID e IoT para control de stock y monitorización de cadenas de frío en hospitales y laboratorios.
3. **Siemens Healthineers:** Ofrece sistemas integrados para hospitales que incluyen gestión de suministros y equipos médicos con trazabilidad.

### 2.1.1. Análisis competitivo
<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Identificar las características, fortalezas y debilidades de los competidores en el sector salud (gestión de inventarios con IoT) para resaltar el valor diferenciador de MediTrack.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realiza con el fin de detectar oportunidades de innovación y construir ventaja competitiva frente a soluciones ya consolidadas en el mercado global.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        Zebra Technologies
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/competitorsLogo/zebra.jpg" alt="Zebra" width="120px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        LogiTag Medical Solutions
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/competitorsLogo/logitag.png" alt="LogiTag" width="120px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        Siemens Healthineers
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/competitorsLogo/siemens.png" alt="Siemens" width="120px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        MediTrack (nuestra solución)
        <br>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td valign="top">Soluciones globales de trazabilidad mediante RFID y códigos de barras aplicadas a cadena de suministro médico.</td>
    <td valign="top">Proveedor especializado en RFID e IoT para inventarios hospitalarios y monitoreo de cadena de frío.</td>
    <td valign="top">Corporación multinacional con soluciones integradas de gestión hospitalaria y equipos médicos conectados.</td>
    <td valign="top">Plataforma IoT enfocada en administración inteligente de inventarios médicos delicados, con reportes predictivos y adaptables a hospitales medianos y grandes.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td valign="top">Liderazgo global en rastreo y trazabilidad con alta precisión. Amplia adopción en diferentes industrias.</td>
    <td valign="top">Alta especialización en salud, fuerte enfoque en cadena de frío y stock crítico hospitalario.</td>
    <td valign="top">Integración completa con sistemas hospitalarios y reputación mundial en tecnología médica.</td>
    <td valign="top">Agilidad, flexibilidad y costo-eficiencia, pensado específicamente para optimizar procesos hospitalarios locales y regionales con escalabilidad modular.</td>
  </tr>
  <tr>
    <td rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td valign="top">Hospitales y distribuidores globales que requieren trazabilidad avanzada en logística médica.</td>
    <td valign="top">Hospitales, clínicas y laboratorios que requieren control estricto de medicamentos sensibles.</td>
    <td valign="top">Hospitales de gran escala y sistemas de salud con alto presupuesto que buscan digitalización total.</td>
    <td valign="top">Hospitales, clínicas y laboratorios en mercados emergentes que buscan eficiencia, menor coste y cumplimiento normativo sin inversiones masivas.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td valign="top">Reputación global, marketing B2B y relaciones con grandes distribuidores.</td>
    <td valign="top">Enfoque en clientes hospitalarios de nicho; ventas directas en el sector salud.</td>
    <td valign="top">Branding global respaldado por Siemens y alianzas con gobiernos y aseguradoras de salud.</td>
    <td valign="top">Marketing directo a hospitales y clínicas regionales, demostraciones de ROI, alianzas con entidades de salud pública y privada.</td>
  </tr>
  <tr>
    <td rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td valign="top">Hardware de rastreo RFID/códigos, software de trazabilidad logística multi-industria.</td>
    <td valign="top">Sistemas IoT especializados en salud, con control de cadena de frío y stock hospitalario crítico.</td>
    <td valign="top">Portafolio amplio que integra desde diagnóstico hasta logística hospitalaria.</td>
    <td valign="top">Software IoT escalable con dashboards inteligentes, alertas, analítica predictiva e integración ERP/HCE.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td valign="top">Costos altos, enfoque corporativo global.</td>
    <td valign="top">Costos medios-altos, especializado para hospitales de gran capacidad.</td>
    <td valign="top">Muy altos, soluciones premium para sistemas hospitalarios robustos.</td>
    <td valign="top">Precios competitivos y flexibles, orientado a optimizar el retorno de inversión. Ideal para instituciones medianas y grandes con restricciones presupuestales.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">Web y móvil con fuerte soporte de hardware RFID.</td>
    <td valign="top">Web con aplicaciones específicas en entorno hospitalario, soporte de hardware.</td>
    <td valign="top">Sistemas integrados dentro de infraestructura hospitalaria, con soporte en software y hardware.</td>
    <td valign="top">Plataforma web y móvil de fácil integración, acceso remoto y escalabilidad modular.</td>
  </tr>
  <tr>
    <td rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Análisis de fortalezas, debilidades, oportunidades y amenazas de cada competidor con respecto a MediTrack.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td valign="top">Liderazgo global, experiencia en trazabilidad multi-industria.</td>
    <td valign="top">Especialización en sector salud, fuerte control de cadena de frío.</td>
    <td valign="top">Integración hospitalaria completa y marca de prestigio mundial.</td>
    <td valign="top">Agilidad, costos más bajos, diseño específico para mercados emergentes con dashboards predictivos.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td valign="top">Poca personalización para hospitales pequeños y medianos.</td>
    <td valign="top">Presencia geográfica limitada; costos que excluyen a mercados emergentes.</td>
    <td valign="top">Soluciones costosas y complejas, difícil adopción por instituciones con bajo presupuesto.</td>
    <td valign="top">Marca nueva, menor reconocimiento internacional frente a gigantes globales.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td valign="top">Expansión en sector salud en países en desarrollo.</td>
    <td valign="top">Mayor demanda de control de cadena de frío tras la pandemia.</td>
    <td valign="top">Gobiernos digitalizando sistemas de salud; alianzas globales.</td>
    <td valign="top">Demanda creciente en hospitales medianos y públicos que buscan eficiencia, digitalización y cumplimiento normativo a bajo costo.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td valign="top">Competidores especializados en salud con mayor personalización.</td>
    <td valign="top">Gigantes globales con mayor alcance y respaldo financiero.</td>
    <td valign="top">Soluciones más ágiles y económicas que disputen mercado emergente.</td>
    <td valign="top">Alta competencia y barreras de adopción tecnológica; necesidad de demostrar rápido ROI.</td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategia 1: Diferenciación mediante especialización en monitoreo en tiempo real**  
Tácticas:  
- Incorporar sensores IoT avanzados para monitorear temperatura, humedad y ubicación con precisión superior a la competencia.  
- Desarrollar una plataforma intuitiva con alertas automáticas y reportes personalizados que faciliten la toma de decisiones rápidas.  
- Garantizar integración fluida con sistemas hospitalarios existentes (ERP, HCE) para minimizar la resistencia al cambio.  

**Estrategia 2: Competitividad en costo y escalabilidad**  
Tácticas:  
- Ofrecer modelos modulares y escalables adaptados a hospitales de diferentes tamaños y presupuestos, desde clínicas pequeñas hasta grandes hospitales.  
- Implementar una estructura de precios competitiva que permita retornos de inversión claros y medibles para las instituciones de salud.  
- Brindar opciones de implementación por fases para facilitar la adopción progresiva y reducir barreras económicas.  

**Estrategia 3: Fortalecimiento de la relación con clientes y usuarios finales**  
Tácticas:  
- Desarrollar un servicio de atención al cliente especializado, con soporte técnico rápido y capacitación continua para el personal hospitalario.  
- Crear programas de fidelización y acompañamiento que refuercen la confianza en la solución y fomenten el uso constante.  
- Realizar talleres y webinars enfocados en la optimización del uso del sistema y las mejores prácticas en la gestión de inventarios delicados.  

**Estrategia 4: Innovación continua y adaptación del producto**  
Tácticas:  
- Establecer un equipo de innovación que monitoree tendencias tecnológicas y regulatorias para asegurar actualización constante del producto.  
- Reactivar ciclos de retroalimentación con usuarios para incorporar mejoras y nuevas funcionalidades basadas en sus necesidades reales.  
- Investigar alianzas estratégicas con startups HealthTech para complementar la oferta con tecnologías emergentes.  

**Estrategia 5: Marketing enfocado en valor y resultados medibles**  
Tácticas:  
- Comunicar claramente los beneficios en ahorro de costos, seguridad del paciente y cumplimiento normativo a través de casos de éxito y evidencias concretas.  
- Participar en ferias, congresos y eventos del sector salud para posicionar la marca como referente en gestión inteligente de inventarios médicos.  
- Generar contenido educativo y técnico que demuestre expertise y diferencie la solución frente a competidores globales.  

Estas estrategias y tácticas buscan posicionar la solución como una alternativa innovadora, accesible y confiable que atienda las necesidades específicas de los clientes hospitalarios, superando tanto las limitaciones de costo como las barreras tecnológicas y operativas que presentan los competidores actuales.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
En esta parte se registran las preguntas empleadas durante las entrevistas, incluyendo tanto aquellas de carácter general que aplican a todos los segmentos objetivo como las formuladas específicamente para cada uno de ellos.

#### **Preguntas Generales**

1. ¿Cuál es tu nombre?
2. ¿Qué edad tienes?
3. ¿Dónde vives actualmente?
4. ¿A qué te dedicas especificamenente dentro de tu rubro?

#### **Preguntas segmento 1**: Trabajadores del sector salud

1. ¿Cuál es su rol específico dentro de su institución?

2. ¿Cuáles son los principales retos que enfrentan actualmente para controlar y garantizar la conservación de insumos delicados, como medicamentos de cadena de frío o material quirúrgico?

3. ¿Qué tecnologías o métodos utilizan actualmente para monitorear las condiciones de almacenamiento y asegurar la trazabilidad?

4. ¿Con qué frecuencia se presentan pérdidas o desabastecimientos de insumos importantes y cómo impactan en la atención al paciente?

5. ¿Qué beneficios cree que aportaría una solución basada en IoT que monitoree en tiempo real la temperatura, humedad y ubicación de los insumos?

6. ¿Cuáles serían las principales dificultades para implementar una solución tecnológica nueva en su institución, y qué apoyo necesitarían?

7. ¿Qué tan importante considera para su institución contar con reportes automáticos y alertas que faciliten la toma de decisiones en la gestión del inventario?

### 2.2.2. Registro de entrevistas
A continuación, se documentaron todas las entrevistas llevadas a cabo para nuestra solución, organizadas por segmento objetivo y acompañadas de un resumen que resalta las observaciones y comentarios relevantes sobre el proyecto.

#### **Segmento 1: Estudiantes Universitarios**

**Entrevista 1:**

- **Nombres:** Ernie Fabian
- **Apellidos:** Cossio Soto
- **Edad:** 29
- **Lugar de residencia:** Miraflores, Lima

**Evidencia de la entrevista:**  

<img src="assets/images/interviews/ErnieEntrevista.png" alt="Ernie Entrevista">


**Enlace de la entrevista:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213404_upc_edu_pe/EZyZXwQjGWFAvmQgLvIn82sB4XdvL7Qtspq4vkSbumW2Hg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=4SyDhX](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213404_upc_edu_pe/EZyZXwQjGWFAvmQgLvIn82sB4XdvL7Qtspq4vkSbumW2Hg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=4SyDhX)

**Resumen de la entrevista:**  
Durante la entrevista, Ernie Cossio se presentó como un profesional enfocado en la innovación en el sector salud, especialmente en la mejora de la gestión de inventarios médicos mediante tecnologías avanzadas. Su trabajo se centra en optimizar el control de insumos críticos en hospitales y clínicas, utilizando IoT para mejorar la trazabilidad, conservación y disponibilidad de estos.

En cuanto a su rol, explicó que se dedica a validar y mejorar los procesos en la gestión de insumos, identificando puntos críticos y proponiendo soluciones tecnológicas. Destacó los principales desafíos del sector, como la falta de monitoreo en tiempo real, la dependencia de registros manuales, y la dificultad para anticipar desabastecimientos y pérdidas por vencimiento o deterioro.

En relación con los métodos actuales, mencionó que muchos centros de salud aún utilizan hojas de cálculo o sistemas básicos, con poca integración y capacidades limitadas de trazabilidad. La frecuencia de pérdidas y desabastecimientos es alta, lo que impacta negativamente en la seguridad del paciente, la continuidad de los tratamientos y los costos.

Al evaluar una solución basada en IoT, resaltó sus beneficios como el monitoreo en tiempo real, la reducción de pérdidas, y la mejora de la trazabilidad, lo que facilita la toma de decisiones. Sin embargo, identificó desafíos como la inversión inicial, la capacitación del personal y la integración con sistemas existentes, sugiriendo que el apoyo necesario incluye soporte técnico y formación. Finalmente, destacó la importancia de los reportes automáticos y las alertas, ya que permiten una gestión preventiva y aseguran la disponibilidad de insumos en condiciones óptimas para una mejor atención al paciente.

**Entrevista 2:**

- **Nombres:** xxxxxxxxxx
- **Apellidos:** xxxxxxxxxx
- **Edad:** xxxxxxxxxx
- **Lugar de residencia:** xxxxxxxxxx, xxxxxxxxxx

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/>

**Enlace de la entrevista:** []()
**Resumen de la entrevista:**  
xxxxxxxxxx

**Entrevista 3:**

- **Nombres:** xxxxxxxxxx
- **Apellidos:** xxxxxxxxxx
- **Edad:** xxxxxxxxxx
- **Lugar de residencia:** xxxxxxxxxx, xxxxxxxxxx

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/>

**Enlace de la entrevista:** []()
**Resumen de la entrevista:**  
xxxxxxxxxx

### 2.2.3. Análisis de entrevistas
Para finalizar, en la sección de análisis se utilizaron métricas derivadas de las respuestas obtenidas, así como la frecuencia con la que ciertos temas fueron mencionados durante las entrevistas.

#### **Análisis de Preguntas Generales**

XXXXXXXXXXXXXXXXX

#### **Análisis de Preguntas Especificas**

XXXXXXXXXXXXXXXXX


## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Product Backlog

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