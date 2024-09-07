# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 7mo Ciclo</strong><br>
    <strong>Desarrollo de Soluciones IOT</strong><br>
    <strong>SW74</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez</strong><br>
    <br><strong>INFORME DE TRABAJO FINAL</strong><br>
    <br><strong>Digital Dart</strong><br>
    <strong>Nombre del Producto</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Castillo Robles, Steve Roger</td>
            <td>U202121679</td>
        </tr>
        <tr>
            <td>Castro Soto, Diego Mauricio</td>
            <td>U202216636</td>
        </tr>
        <tr>
            <td>Espinoza Quispe, Jennifer Mary</td>
            <td>U202120911</td>
        </tr>
        <tr>
            <td>Esquivel Aguayo, Diego Martin</td>
            <td>U202116749</td>
        </tr>
        <tr>
            <td>Quito Igreda, Cristian Andrés</td>
            <td>U202121882</td>
        </tr>
    </table>
</div>

# Registro de Versiones del Informe

<table>
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
    <tr>
        <td rowspan="25">TB1</td>
        <td rowspan="5">Mes/Año</td>
        <td>Steve Roger Castillo Robles</td>
        <td>Descripción de las modificaciones realizadas en esta versión.</td>
    </tr>
    <tr>
        <td>Diego Mauricio Castro Soto</td>
        <td>Descripción de las modificaciones realizadas en esta versión.</td>
    </tr>
    <tr>
        <td>Jennifer Mary Espinoza Quispe</td>
        <td>Descripción de las modificaciones realizadas en esta versión.</td>
    </tr>
    <tr>
        <td>Diego Martin Esquivel Aguayo</td>
        <td>Descripción de las modificaciones realizadas en esta versión.</td>
    </tr>
    <tr>
        <td>Cristian Andrés Quito Igreda</td>
        <td>Descripción de las modificaciones realizadas en esta versión.</td>
    </tr>
</table>
<br><br>

# Project Report Collaboration Insights

<br>

# Contenido

## Tabla de Contenidos

### [Registro de Versiones del Informe](#registro-de-versiones-del-informe)

### [Project Report Collaboration Insights](#project-report-collaboration-insights)

### [Contenido](#contenido)

### [Student Outcomes](#student-outcome)

### [Capítulo I: Introducción](#capítulo-i-introducción)

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

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)

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
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solution Software Design](#capc3adtulo-iv-solution-software-design)

- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. Event Storming](#411-event-storming)
    - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
    - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
    - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.X. Bounded Context: Bounded Context Name](#42x-bounded-context-bounded-context-name)
    - [4.2.X.1. Domain Layer](#42x1-domain-layer)
    - [4.2.X.2. Interface Layer](#42x2-interface-layer)
    - [4.2.X.3. Application Layer](#42x3-application-layer)
    - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
    - [4.2.X.6. Bounded Context Software Architecture Component Level Diagrams](#42x6-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.X.7. Bounded Context Software Architecture Code Level Diagrams](#42x7-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.7.1. Bounded Context Domain Layer Class Diagrams](#42x71-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.7.2. Bounded Context Database Design Diagram](#42x72-bounded-context-database-design-diagram)

### [Capítulo V: Solution UI/UX Design](#capc3adtulo-v-solution-uiux-design)

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
  - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

### [Capítulo VI: Product Implementation, Validation & Deployment](#capc3adtulo-vi-product-implementation-validation--deployment)

### [Conclusiones](#conclusiones)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET – EAC - Student Outcome 5**
**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

<!-- Cambiamos el rowspan="1" por rowspan="n" cuando agregamos más de una acción realizada por criterio específico. (TB1, TP1, TB2, TF1)-->
<table>
    <tr>
        <th><b>Criterio específico</b></th>
        <th><b>Acciones realizadas</b></th>
        <th><b>Conclusiones</b></th>
    </tr>
    <tr>
        <td rowspan="1"><b>
            Trabaja en equipo para proporcionar liderazgo en forma conjunta </b></td>
        <td>TB1<br><br>
            <b>Steve Roger Castillo Robles </b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br> 
            <b>Diego Mauricio Castro Soto</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Jennifer Mary Espinoza Quispe</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Diego Martin Esquivel Aguayo</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Cristian Andrés Quito Igreda</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
        </td>
        <td>TB1<br><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
        </td>
    </tr>
    <tr>
        <td rowspan="1"><b>
            Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</b></td>
        <td>TB1<br><br>
            <b>Steve Roger Castillo Robles </b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br> 
            <b>Diego Mauricio Castro Soto</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Jennifer Mary Espinoza Quispe</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Diego Martin Esquivel Aguayo</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
            <b>Cristian Andrés Quito Igreda</b><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
            <br><br>
        </td>
        <td>TB1<br><br>
            - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies. Nullam nec purus nec nunc ultricies ultricies.
        </td>
    </tr>
</table>

# Capítulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Descripción de la StartUp

**DigitalDart** es una empresa emergente de tecnología especializada en desarrollar soluciones IoT innovadoras para la seguridad y protección familiar. Nos enfocamos en crear dispositivos inteligentes que faciliten la monitorización y seguridad de personas vulnerables, como personas mayores con Alzheimer y niños pequeños. Nuestra misión es mejorar la seguridad familiar mediante herramientas tecnológicas avanzadas que ofrezcan monitoreo en tiempo real y alertas de seguridad.

### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="./images/chapter-01/profile-pics/steve_rogers.png" alt="Steve Castillo" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Steve Roger Castillo Robles, estudiante de Ingeniería de Software con una pasión por las nuevas tecnologías. Tengo habilidades en Angular, Vue, Spring Boot, bases de datos como Mysql, PostgreSQL. Además, utilizo Git y GitHub para la gestión eficiente de mis proyectos de manera eficiente. Siempre estoy buscando oportunidades para aplicar y expandir mis conocimientos en proyectos reales. Mi objetivo es utilizar mis habilidades y educación para contribuir de manera significativa en el campo de la tecnología.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="./images/chapter-01/profile-pics/diego_castro.png" alt="Diego Castro" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Diego Mauricio Castro Soto
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Diego Castro, me considero alguien autodidacta a quién le gusta siempre aprender nuevas cosas leyendo diversos recursos en la web, ya sea investigando en foros, leyendo libros o a través de videos. Desde ya hace un tiempo me encuentro adquiriendo nuevos conocimientos de diversos lenguajes de programación como C, C++ y C#. Adicional a esto me encuentro sumamente interesado en ahondar en las ramas del desarrollo de videojuegos, la seguridad informática y el desarrollo de aplicaciones web.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="./images/chapter-01/profile-pics/jennifer_espinoza.png" alt="Jennifer Espinoza" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Jennifer Mary Espinoza Quispe
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Jennifer Espinoza, me encuentro en el 7mo ciclo de la carrera de Ing. de Software. En lo personal, me agrada aprender cosas nuevas, como nuevos lenguajes de programación e idiomas. Actualmente manejo el lenguaje de C++, un poco de Python y TypeScript. A nivel de desarrollo web conozco frameworks como Angular y Sprint Boot. Me considero una persona creativa, responsable y paciente, habilidades que ayudarán en el presente proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="./images/chapter-01/profile-pics/diego_esquivel.png" alt="Diego Esquivel" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Diego Martin Esquivel Aguayo
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Diego Esquivel, tengo 20 años, me encuentro en el séptimo ciclo de Ingeniería de Software. Soy una persona amigable, tranquila, responsable y ordenada. Cumplo con entregar los trabajos en los plazos establecidos y me adapto fácilmente a las condiciones del trabajo en equipo y a los nuevos lenguajes de programación. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/cristian.jpg" alt="Cristian Quito" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Cristian Andrés Quito Igreda
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Cristian Andrés Quito Igreda y estoy estudiando la carrera de Ingeniería de Software en la UPC. La razón principal por la que escogí esta carrera es porque desde mis inicios de la secundaria me causó curiosidad el funcionamiento interno de las aplicaciones de escritorio y web como también el desarrollo de grandes proyectos de software. Entre mis principales habilidades destaca la responsabilidad, el trabajo en equipo y el pensamiento lógico para la resolución de problemas. Finalmente, poseo conocimientos intermedios en C++, Python y SQL Server, además de contar con experiencia en Git, GitHub, PostgreSQL y MongoDB.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

## 1.2.1. Antecedentes y problemática

El cuidado de personas vulnerables, como los mayores con Alzheimer y los niños pequeños, presenta desafíos importantes en cuanto a su seguridad. Estos grupos son especialmente susceptibles a situaciones peligrosas si no se monitorean adecuadamente. La falta de soluciones tecnológicas accesibles y efectivas puede poner en riesgo su bienestar, lo que genera preocupación en sus cuidadores y familiares.

Según el Informe Mundial sobre el Alzheimer 2023, aproximadamente el 60% de las personas que padecen Alzheimer deambulan al menos una vez, lo que puede resultar en situaciones peligrosas si no se detectan a tiempo. De manera similar, los niños pequeños, al ser curiosos por naturaleza, pueden fácilmente salir de áreas seguras, lo que requiere una supervisión constante y efectiva.

**GuardianArea** es una solución diseñada para enfrentar estos desafíos, ofreciendo una pulsera con rastreador que permite establecer geo-cercas y recibir notificaciones en tiempo real si la persona monitoreada o el niño salen de las zonas seguras, asegurando su protección y brindando tranquilidad a los cuidadores y familiares.


### What (¿Qué?)

El principal problema identificado es la dificultad de monitorear a personas vulnerables, como los mayores con Alzheimer y los niños pequeños, lo que puede llevar a situaciones de riesgo si no se detectan a tiempo.

### When (¿Cuándo?)

El problema surge cuando estas personas salen de áreas seguras, lo que puede ocurrir en cualquier momento si no se supervisa adecuadamente.

### Where (¿Dónde?)

El problema se identifica en entornos familiares, centros de atención y espacios públicos, donde estas personas son más propensas a deambular sin supervisión.

### Who (¿Quién?)

Este problema afecta a los cuidadores y familiares de personas con Alzheimer y niños pequeños, quienes tienen la responsabilidad de garantizar su seguridad.

### Why (¿Por qué?)

La causa principal es la falta de herramientas de monitoreo en tiempo real que permitan detectar y alertar sobre la salida de las zonas seguras, lo que pone en riesgo la seguridad de estas personas.

### How (¿Cómo?)

La solución propuesta es **GuardianArea**, una pulsera con rastreador que permite establecer geo-cercas y recibir notificaciones en tiempo real si la persona monitoreada o el niño salen de las zonas seguras.

### How much (¿Cuánto?)

Este problema tiene un impacto significativo en la seguridad y bienestar de las personas vulnerables. El uso de **GuardianArea** podría reducir el riesgo de situaciones peligrosas en un 70% dentro de los primeros seis meses de implementación.

## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

El cuidado de personas mayores con Alzheimer y niños pequeños presenta desafíos significativos para garantizar su seguridad debido a la falta de herramientas efectivas de monitoreo. Estas personas vulnerables están en riesgo de situaciones peligrosas, como el deambular o salir de áreas seguras sin ser detectados.

La ausencia de soluciones tecnológicas accesibles y efectivas exacerba estos riesgos, poniendo en peligro la vida y el bienestar de estos individuos.

¿Cómo podemos mejorar la seguridad de personas mayores con Alzheimer y niños pequeños mediante un sistema de monitoreo en tiempo real que alerte a sus cuidadores y familiares cuando se salen de las zonas seguras?

### 1.2.2.2. Lean UX Assumptions

**Features:**

- Monitoreo en tiempo real mediante geo-cercas.
- Alertas automáticas cuando la persona monitoreada sale de la zona segura.
- Acceso a un historial de movimientos para análisis y prevención.

**Business outcomes:**

- Incremento en la adopción del sistema por parte de familias y centros de cuidado.
- Generación de ingresos mediante la venta de pulseras y suscripciones a servicios de monitoreo.
- Expansión geográfica y diversificación en otros segmentos vulnerables.

**Users:**

- Cuidadores y familiares de personas mayores con Alzheimer.
- Cuidadores y familiares de niños pequeños.

**Users outcomes:**

- Mejora en la seguridad y bienestar de personas vulnerables.
- Reducción en los niveles de ansiedad y estrés en cuidadores y familiares. 
- Mayor tranquilidad al saber que pueden reaccionar rápidamente ante cualquier emergencia.

### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:** Creemos que, al proporcionar un sistema de monitoreo en tiempo real para personas vulnerables, mejoraremos su seguridad y bienestar. Sabremos que hemos tenido éxito cuando veamos una reducción del 70% en incidentes relacionados con la salida de zonas seguras dentro de los primeros seis meses de implementación.

**Hipótesis 2:** Creemos que al ofrecer alertas automáticas cuando la persona monitoreada sale de la zona segura, los cuidadores podrán reaccionar rápidamente para evitar situaciones peligrosas. Sabremos que hemos tenido éxito si el 95% de las alertas son atendidas en un plazo de 10 minutos, evitando cualquier riesgo significativo.

**Hipótesis 3:** Creemos que, al permitir el acceso al historial de movimientos, los cuidadores podrán prever posibles situaciones de riesgo. Sabremos que hemos tenido éxito si el 80% de los usuarios utiliza esta función para ajustar las zonas seguras dentro de los primeros tres meses.

**Hipótesis 4:** Creemos que al incorporar un sistema de geo-cercas personalizable en tiempo real, los cuidadores podrán adaptar rápidamente las áreas seguras. Sabremos que hemos tenido éxito cuando el 90% de los usuarios ajusten las zonas al menos una vez al mes.

**Hipótesis 5:** Creemos que, al integrar un sistema de notificaciones por voz, los cuidadores tendrán una respuesta más rápida. Sabremos que hemos tenido éxito si el 85% de los usuarios considera útil esta característica.

**Hipótesis 6:** Creemos que, al implementar un historial de alertas con recomendaciones automatizadas, los cuidadores podrán anticiparse a situaciones de riesgo. Sabremos que hemos tenido éxito si el 75% de los cuidadores encuentran las recomendaciones útiles para la prevención.

### 1.2.2.4. Lean UX Canvas

<div style="text-align: center;">
    <img src="./images/chapter-01/lean-ux-canvas.png" alt="Lean Ux Canvas">
</div>

## 1.3. Segmentos objetivo

**Segmento objetivo 1: Cuidadores o Familiares de personas con Alzheimer**  
Este segmento se enfoca en los cuidadores y familiares de personas con Alzheimer que necesitan monitorear de cerca a estos pacientes para garantizar su seguridad. Buscan herramientas que les permitan reaccionar rápidamente ante situaciones peligrosas y mantener la tranquilidad de saber que sus seres queridos están seguros.

**Segmento objetivo 2: Cuidadores o Familiares de niños pequeños**  
Este segmento incluye a los cuidadores y familiares de niños pequeños que desean aumentar la seguridad y supervisión de los niños. Están interesados en soluciones que les permitan prevenir situaciones peligrosas al recibir alertas cuando los niños salen de las zonas seguras establecidas.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Luego de realizar una investigación en el mercado IOT, hemos hallado tres portales que ofrecen características similares a la de GuardianArea, por eso son considerados como potenciales competidores. Estos competidores son:

1. **Angel Sense**: Dispositivo de rastreo GPS diseñado específicamente para la seguridad de niños, personas con necesidades especiales y adultos mayores. Ofrece funcionalidades como alertas de geocercas, monitoreo en tiempo real y comunicación directa con el usuario a través de una aplicación móvil.

<div style="text-align: center;">
    <img src="./images/chapter-02/angel-sense-logo.svg" alt="Angel Sens" style="max-width: 400px; width: 30%;">
</div>

2. **Theora Care**: Proporciona soluciones de monitoreo dirigidas a personas mayores, especialmente aquellas con Alzheimer. Su plataforma incluye sensores de actividad, rastreo GPS y herramientas para detectar comportamientos inusuales.
 
<div style="text-align: center;">
    <img src="./images/chapter-02/theora-care-logo.png" alt="Theora Care" style="max-width: 400px; width: 30%">
</div>

3. **Revolutionary Tracker**: Dispositivo portátil que combina el rastreo GPS con sensores de salud y seguridad. Su enfoque principal está en ofrecer un monitoreo integral para personas mayores, ayudando a las familias a mantener a sus seres queridos seguros y monitoreados.

<div style="text-align: center;">
    <img src="./images/chapter-02/revolutionary-tracker-logo.png" alt="Revolutionary Tracker" style="max-width: 400px; width: 30%;">
</div>

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        GuardianArea
        <br>
        <div style="text-align: center; margin-top: 10px;">
            <img src="./images/chapter-02/guardian_area_logo.svg" alt="GuardianArea" width="60px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    Theora Care
    <div style="text-align: center; margin-top: 10px">
      <img src="./images/chapter-02/theora-care-logo.png" alt="Theora Care" width="100px">
    </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
      AngelSense
      <div style="text-align: center;">
      <img src="./images/chapter-02/angel-sense-logo.svg" alt="Theora Care" width="100px">
    </div>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Revolutionary Tracker 
      <div style="text-align: center; margin-top: 10px;">
        <img src="./images/chapter-02/revolutionary-tracker-logo.png" alt="Revolutionary Tracker" width="60px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Solución avanzada de monitoreo GPS con sensores adicionales para niños y personas con Alzheimer.</td>
    <td colspan="1" valign="top">Sistema de monitoreo para personas mayores con Alzheimer, incluye sensores de actividad.</td>
    <td colspan="1" valign="top">Dispositivo de rastreo GPS enfocado en niños, personas con necesidades especiales y adultos mayores.</td>
    <td colspan="1" valign="top">Dispositivo portátil de rastreo GPS con sensores para detección de caídas y alertas.
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td colspan="1" valign="top">Monitoreo en tiempo real, detección de caídas, alertas personalizables, sensores de salud integrados y configuración de geocercas</td>
    <td colspan="1" valign="top">Monitoreo constante de actividad diaria y detección de patrones de comportamiento para evitar caídas y futuras lesiones.</td>
    <td colspan="1" valign="top">Enfoque específico en la seguridad infantil con alertas de geocercas.</td>
    <td colspan="1" valign="top">Combinación de rastreo GPS con monitoreo de salud y seguridad.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Familia con niños y familia con personas con Alzheimer</td>
    <td colspan="1" valign="top">Cuidadores y familias de personas con Alzheimer.</td>
    <td colspan="1" valign="top">Padres de niños con necesidades especiales, escuelas.</td>
    <td colspan="1" valign="top">Familias y cuidadores de personas mayores.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">GuardianArea planteará una estrategia basada en publicidad en redes sociales, colaboraciones con centros de salud, comunidades médicas y de cuidado con un enfoque en tranquilidad familiar.</td>
    <td colspan="1" valign="top">Campañas en comunidades médicas y asociaciones de Alzheimer.</td>
    <td colspan="1" valign="top">Enfoque en redes sociales y grupos de apoyo para niños con necesidades especiales.</td>
    <td colspan="1" valign="top">Publicidad en revistas de salud y bienestar, marketing digital enfocado en seguridad.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Dispositivo portátil con GPS y sensores para monitoreo de salud y seguridad. Además, plataforma digital para el monitoreo a través de un dashboard y control de sensores y configuración de geocercas.</td>
    <td colspan="1" valign="top">Monitoreo de actividad, rastreo GPS, alertas de comportamiento inusual.</td>
    <td colspan="1" valign="top">Dispositivo de rastreo GPS con alertas.</td>
    <td colspan="1" valign="top">Dispositivo portátil con GPS, sensores de caída, y monitoreo de salud.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">$150 por dispositivo, suscripción mensual entre $10 a $35</td>
    <td colspan="1" valign="top">$247.97 por dispositivo con un plan mensual de $29.97</td>
    <td colspan="1" valign="top">$229 por el dispositivo con un plan mensual de $49.99 mensuales por un plan anual. Con una tarifa de activación de $19.</td>
    <td colspan="1" valign="top">262.87 por el dispositivo</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Los canales de distribución son Página web oficial, App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son Página web oficial, App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son Página web oficial, App Store y Google Play.</td>
    <td colspan="1" valign="top">El canal de distribución es la Web</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Integración de sensores de salud y seguridad, fácil de usar, enfoque en segmentos vulnerables y genración de dashboard de indicadores.</td>
    <td colspan="1" valign="top">Comunicación directa con el usuario, accesible y fácil de usar para personas mayores.</td>
    <td colspan="1" valign="top">Diseño especializado para niños, alertas rápidas, fácil uso para padres.</td>
    <td colspan="1" valign="top">Combinación de tecnologías de seguridad y salud en un solo dispositivo.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Necesidad de suscripción mensual.</td>
    <td colspan="1" valign="top">Precio elevado y enfoque limitado a personas con Alzheimer.</td>
    <td colspan="1" valign="top">Costo mensual elevado, limitado a un solo usuario por dispositivo.</td>
    <td colspan="1" valign="top">Enfoque principal en personas mayores y sin actualizaciones constantes en sus redes.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Expansión hacia otros mercados de salud y bienestar, integración con apps de salud.</td>
    <td colspan="1" valign="top">Expansión de las funciones para otros tipos de enfermedades neurodegenerativas.</td>
    <td colspan="1" valign="top">Expansión a mercados internacionales, mejoras en la precisión del rastreo.</td>
    <td colspan="1" valign="top">Ampliación de la funcionalidad para incluir más métricas de salud.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia de dispositivos con integración de IA</td>
    <td colspan="1" valign="top">Nuevas soluciones de monitoreo basadas en IA que podrían ofrecer mejores resultados.	</td>
    <td colspan="1" valign="top">Aparición de nuevos competidores con tecnología más avanzada.</td>
    <td colspan="1" valign="top">Competencia en un mercado saturado de dispositivos de rastreo y monitoreo.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

GuardianArea implementará estrategias específicas para destacar en el mercado, nos basaremos en nuestras fortalezas y oportunidades y abordaremos las áreas de mejora necesarias:

1. **Interfaz Mejorada y Usabilidad**: Simplificaremos el diseño de la interfaz para que sea fácil de navegar, permitiendo que los usuarios configuren geocercas y reciban alertas sin complicaciones. La facilidad de uso será un diferenciador clave.

2. **Optimización del Usuario**: Usaremos datos de sensores para presentar gráficos claros en el dashboard, lo que permitirá a los usuarios interpretar rápidamente la información relevante.

3. **Retroalimentación para Mejora Continua**: Recogeremos opiniones de los usuarios y ajustaremos la plataforma según sus necesidades, asegurando que las funcionalidades evolucionen de acuerdo con sus expectativas.

4. **Marketing Específico y Alianzas Estratégicas**:Ejecutaremos campañas digitales enfocadas en familias y cuidadores, usando redes sociales y grupos especializados. Además, estableceremos alianzas con instituciones de salud para aumentar nuestra presencia en el mercado.

## 2.2. Entrevistas

### 2.2.1 Diseño de entrevistas

**Preguntas Demográficas**

- ¿Cómo te llamas?
- ¿Cuántos años tienes?
- ¿Lugar de residencia?
- Estado Civil?
- ¿A qué te dedicas actualmente?

**Preguntas sobre personalidad:**

- ¿Te consideras una persona extrovertida o introvertida? ¿Por qué?

---

### Entrevistas para Cuidadores o Familiares de Personas con Alzheimer

**Datos Demográficos**

1. ¿Cuál es su relación con la persona que padece Alzheimer?

**Preferencias y Uso de Tecnología**

1. ¿Con qué frecuencia utiliza estas tecnologías (aplicaciones móviles y aplicaciones web)?
2. ¿Utiliza actualmente algún dispositivo o tecnología para monitorear la salud o ubicación de su ser querido?
3. ¿Ha habido alguna situación en la que sintió que una tecnología podría haberle ayudado, pero no la tenía a su disposición?

**Objetivos y Motivaciones**

1. ¿Cuáles son sus principales preocupaciones en el cuidado de su ser querido con Alzheimer?
2. ¿Qué espera obtener de un sistema que monitoree en tiempo real la ubicación y salud de su ser querido?
3. ¿Le gustaría tener la posibilidad de compartir los datos del monitoreo con otros miembros de la familia o cuidadores?

**Frustraciones y Desafíos**

1. ¿Cuáles son las mayores dificultades que enfrenta en el cuidado diario de su ser querido?
2. ¿Ha enfrentado algún problema que podría haber sido resuelto con tecnología?

**Biografía**

1. ¿Cuánto tiempo lleva cuidando a su ser querido con Alzheimer?
2. ¿Cómo describiría un día típico en el cuidado de su ser querido?

**Opinión sobre la idea de negocio**

1. ¿Qué te parece la idea de nuestro proyecto? ¿Te sería útil?
2. ¿Tienes sugerencias sobre posibles mejoras o características adicionales que podríamos integrar en nuestra aplicación?

---

### Entrevistas para Cuidadores o Familiares de Niños Pequeños

**Datos Demográficos**

1. ¿Cuál es su relación con el niño que cuida?

**Preferencias y Uso de Tecnología**

1. ¿Con qué frecuencia utiliza dispositivos tecnológicos (smartphones, tablets, wearables)?
2. ¿Qué tan cómodo se siente utilizando aplicaciones móviles?
3. ¿Utiliza actualmente algún dispositivo o tecnología para monitorear la seguridad o salud de su hijo/a?
4. ¿Ha habido alguna situación en la que sintió que una tecnología podría haberle ayudado, pero no la tenía a su disposición?

**Objetivos y Motivaciones**

1. ¿Cuáles son sus principales preocupaciones en relación a la seguridad y bienestar de su hijo/a?
2. ¿Qué beneficios espera obtener de un sistema que monitoree en tiempo real la ubicación y salud de su hijo/a?
3. ¿Qué características considera más importantes en un sistema de monitoreo? (e.g., alertas, seguimiento de ubicación, monitoreo de salud, facilidad de uso, etc.)
4. ¿Le gustaría tener la posibilidad de compartir los datos del monitoreo con otros miembros de la familia o cuidadores?

**Frustraciones y Desafíos**

1. ¿Qué problemas has enfrentado en el cuidado diario de su hijo/a?
2. ¿Ha enfrentado algún problema que podría haber sido resuelto con tecnología?

**Biografía**

1. ¿Cuánto tiempo lleva cuidando a su hijo/a?
2. ¿Cómo describiría un día típico en el cuidado de su hijo/a?

**Opinión sobre la idea de negocio**

1. ¿Qué te parece la idea de nuestro proyecto? ¿Te sería útil?
2. ¿Tienes sugerencias sobre posibles mejoras o características adicionales que podríamos integrar en nuestra aplicación?

### 2.2.2 Registro de entrevistas

### Segmento 1: Cuidadores o Familiares de personas con Alzheimer

**Entrevista 01**
- Nombres: Aldo Alberto
- Apellidos: Baldeón Fabian
- Edad: 21
- Distrito: Villa María del Triunfo 
- Evidencia de la reunión: 
- Inicio: 
- Fin: 
- Enlace de entrevista:
    <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_aldo_baldeon.PNG" alt="Entrevista 01"  width="90%"/>
    </div> 
- Resumen de la entrevista: 

    Aldo Baldeón es estudiante en la UPC y se identifica como una persona introvertida. Comenta que pasa la mayor parte de su tiempo en casa estudiando y no suele salir con frecuencia. Aldo está a cargo del cuidado de su abuelo, quien padece de Alzheimer, y aunque no utiliza tecnologías avanzadas para monitorearlo, recurre a aplicaciones básicas como WhatsApp para sus estudios y comunicación.

    Aldo expresó sus principales preocupaciones respecto al bienestar de su abuelo, que incluyen la confusión, desorientación y el riesgo de que se escape de casa, además de la necesidad constante de asistencia para sus necesidades básicas. Estos factores le generan mucho estrés en su día a día.

    Un sistema de monitoreo en tiempo real le resultaría muy útil, especialmente uno que pueda alertarlo si su abuelo sale de los límites de su hogar, facilitando su búsqueda en caso de que se pierda.

    Aldo comparte la responsabilidad del cuidado de su abuelo con una prima, turnándose los fines de semana y durante la semana. Entre sus tareas diarias destacan alimentarlo, bañarlo y mantenerlo entretenido mediante la conversación.

    Finalmente, Cristian presentó la idea de Biocercos, un proyecto de sistema de monitoreo que podría definir áreas específicas y emitir alertas sobre la ubicación y estado de salud del paciente. Aldo consideró que este proyecto sería de gran utilidad, destacando que la capacidad de recibir alertas sobre la ubicación de su abuelo sería una característica esencial.

**Entrevista 02**
- Nombres: Adrián Martín
- Apellidos: Quito Igreda
- Edad: 20
- Distrito: Los Olivos
- Evidencia de la reunión:
    <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_adrian_quito.PNG" alt="Entrevista 01"  width="90%"/>
    </div>  
- Inicio: 
- Fin: 
- Enlace de entrevista: 
- Resumen de la entrevista:

  Adrián Martín Quito es estudiante de Ingeniería Electrónica en la UPC y se describe como una persona introvertida. Vive en Los Olivos y está a cargo del cuidado de su abuela, quien padece de Alzheimer. Aunque utiliza aplicaciones móviles y web diariamente, Adrián no emplea dispositivos específicos para monitorear a su abuela, prefiriendo un enfoque más tradicional y constante en su cuidado.

  Entre sus principales preocupaciones se encuentran los riesgos cotidianos a los que su abuela podría estar expuesta, como abrir la puerta a extraños o olvidar apagar electrodomésticos. La posibilidad de volver a clases presenciales aumenta su preocupación por la seguridad de su abuela. Adrián cree que una aplicación que monitoree en tiempo real la ubicación y el estado de su abuela sería muy útil.

  En su rutina diaria, Adrián enfrenta desafíos como que su abuela a veces no lo reconoce o tiene dificultades para realizar tareas de manera independiente. Aunque esta situación ha afectado sus estudios, Adrián dedica más tiempo al cuidado de su abuela, priorizando su seguridad por encima de otras responsabilidades.

  Adrián ha estado en esta situación durante aproximadamente cuatro meses, desde que la condición de su abuela se agravó. Aunque lo encuentra desafiante, está dispuesto a adaptarse y explorar nuevas soluciones que puedan mejorar la calidad de vida de su abuela y reducir el estrés del cuidado.

  Finalmente, Adrián considera que un sistema de geo-cerca sería una solución ideal para monitorear a su abuela. Además, sugiere que la inclusión de una cámara que se active al recibir una alarma ayudaría a verificar si su abuela está en peligro, brindando una mayor sensación de seguridad y tranquilidad.

**Entrevista 03**
- Nombres: Piero Alessandro
- Apellidos: Descalzi Saenz
- Edad: 21
- Distrito: Breña
- Evidencia de la reunión:
   <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_piero_descalzi.png" alt="Entrevista 03"  width="90%"/>
    </div> 
- Inicio: 
- Fin: 
- Enlace de entrevista: 
- Resumen de la entrevista: 

    Durante la entrevista, recibí a Piero Descalci, un diseñador de videojuegos de 21 años que vive en Lima, Breña, y que se describe como una persona introvertida. Piero me comentó que prefiere pasar tiempo en casa con su familia, especialmente ahora que su primo Campos, diagnosticado conDu Alzheimer hace unos años, necesita más atención.

    Piero utiliza aplicaciones móviles y páginas web diariamente para coordinar citas médicas y gestionar las tareas del cuidado de su primo. Me confesó que la seguridad es su principal preocupación, ya que teme que Campos se pierda o enfrente problemas de salud sin que puedan intervenir a tiempo.

    El desgaste emocional ha sido una de las mayores dificultades para Piero, quien compartió conmigo momentos realmente angustiosos, como cuando su primo se perdió, lo que resultó en situaciones aterradoras y en un sentimiento constante de no estar haciendo lo suficiente. Me contó que en varias ocasiones la tecnología podría haber sido de gran ayuda, como cuando su primo se alejó de casa y no contaban con un dispositivo que los alertara. Esto los hizo perder mucho tiempo buscándolo, deseando tener alguna herramienta que pudiera ayudarlos en esos momentos críticos.

    Le hablé del desarrollo en el que estamos trabajando: una pulsera con rastreador que notifica si una persona con Alzheimer o un niño pequeño sale de un área delimitada. Piero consideró que esta idea sería de gran utilidad para ofrecer mayor seguridad y tranquilidad a las familias y cuidadores.

    Finalmente, Piero sugirió algunas mejoras para la aplicación, como la capacidad de enviar alertas a varios miembros de la familia simultáneamente y la posibilidad de monitorear más parámetros de salud, como el ritmo cardíaco o la presión arterial. Le agradecí por su participación y concluimos la entrevista.

---

### Segmento 2: Cuidadores o Familiares de niños pequeños

**Entrevista 01**
- Nombres: Natalia Jimena 
- Apellidos: La Rosa Marcos
- Edad: 24
- Distrito: Bellavista 
- Evidencia de la reunión: 
    <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_natalia_larosa.jpg" alt="Entrevista 01"  width="90%"/>
    </div> 
- Inicio: 
- Fin: 
- Enlace de entrevista: 
- Resumen de la entrevista: 

    Natalia La Rosa tiene 24 años y es egresada de la carrera de ingeniería biomédica. Ella cuida a su hermano pequeño regularmente. Se considera una persona muy introvertida, especialmente en situaciones que incluyen a extraños. Josué usa dispositivos tecnológicos ocasionalmente para rastrear su estudio, y para monitorear la cámara de su hogar, pero no utiliza tecnología como sensores de monitoreo para cuidar a su hermano.

    José dijo que no tener a un adulto presente para cuidar de su hermano, ya que su madre está trabajando, es la razón por la que está realmente preocupado por su hermano. Opina que una aplicación que lleve a cabo la vigilancia con acciones a control remoto sería una buena manera de cuidar a su hermano en situaciones críticas, como verse obligado a quedarse solo en casa. Además, le gustaría poder controlar las cámaras desde más de un dispositivo y cree que un sistema que no solo le permita vigilar, sino también intervenir en caso de una emergencia sería de un valor inestimable para él.

    José siente que una aplicación como GuardianArea sería lo que el doctor ordenó en su caso, ya que no solo le permitiría estar en paz a través de vigilar y proteger a su hermano de una manera más competente, sino también de estar mejor equipado para intervenir en caso de una emergencia.

**Entrevista 02**
- Nombres: Angie Beverly
- Apellidos: Zavaleta Quispe
- Edad: 28
- Distrito: Rímac 
- Evidencia de la reunión: 
    <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_angie_zavaleta.png" alt="Entrevista 01"  width="90%"/>
    </div> 
- Inicio: 
- Fin: 
- Enlace de entrevista: 
- Resumen de la entrevista: 
  
  Angie Zavaleta Quispe, de 28 años, trabaja en el area de recursos humanos y vive en el Rímac. Ella se considera introvertida, especialmente con personas nuevas, aunque se siente más cómoda con quienes ya conoce. Angie se ocupa del cuidado de su hermana pequeña de 9 años, quien es bastante hiperactiva, ello le genera preocupación, especialmente cuando están fuera de casa.
  
  Actualmente, Angie no emplea dispositivos de monitoreo, pero la idea de un sistema que le permita verificar la ubicación de su hermana en tiempo real le resulta atractiva. Angie contó una experiencia, donde su hermana se perdió en un mercado, lo que preocupó a su familia y le generó la necesidad de controlar la ubicación de su hermana cuando sale.
  
  Angie comenta que durante los fines de semana, ella y su hermana disfrutan de salir a parques, lo que resalta la necesidad de vigilar constantemente a su hermana debido a su hiperactividad. GuardianArea sería ideal para ellas, facilitando este monitoreo constante de manera efectiva.
  
  En resumen, Angie ve un gran valor con **GuaridianArea** que puede ofrecerle tranquilidad y seguridad al saber que puede monitorear la ubicación de su hermana en tiempo real y recibir alertas si sale de una zona segura.

**Entrevista 03**
- Nombres: José Carlos Isaac
- Apellidos: Ampudia Flores
- Edad: 20
- Distrito: Monterrico
- Evidencia de la reunión: 
    <div align=center>
        <img src="./images/chapter-02/interviews/entrevista_jose_isaac.png" alt="Entrevista 01"  width="90%"/>
    </div>

- Inicio: 
- Fin: 
- Enlace de entrevista: 
- Resumen de la entrevista: 

    Natalia La Rosa, de 24 años, es ingeniera biomédica y reside en Bellavista, Callao. Se describe como una persona extrovertida, que disfruta de salir con amigos y conocer gente nueva. Además, es responsable del cuidado de su hermano menor, para lo cual utiliza herramientas tecnológicas, aunque su principal recurso ha sido el control parental de YouTube.

    Natalia expresó su preocupación por la seguridad de su hermano, sobre todo cuando está ocupada con sus estudios universitarios o trabajo. Le preocupa que su hermano pueda abrir la puerta a extraños o salir solo, lo que lo pondría en peligro.

    Natalia considera que un sistema de monitoreo en tiempo real sería ideal para su situación, destacando la importancia de la precisión en la ubicación y la emisión de alarmas inmediatas si su hermano sale de la zona segura. También le parece relevante que el sistema sea fácil de usar y tenga la posibilidad de conectarse con la policía para reportar emergencias de manera rápida.

    En su experiencia diaria, Natalia ha enfrentado situaciones difíciles, como el hecho de que su hermano salga solo a la calle, exponiéndose a diversos peligros. Un día típico para ella incluye llevar y recoger a su hermano del colegio, y permitirle entrar y salir de casa con una llave, lo que le genera cierta preocupación.

    Finalmente, Natalia considera que el proyecto de monitoreo propuesto sería de gran utilidad para su familia, ya que les permitiría estar más al tanto de la ubicación y las actividades de su hermano. Sugiere que se integre una conexión directa con la policía para reportar desapariciones de forma inmediata, lo que mejoraría significativamente la seguridad.

### 2.2.3 Análisis de entrevistas

**Segmento objetivo 1: Cuidadores o Familiares de personas con Alzheimer**

**Características Objetivas:**
- Edad: Jóvenes (estudiantes) entre 20 y 25 años.
- Nivel educativo: Universitario.
- Rol: Cuidadores de familiares con Alzheimer.
- Tecnología usada: Aplicaciones básicas como WhatsApp.

**Características Subjetivas:**
- Preocupaciones principales: Seguridad y bienestar del familiar (desorientación y fugas).
- Sentimientos: Estrés por la responsabilidad del cuidado.

**Problemas comunes:**
- Desorientación del familiar.
- Cuidado no eficiente sin tecnología avanzada.

**Estadísticas:**
- 100% consideran útil un sistema de monitoreo en tiempo real.
- 66% valoran las alertas inmediatas al salir de zonas seguras.
- 33% sugieren el uso de cámaras.

---

**Segmento objetivo 2: Cuidadores o Familiares de niños pequeños**

**Características Objetivas:**
- Edad: Entre 24 y 28 años.
- Nivel educativo: Universitario.
- Rol: Cuidadores de hermanos menores.
- Tecnología usada: Cámaras de seguridad y control parental.

**Características Subjetivas:**
- Preocupaciones principales: Seguridad del niño en casa y lugares públicos.
- Sentimientos: Ansiedad por el riesgo de que se pierdan.

**Problemas comunes:**
- Pérdida de ubicación en espacios públicos.
- Monitoreo limitado sin capacidad de intervención inmediata.

**Estadísticas:**
- 100% desean recibir alertas si el niño sale de una zona segura.
- 50% consideran importante la conexión con la policía.
- 33% desean monitoreo desde múltiples dispositivos.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

**Segmento: Cuidadores de Personas con Alzheimer**
<div style="text-align: center;">
    <img src="./images/chapter-03/to-be-alzheimer.png" alt="To-Be Alzheimer" style="max-width: 800px; width: 95%">
</div>
<br>

**Segmento: Cuidadores de Niños**
<div style="text-align: center;">
    <img src="./images/chapter-03/to-be-child.png" alt="To-Be Child" style="max-width: 800px; width: 95%">
</div>
<br>

## 3.2. User Stories
### **User Story 01**

| **Épica**                | **Monitoreo y Seguridad en Tiempo Real**     |
|--------------------------|--------------------------------------------------|
| **ID-HU**                | 01                                               |
| **Owner**                | Diego Castro                                     |
| **Título HU**            | Visualización de Ubicación en Tiempo Real        |
| **Descripción:**         | Como cuidador, quiero poder visualizar la ubicación en tiempo real de la persona a cuidar para estar atento ante cualquier situación. |
| **Criterio de Aceptación:** | **Scenario 01:** Ver Ubicación en Tiempo Real <br/> Dado que he configurado el dispositivo correctamente, <br/> Cuando accedo a la aplicación, <br/> Entonces debería ver la ubicación en tiempo real de la persona a cuidar en el mapa. <br/><br/> **Scenario 02:** Actualización en Tiempo Real <br/> Dado que el niño o la persona con Alzheimer se está moviendo, <br/> Cuando la ubicación cambia, <br/> Entonces la aplicación debería actualizar la ubicación automáticamente. |

---

### **User Story 02**

| **Épica**                | **Monitoreo y Seguridad en Tiempo Real**         |
|--------------------------|--------------------------------------------------|
| **ID-HU**                | 02                                               |
| **Owner**                | Jennifer Espinoza                                    |
| **Título HU**            | Alerta de Salida de Zona Segura                  |
| **Descripción:**         | Como cuidador, quiero recibir una notificación si la persona a cuidar sale de la geo-cerca para reaccionar rápidamente. |
| **Criterio de Aceptación:** | **Scenario 01:** Recibir Notificación de Salida <br/> Dado que la persona a cuidar ha salido de la zona segura, <br/> Cuando la geo-cerca es cruzada, <br/> Entonces debería recibir una notificación en la aplicación móvil. <br/><br/> **Scenario 02:** Notificación Repetida <br/> Dado que la persona a cuidar permanece fuera de la geo-cerca, <br/> Cuando pasan 2 minutos, <br/> Entonces debería recibir una segunda notificación. |

---

### **User Story 03**

| **Épica**                | **Configuración y Gestión de Geo-cercas**  |
|--------------------------|--------------------------------------------------|
| **ID-HU**                | 03                                               |
| **Owner**                | Diego Esquivel                                     |
| **Título HU**            | Establecer Geo-cercas                            |
| **Descripción:**         | Como cuidador, quiero poder establecer geo-cercas para definir zonas seguras para la persona a cuidar. |
| **Criterio de Aceptación:** | **Scenario 01:** Configurar Geo-cerca <br/> Dado que deseo delimitar una zona segura, <br/> Cuando accedo a la sección de geo-cercas, <br/> Entonces debería poder dibujar un área en el mapa y guardarla como geo-cerca. <br/><br/> **Scenario 02:** Editar Geo-cerca Existente <br/> Dado que deseo cambiar los límites de una geo-cerca, <br/> Cuando selecciono una geo-cerca existente, <br/> Entonces debería poder editar su tamaño y forma. |

---

### **User Story 04**

| **Épica**                | **Comunicación y Control Remoto** |
|--------------------------|------------------------------------------------------|
| **ID-HU**                | 04                                                   |
| **Owner**                | Steve Castillo                                         |
| **Título HU**            | Comunicación Remota con el niño a cuidar |
| **Descripción:**         | Como cuidador de un niño, quiero poder comunicarme con él a través del altavoz del dispositivo para darle instrucciones en caso de emergencia. |
| **Criterio de Aceptación:** | **Scenario 01:** Enviar Mensaje de Voz <br/> Dado que necesito comunicarme urgentemente, <br/> Cuando presiono el botón de altavoz en la aplicación, <br/> Entonces debería poder grabar y enviar un mensaje de voz al dispositivo. <br/><br/> **Scenario 02:** Confirmación de Recepción <br/> Dado que envié un mensaje de voz, <br/> Cuando el mensaje es recibido por el dispositivo, <br/> Entonces debería recibir una confirmación en la aplicación. |

---

### **User Story 05**

| **Épica**                | **Monitoreo y Seguridad en Tiempo Real**      |
|--------------------------|----------------------------------------------------|
| **ID-HU**                | 05                                                 |
| **Owner**                | Cristian Quito                                       |
| **Título HU**            | Activación de Alarmas en Situación de Peligro      |
| **Descripción:**         | Como cuidador, quiero que el dispositivo active una alarma sonora si la persona a cuidar está en peligro, para llamar la atención de personas cercanas. |
| **Criterio de Aceptación:** | **Scenario 01:** Activación Automática de Alarma <br/> Dado que la persona a cuidar ha salido de la geo-cerca, <br/> Cuando se detecta la salida, <br/> Entonces la alarma sonora instalada debería activarse automáticamente. <br/><br/> **Scenario 02:** Desactivación Manual de Alarma <br/> Dado que la situación ha sido resuelta, <br/> Cuando presiono el botón de desactivar en la aplicación, <br/> Entonces la alarma sonora debería apagarse inmediatamente. |

---

### **User Story 06**

| **Épica**                | **Visualización de Historial**        |
|--------------------------|----------------------------------------------------|
| **ID-HU**                | 06                                                 |
| **Owner**                | Diego Castro                                       |
| **Título HU**            | Monitoreo de Actividad Física                      |
| **Descripción:**         | Como cuidador, quiero poder monitorear la actividad física del niño a cuidar para asegurarme de que esté activo y saludable. |
| **Criterio de Aceptación:** | **Scenario 01:** Visualizar Actividad Física <br/> Dado que me encuentro en la pantalla principal de la aplicación, <br/> Cuando accedo a la sección de historial de actividad física, <br/> Entonces debería ver un resumen de los movimientos y actividad del día. <br/><br/> **Scenario 02:** Notificación de Inactividad <br/> Dado que el dispositivo detecta poca actividad, <br/> Cuando el niño ha superado el tiempo máximo de inactividad configurado en la aplicación, <br/> Entonces debería recibir una notificación para verificar la situación. |

---

### **User Story 07**

| **Épica**                | **Comunicación y Control Remoto** |
|--------------------------|----------------------------------------------------------|
| **ID-HU**                | 07                                                       |
| **Owner**                | Jennifer Espinoza                                             |
| **Título HU**            | Control de Dispositivos Externos                         |
| **Descripción:**         | Como cuidador, quiero que GuardianArea pueda activar otros dispositivos como luces o cámaras cuando la persona a cuidar está en peligro para ayudarme a controlar la situación. |
| **Criterio de Aceptación:** | **Scenario 01:** Activación de Luces Externas <br/> Dado que la persona a cuidar ha salido de la geo-cerca, <br/> Cuando el evento es detectado, <br/> Entonces las luces exteriores de la casa deberían encenderse automáticamente. <br/><br/> **Scenario 02:** Activación de Cámara de Seguridad <br/> Dado que la persona a cuidar ha salido de la geo-cerca, <br/> Cuando el evento es detectado, <br/> Entonces la cámara de seguridad debería activarse y comenzar a grabar. |

---

### **User Story 08**

| **Épica**                | **Diagnóstico y Solución de Problemas del Dispositivo**           |
|--------------------------|----------------------------------------------------|
| **ID-HU**                | 08                                                 |
| **Owner**                | Diego Esquivel                                       |
| **Título HU**            | Diagnóstico y Solución de Problemas del Dispositivo GuardianArea       |
| **Descripción:**         | Como cuidador, quiero poder diagnosticar y resolver problemas del dispositivo a través de la aplicación para asegurar su correcto funcionamiento. |
| **Criterio de Aceptación:** | **Scenario 01:** Diagnóstico Automático <br/> Dado que el dispositivo no está funcionando correctamente, <br/> Cuando accedo a la función de diagnóstico, <br/> Entonces debería poder ejecutar un diagnóstico automático y recibir un informe del estado del dispositivo. <br/><br/> **Scenario 02:** Solución de Problemas Guiada <br/> Dado que se ha identificado un problema, <br/> Cuando accedo a la función de solución de problemas, <br/> Entonces debería recibir instrucciones paso a paso para resolver el problema.|

---

### **User Story 09**

| **Épica**                | **Visualización de Historial**          |
|--------------------------|----------------------------------------------------|
| **ID-HU**                | 09                                                 |
| **Owner**                | Steve Castillo                                       |
| **Título HU**            | Revisión del Historial de Eventos                  |
| **Descripción:**         | Como cuidador, quiero poder revisar un historial de todos los eventos y alertas para analizar el comportamiento y mejorar la seguridad. |
| **Criterio de Aceptación:** | **Scenario 01:** Acceso al Historial de Eventos <br/> Dado que necesito revisar eventos pasados, <br/> Cuando accedo a la sección de historial, <br/> Entonces debería poder ver una lista de todos los eventos y alertas anteriores. <br/><br/> **Scenario 02:** Filtrado del Historial <br/> Dado que necesito encontrar eventos específicos, <br/> Cuando utilizo los filtros disponibles, <br/> Entonces debería poder ver solo los eventos que cumplen con los criterios seleccionados. |

---

### **User Story 10**

| **Épica**                | **Configuración y Gestión de Geo-cercas** |
|--------------------------|--------------------------------------------------------------|
| **ID-HU**                | 10                                                           |
| **Owner**                | Cristian Quito                                                 |
| **Título HU**            | Configuración de Alertas Personalizadas                     |
| **Descripción:**         | Como cuidador, quiero establecer el comportamiento del dispositivo cuando la persona a cuidar se acerque a una geo-cerca para tener un mayor control. |
| **Criterio de Aceptación:** | **Scenario 01:** Configurar Alerta Personalizada <br/> Dado que quiero establecer una alerta específica, <br/> Cuando accedo a la configuración de alertas, <br/> Entonces debería poder definir los criterios para la alerta personalizada. <br/><br/> **Scenario 02:** Editar Alerta Personalizada <br/> Dado que necesito ajustar una alerta existente, <br/> Cuando selecciono una alerta personalizada en la configuración, <br/> Entonces debería poder editar los criterios y guardar los cambios. |


# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. Event Storming

Durante nuestra sesión de event storming, llevamos a cabo una reunión en la que discutimos diversas ideas. A lo largo de la sesión, identificamos conceptos clave para nuestra aplicación y comenzamos a desarrollar las primeras versiones.

A continuación, presentaremos el desarrollo de nuestro event storming, realizado con la herramienta Miro. En esta sesión participaron los cinco integrantes de Digital Dart, quienes contribuyeron con sus ideas y perspectivas para el avance del proyecto.

**Paso 1: Unstructured Exploration**
<div style="text-align: center;">
    <img src="./images/chapter-04/0-postits-event.png" alt="PostIts" style="max-width: 800px; width: 95%">
</div>
<div style="text-align: center;">
    <img src="./images/chapter-04/1-step-event.png" alt="Paso 1" style="max-width: 800px; width: 95%">
</div>
En esta etapa, identificamos y agrupamos los eventos clave del sistema en pasado, considerando tanto las acciones significativas como los distintos tipos de usuarios y funcionalidades principales de la aplicación.

**Paso 02: Timelines**
<div style="text-align: center;">
    <img src="./images/chapter-04/1-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
En este paso, organizamos los eventos de dominio en el orden en que ocurren, comenzando con el flujo ideal ("happy path") y luego añadiendo escenarios alternativos para cubrir diversas situaciones("unhappy path").

**Paso 03: Paint Points**
<div style="text-align: center;">
    <img src="./images/chapter-04/3-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
Durante el proceso, identificamos los puntos críticos, que son áreas donde los usuarios enfrentan dificultades o fricciones. Abordar estos puntos es esencial para mejorar la experiencia del usuario y optimizar el diseño del sistema.

**Paso 04: Pivotal Points**

<div style="text-align: center;">
    <img src="./images/chapter-04/4-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>

Identificamos los eventos fundamentales, marcados con una barra vertical, que indican cambios significativos en el contexto o fase del flujo de trabajo. 

**Paso 05: Commands**
<div style="text-align: center;">
    <img src="./images/chapter-04/5-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
En esta etapa, identificamos los comandos que inician los eventos y asignamos cada uno a un actor específico, clarificando así las acciones y responsabilidades dentro del sistema.

**Paso 06: Policies**
<div style="text-align: center;">
    <img src="./images/chapter-04/6-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
Identificamos y definimos las políticas que automatizan la ejecución de comandos basados en eventos específicos del sistema.

**Paso 07: Read Models**
<div style="text-align: center;">
    <img src="./images/chapter-04/7-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
Durante este paso diseñamos los modelos de lectura que proporcionan la información necesaria para que los actores tomen decisiones y ejecuten comandos de manera eficiente.

**Paso 08: External Systems**
<div style="text-align: center;">
    <img src="./images/chapter-04/8-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
Durante esta etapa, se identifican los sistemas externos relevantes para cada contexto y se definen las interfaces y comunicaciones necesarias para su integración efectiva.

**Paso 09: Aggregates**
<div style="text-align: center;">
    <img src="./images/chapter-04/9-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
Definimos y diseñamos los agregados para cada contexto del sistema, asegurando que representen de manera coherente las transacciones y operaciones clave, agrupando conceptos relacionados y gestionando comandos y eventos asociados.

**Paso 10: Bounded Contexts**
<div style="text-align: center;">
    <img src="./images/chapter-04/10-step-event.png" alt="Paso 2" style="max-width: 800px; width: 95%">
</div>
En esta etapa final, se identifican y definen los contextos delimitados, agrupando los agregados que están estrechamente relacionados o que interactúan entre sí mediante políticas. Estos contextos delimitados ayudan a organizar y gestionar las distintas áreas del sistema.

**Link Miro:** [Event Storming]()
































