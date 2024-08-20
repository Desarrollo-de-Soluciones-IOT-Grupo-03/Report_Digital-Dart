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
  - [4.1.1. EventStorming](#411-eventstorming)
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

**DigitalDart** es una empresa emergente de tecnología que se especializa en desarrollar soluciones IoT innovadoras para preservar y conservar recursos valiosos. Nos enfocamos en crear dispositivos inteligentes que permitan la administración remota de condiciones ambientales críticas en espacios como bibliotecas, museos y galerías de arte. Nuestra misión es ayudar a preservar la historia y la cultura al ofrecer herramientas tecnológicas que aseguren la longevidad de libros, documentos y artefactos antiguos.

### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/steve.png" alt="Steve Castillo" style="margin-bottom: 5px;" width="600"/>
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
            <img src="https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/castro.png" alt="Diego Castro" style="margin-bottom: 5px;" width="600"/>
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
            <img src="https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/Jenn.png" alt="Jennifer Espinoza" style="margin-bottom: 5px;" width="600"/>
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
            <img src="https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/esquivel.png" alt="Diego Esquivel" style="margin-bottom: 5px;" width="600"/>
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

La conservación de libros y documentos antiguos en bibliotecas y museos es una preocupación crítica. Estos objetos son extremadamente vulnerables a condiciones ambientales inadecuadas, como la humedad, la temperatura y la iluminación, que pueden acelerar su deterioro. La falta de un monitoreo y control efectivo de estas condiciones puede llevar a la pérdida irreversible de patrimonio cultural y conocimiento histórico.

Según la Organización de las Naciones Unidas para la Educación, la Ciencia y la Cultura (UNESCO, 2021), el deterioro de documentos históricos debido a la exposición a condiciones ambientales inadecuadas es un problema global significativo, especialmente en instituciones con recursos limitados. Estas condiciones adversas pueden causar daños irreversibles en los materiales y afectan la preservación a largo plazo.

**EnviroSafe** es una aplicación diseñada para enfrentar estos desafíos proporcionando un sistema de monitoreo y control remoto de las condiciones ambientales en bibliotecas y museos. Con **EnviroSafe**, los administradores pueden supervisar y ajustar parámetros como la temperatura, la humedad y la iluminación en tiempo real, reduciendo así el riesgo de daños a las colecciones.

### What (¿Qué?)

El principal problema identificado es la dificultad de mantener condiciones ambientales óptimas en bibliotecas y museos para preservar libros y documentos antiguos. Esto resulta en un aumento del deterioro y la pérdida de patrimonio cultural.

### When (¿Cuándo?)

El problema surge cuando no se tiene un control constante y automatizado de las condiciones ambientales. Esto puede ocurrir durante todo el año, especialmente en temporadas con cambios climáticos drásticos o en instalaciones con infraestructura limitada.

### Where (¿Dónde?)

El problema se identifica en bibliotecas, museos y otras instituciones que albergan documentos y libros antiguos, especialmente en zonas con alta humedad o fluctuaciones de temperatura, como áreas costeras o tropicales.

### Who (¿Quién?)

Este problema afecta a los administradores de bibliotecas y museos, así como a los conservacionistas encargados de la preservación del patrimonio cultural. También impacta indirectamente a investigadores, académicos y al público en general que depende de la integridad de estos recursos.

### Why (¿Por qué?)

La causa principal es la falta de sistemas automatizados de monitoreo y control de condiciones ambientales, lo que dificulta el mantenimiento de un entorno adecuado para la conservación de libros y documentos. Los métodos manuales son insuficientes y propensos a errores.

### How (¿Cómo?)

La solución propuesta es **EnviroSafe**, una aplicación que permite el monitoreo y control remoto de las condiciones ambientales, alertando automáticamente a los administradores ante cualquier cambio crítico que pueda poner en riesgo la integridad de los documentos.

### How much (¿Cuánto?)

Este problema tiene un impacto significativo en la preservación de la cultura y el conocimiento, ya que un 30% de las colecciones en riesgo podría ser dañado o perdido si no se implementan medidas adecuadas. El uso de **EnviroSafe** podría reducir este riesgo significativamente, mejorando la preservación en un 25% dentro de los primeros seis meses de implementación.

## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

Las bibliotecas y museos enfrentan dificultades para mantener condiciones ambientales óptimas, lo que resulta en un deterioro acelerado de libros y documentos antiguos. La falta de recursos y sistemas automatizados agrava este problema, poniendo en riesgo el patrimonio cultural.

La ausencia de un monitoreo y control eficaz de las condiciones ambientales conduce a la degradación de colecciones valiosas, lo que limita su disponibilidad para futuras generaciones.

¿Cómo podemos mejorar la eficacia en la preservación de libros y documentos antiguos mediante un sistema automatizado de monitoreo y control ambiental en bibliotecas y museos?

### 1.2.2.2. Lean UX Assumptions

**Features:**
- Monitoreo en tiempo real de humedad, temperatura e iluminación.
- Control remoto de dispositivos que regulen estas condiciones.
- Alertas automáticas ante cambios críticos en las condiciones ambientales.

**Business outcomes:**
- Incremento en la adopción de la solución por parte de instituciones académicas y culturales.
- Generación de ingresos mediante la venta del dispositivo y suscripción a servicios de monitoreo avanzado.
- Expansión geográfica a otras regiones y países donde la conservación de documentos es una prioridad.

**Users:**
- Bibliotecarios y conservadores responsables del mantenimiento de colecciones antiguas.
- Administradores de museos y galerías que buscan proteger artefactos valiosos.

**Users outcomes:**
- Mejora en la conservación de colecciones, reduciendo el deterioro debido a condiciones ambientales.
- Reducción en los costos asociados con la restauración y reemplazo de materiales dañados.
- Tranquilidad para los administradores al saber que sus colecciones están protegidas de manera eficiente.

### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:** Creemos que, al proporcionar un sistema de monitoreo y control remoto para bibliotecas y museos, mejoraremos la preservación de libros y documentos antiguos. Sabremos que hemos tenido éxito cuando veamos una reducción del 25% en la incidencia de daños causados por condiciones ambientales inadecuadas dentro de los primeros seis meses de implementación.

**Hipótesis 2:** Creemos que, al ofrecer alertas automáticas ante cambios críticos en la temperatura, humedad o iluminación, los administradores podrán reaccionar rápidamente para evitar daños. Sabremos que hemos tenido éxito si el 90% de las alertas son atendidas en un plazo de 30 minutos, evitando cualquier daño significativo.

**Hipótesis 3:** Creemos que, al integrar reportes semanales automáticos sobre las condiciones ambientales, los administradores podrán tomar decisiones más informadas sobre el mantenimiento y conservación. Sabremos que hemos tenido éxito si el 80% de los administradores reporta un aumento en la eficiencia de sus intervenciones de conservación dentro de los primeros tres meses.

**Hipótesis 4:** Creemos que, al permitir el acceso remoto a los datos históricos de condiciones ambientales, los conservacionistas podrán identificar patrones y prever problemas antes de que ocurran. Sabremos que hemos tenido éxito si el 70% de los usuarios utiliza esta función para realizar ajustes preventivos en sus instalaciones.

**Hipótesis 5:** Creemos que, al ofrecer un sistema de alerta escalonado, donde los administradores son notificados según la gravedad del cambio ambiental, se reducirá el tiempo de respuesta ante condiciones críticas. Sabremos que hemos tenido éxito si el tiempo promedio de respuesta ante alertas críticas se reduce en un 40% dentro de los primeros dos meses.

**Hipótesis 6:** Creemos que, al proporcionar opciones de personalización para los umbrales de alerta, los administradores podrán adaptar EnviroSafe a las necesidades específicas de sus colecciones. Sabremos que hemos tenido éxito si el 85% de los usuarios personaliza estos umbrales dentro del primer mes de uso.

### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas](https://digitaldartstorage.blob.core.windows.net/digitaldartstorage/Lean_UX_Canvas.png)

## 1.3. Segmentos objetivo

**Segmento objetivo 1: Bibliotecas universitarias y académicas**  
Este segmento se enfoca en instituciones educativas que tienen colecciones de libros y documentos antiguos que requieren una conservación cuidadosa. Estas bibliotecas buscan soluciones tecnológicas que les permitan mantener sus colecciones en condiciones óptimas, asegurando su disponibilidad para futuras generaciones de estudiantes e investigadores.

**Segmento objetivo 2: Museos y galerías**  
En este segmento, nos dirigimos a museos y galerías que albergan artefactos, documentos y obras de arte que requieren un control ambiental estricto para su preservación. Estas instituciones valoran las herramientas que les permitan monitorear y ajustar las condiciones en tiempo real, minimizando los riesgos de deterioro.
