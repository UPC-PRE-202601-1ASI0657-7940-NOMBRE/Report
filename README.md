<img width="1600" height="872" alt="image" src="https://github.com/user-attachments/assets/5b595110-6130-4608-a7e8-5b0e64039a6c" />
<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Carrera de Ingeniería de Software - Ciclo VII</strong><br><br>
    <strong>1ASI0657 - Fundamentos de Arquitectura de Software</strong><br>
    <br><strong>NRC 7940</strong><br>
    <br><strong>Profesor: Daniel Enrique Mori Yzaguirre</strong><br>
    <br><strong><b>INFORME DEL AVANCE 2</strong></b><br>
</p>

<p align="center">
    <strong>Startup del Proyecto: Bibflip</strong><br>
    <strong>Producto: Bib Flip</strong><br>
</p>

<div>
    <h3 align="center">Team Members:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Carranza Tesén, Joaquín</td>
            <td>U20191B935</td>
        </tr>
        <tr>
            <td>Rengifo Lozano, David</td>
            <td>U202221022</td>
        </tr>
        <tr>
            <td>Velarde Luyo, Piero </td>
            <td>U20211A620</td>
        </tr>
    </table>
    </div>
</body>
<br>
<br>
<br>
<br>
<p align="center">
<br><strong>2026-10</strong></p>
<br>

<br>
<br>

## Registro de Versiones del Informe

En esta sección se resumen los avances y modificaciones realizadas durante el ciclo de vida de desarrollo del proyecto equivalente a un semestre.

| Versión | Fecha      | Autor                          | Descripción de modificación                                                 |
| ------- | ---------- | ------------------------------ | --------------------------------------------------------------------------- |
| Avance 1     | 18/04/2025 | Bibflip | Comenzamos evaluando el problema, definiendo el público objetivo y estableciendo la solución del producto. Posteriormente, procedimos a redactar las historias de usuario y a organizar el product backlog.                                       |
| Avance 2     | 03/05/2025 | Bibflip | Se elaboró la segunda parte del trabajo, la cual abarca el capítulo 4. En esta sección se definieron los conceptos clave de la arquitectura de software y se detalló, junto con sus diagramas, la solución propuesta.                                       |


# Contenido

## Tabla de Contenidos

### [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
          - [**Business Outcomes:**](#business-outcomes)
          - [**Users:**](#users)
          - [**User Outcomes \& Benefits:**](#user-outcomes--benefits)
          - [**Feature Assumptions:**](#feature-assumptions)
          - [**Business Assumptions:**](#business-assumptions)
          - [**User Assumptions:**](#user-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)
### [Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)
- [4.1. Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)
  - [4.1.1. Principles Statements](#411-principles-statements)
  - [4.1.2. Approaches Statements Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)
  - [4.1.3. Context Diagram](#413-context-diagram)
  - [4.1.4. Approach driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)
  - [4.1.5. Relational/Non Relational Database Diagram](#415-relationalnon-relational-database-diagram)
  - [4.1.6. Design Patterns](#416-design-patterns)
  - [4.1.7. Tactics](#417-tactics)
- [4.2. Architectural Drivers](#42-architectural-drivers)
  - [4.2.1. Design Purpose](#421-design-purpose)
  - [4.2.2. Primary Functionality (Primary User Stories)](#422-primary-functionality-primary-user-stories)
  - [4.2.3. Quality Attribute Scenarios](#423-quality-attribute-scenarios)
  - [4.2.4. Constraints](#424-constraints)
  - [4.2.5. Architectural Concerns](#425-architectural-concerns)
- [4.3. ADD Iterations](#43-add-iterations)
  - [4.3.1. Iteration 1: Bibflip Foundation & Security Enhancement](#431-iteration-1-bibflip-foundation--security-enhancement)
    - [4.3.1.1. Architectural Design Backlog 1](#4311-architectural-design-backlog-1)
    - [4.3.1.2. Establish Iteration Goal by Selecting Drivers](#4312-establish-iteration-goal-by-selecting-drivers)
    - [4.3.1.3. Choose One or More Elements of the System to Refine](#4313-choose-one-or-more-elements-of-the-system-to-refine)
    - [4.3.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#4314-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
    - [4.3.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#4315-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
    - [4.3.1.6. Sketch Views (C4 & UML) and Record Design Decisions](#4316-sketch-views-c4--uml-and-record-design-decisions)
    - [4.3.1.7. Analysis of Current Design and Review Iteration Goal (Kanban Board)](#4317-analysis-of-current-design-and-review-iteration-goal-kanban-board)
  - [4.3.2. Iteration 2: Booking Management & IoT Integration](#432-iteration-2-booking-management--iot-integration)
    - [4.3.2.1. Architectural Design Backlog 2](#4321-architectural-design-backlog-2)
    - [4.3.2.2. Establish Iteration Goal by Selecting Drivers](#4322-establish-iteration-goal-by-selecting-drivers)
    - [4.3.2.3. Choose One or More Elements of the System to Refine](#4323-choose-one-or-more-elements-of-the-system-to-refine)
    - [4.3.2.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#4324-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
    - [4.3.2.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#4325-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
    - [4.3.2.6. Sketch Views (C4 & UML) and Record Design Decisions](#4326-sketch-views-c4--uml-and-record-design-decisions)
    - [4.3.2.7. Analysis of Current Design and Review Iteration Goal (Kanban Board)](#4327-analysis-of-current-design-and-review-iteration-goal-kanban-board)

---

# Student Outcome

| Criterio específico                                                                                                                     | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. | **Piero Velarde Luyo** <br> **Avance 1:** Analicé el planteamiento del problema y profundicé mis conocimientos informáticos para integrar en la solución los segmentos de usuarios adecuados, basándome en los requerimientos del software. <br> **Avance 2:** La redacción y elaboración del capítulo 4 me permitió actualizar mis conocimientos en arquitectura de software. Gracias a esto, pude estructurar la solución con mayor claridad y tomar decisiones técnicas fundamentadas que impulsan mi desarrollo profesional. | **Avance 1:** Como equipo, revisamos los conceptos clave del proyecto para definir el problema y desarrollar la solución. Al identificar áreas de mejora en la arquitectura de software, actualizamos nuestros conocimientos para aplicar las mejores prácticas. Esto nos permitió diseñar un software más robusto y escalable. <br> **Avance 2:** Investigamos y aplicamos conceptos de arquitectura de software para estructurar nuestra propuesta. Esto nos permitió definir los elementos solicitados e identificar qué otros conocimientos eran necesarios para diseñar una arquitectura sólida.                                 |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.  | **Piero Velarde Luyo** <br> **Avance 1:** Me familiaricé con el perfil de los usuarios y el personal técnico para integrarme por completo al proyecto, impulsando propuestas de organización y reuniones de trabajo. <br> **Avance 2:** Liderar el equipo me hizo notar que el aprendizaje continuo es vital en el desarrollo de software. Por ello, investigué conceptos técnicos clave para respaldar nuestras decisiones arquitectónicas y orientar la solución de manera efectiva.                                          | **Avance 1:** En esta etapa, el equipo colaboró para desarrollar la solución y repasó los conceptos previos para fundamentar nuestras herramientas. Además, investigamos nuevos temas para entender mejor el problema, lo que nos permitió definir los requerimientos y las historias de usuario de forma coherente y precisa. <br> **Avance 2:** Continuaremos investigando y definiendo los conceptos técnicos necesarios para diagramar nuestra arquitectura. Así, garantizaremos la satisfacción de los requerimientos de los interesados y daremos inicio a la primera iteración del diseño arquitectónico guiado por atributos. |



---


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

En el 2020, se reportaron matrículas con aproximadamente 1.3 millones de estudiantes de pregrado y 95 mil de posgrado en universidades peruanas (SUNEDU, 2022). Estos índices, a su vez, provocan una alta demanda de espacios de estudio y problemas con la disponibilidad de las bibliotecas. Un claro ejemplo de ello se puede observar en la Universidad Nacional Mayor de San Marcos. Esta institución universitaria, siendo una de las más grandes del país, cuenta con la infraestructura necesaria para poder atender 2500 estudiantes de manera simultánea (Montoro, 2024). Sin embargo, esto resulta insuficiente debido a la gran cantidad de alumnos. Este problema no está exento de instituciones privadas, ya que universidades como la UPC también han demostrado tener ciertas deficiencias con sus plataformas. Sobre ello, el 31 de marzo de 2025, estudiantes de la UPC denunciaron un colapso total durante el proceso de matrícula en su nueva plataforma conocida como Banner. Esto comenzó el 24 de marzo cuando una gran cantidad de alumnos intentaron acceder al sistema, pero múltiples fallas impidieron completar el proceso, obligando a la universidad a suspender temporalmente la matrícula y forzando a los estudiantes a hacer largas colas presenciales (Diario UNO, 2025). Esta situación logró solventarse gracias a la participación masiva de la manifestación del alumnado y la actualización continúa del sistema. No obstante, esta solución solo abarcó las principales funcionalidades de la plataforma y hasta el día de hoy mantiene algunas en espera de mejora, lo cual ocasionó que el personal universitario simplemente tuviera que adaptarse a los cambios. 

Una de estas funcionalidades que quedaron deprecadas componen el sistema de reserva de cubículos y espacios de estudio pertencientes a la biblioteca. Por ello, baje ese contexto, presentamos Bib Flip como una solución tecnológica desarrollada para mejorar la experiencia del uso de cubículos estudiantiles en universidades peruanas. Para ello, la propuesta deberá incluir una aplicación web y móvil con dispositivos IoT integrados. Además, nuestro enfoque es principalmente resolver problemas relacionados con la disponibilidad y la ocupación de cubículos universitarios en tiempo real para reducir tiempos de espera. 

Bib Flip brindará a los estudiantes la posibilidad de verificar la disponibilidad de espacios individuales y grupales, hacer reservas y revisar sus detalles. Además, ofrecerá un mapa interactivo para ubicar las sedes disponibles, así como la opción de registrar nuevos usuarios para acceder a los servicios de la aplicación. Además, contará con un panel exclusivo para que administradores seleccionados puedan gestionar los cubículos de estudio y visualizar las reservas activas, permitiendo un control actualizado del uso de cubículos, planificar la distribución de recursos de manera eficiente y optimizar la organización operativa.

Misión:
Ofrecer una solución tecnológica eficiente y accesible en la gestión de espacios de estudio para mejorar la experiencia académica y las operaciones de la biblioteca.

Visión:
Consolidarse como la principal solución digital en el Perú para la gestión de procesos en bibliotecas universitarias, promoviendo una experiencia de estudio más ordenada, ágil y satisfactoria para los estudiantes, y una gestión más eficiente para las instituciones educativas.

### 1.1.2. Perfiles de integrantes del equipo

|                       Photo                        |                      Description                      |
| :------------------------------------------------: | :---------------------------------------------------: |
| <img width="404" height="140" alt="foto" src="https://github.com/user-attachments/assets/9dde8619-ff29-4250-850a-9daeb7186c16" />| **Carranza Tesén, Joaquín** <br> Hola, soy Joaquín Carranza. Tengo 25 años y actualmente curso el séptimo ciclo de la carrera de Ingeniería de Software. Me gusta la tecnología y la forma en que ayuda a las personas a resolver problemas de manera más rápida y eficiente. Me interesa especialmente el manejo de datos y la ciberseguridad. Siento que puedo aportar a mi equipo ideas desde otra perspectiva, ya que siempre me cuestiono cómo se podría mejorar el producto o hacia qué objetivo estamos apuntando. |
| [![david.jpg](https://i.postimg.cc/zX8Bw1SK/1881dbb4-5d7f-4e6a-97e4-0c43780b41a0.jpg)](https://postimg.cc/G9gdrVfm) | **Rengifo Lozano, David** <br>  Soy David Rengifo Lozano, tengo 21 años y estoy cursando la carreta de ingenieria de software. Soy apasionado por la tecnologia, la ciencia y los negocios, me gusta crear valor percibible.|
| [![pierovelarde.jpg](https://i.postimg.cc/pdj5nykJ/pierovelarde.jpg)](https://postimg.cc/Y4pC5r5v) | **Velarde Luyo, Piero Alberto** <br> Soy Piero, estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Escogí esta carrera por mi facilidad en el uso de las computadoras. Asímismo, por mi interés en el funcionamiento de las anteriores mencionadas y todo respecto a la programación y las tecnologías emergentes. |


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

**What (¿Qué problema abordamos?)**
<br><br>La administración ineficaz de los espacios de estudio en las bibliotecas universitarias peruanas es el problema principal. Los alumnos experimentan incertidumbre con respecto a la disponibilidad de cubículos, se frustran cuando no encuentran espacios libres y deben esperar mucho tiempo. Asimismo, el sistema que las universidades suelen otorgar para la reserva de espacios de estudio conlleva un proceso lento y poco eficiente en la mayoría de situaciones.<br>

**Why (¿Por qué existe este problema?)**
<br><br>La raíz del problema surge del crecimiento exponencial de la matrícula universitaria, infraestructura insuficiente para atender la demanda real y procesos deficientes para la administración de reservas.<br>

**Where (¿Dónde ocurre el problema?)**
<br><br>El problema surge en las bibliotecas de instituciones universitarias peruanas. Para ello, nos centraremos principalmente en la sede San Miguel de la Universidad Peruana de Ciencias Aplicadas.<br>

**When (¿Cuándo se intensifica el problema?)**
<br><br>La problemática se agudiza en diferentes períodos como las semanas de entregas de trabajos parciales y finales, semanas de presentación y envío de avances académicos y en horarios con gran concurrencia de alumnos (mañana y tarde).<br>

**Who (¿Quién está afectado?)**
<br><br>Se indentifican entre los principales afectados a los estudiantes universitarios que experimentan dificultades para acceder a espacios de estudio cuando los necesitan, especialmente durante períodos altamente concurridos como en semanas de trabajos parciales y finales. En segundo lugar, también tenemos al personal de bibliotecas universitarias que enfrentan desafíos en la gestión de cubículos.<br>

**How (¿Cómo?)**
<br><br>La solución se llevará a cabo integrando sensores de medición de peso para cada asiento del cubículo, los cuales estarán vinculados por medio de una red IoT que envíe datos en tiempo real a un sistema centralizado para la gestión bibliotecaria. Además, los estudiantes podrán visualizar la disponibilidad y el personal del establecimiento podrá gestionar la ocupación de manera óptima y recibir alertas en caso de anomalías a través de una aplicación móvil y web.<br>

**How much (¿Cuánto?)**
<br><br>*¿Cuánto afecta este problema?*
<br>La gestión ineficiente de espacios de estudio genera pérdidas académicas significativas para las instituciones universitarias debido a la disminución en la satisfacción estudiantil, lo cual se traduce en una menor productividad académica por parte de los estudiantes.
<br><br>*¿Cuánto costará resolver este problema?*
<br>La problemática identificada no requiere una reestructuración completa del sistema bibliotecario universitario, sino una intervención tecnológica específica que resuelva los principales obstáculos: el acceso rápido a información de disponibilidad en tiempo real y una mejor planificación anticipada de espacios de estudio. En este sentido, la solución propuesta no busca reemplazar los procesos académicos tradicionales, sino complementarlos con herramientas digitales que permitan a las bibliotecas universitarias peruanas operar con mayor eficiencia, transparencia y satisfacción estudiantil.
<br>Por ello, el costo de implementación variará según el número de cubículos y la infraestructura tecnológica requerida para la instalación y mantenimiento de los sensores, así como el desarrollo de la plataforma digital integrada al sistema bibliotecario existente.
<br><br>*¿Cuántas personas se beneficiarán?*
<br>Esta solución beneficiará directamente a estudiantes universitarios y al personal bibliotecario, con un impacto indirecto en toda la comunidad académica. Se estima que, en bibliotecas universitarias de tamaño mediano, la implementación de esta tecnología podría mejorar la eficiencia en la asignación de espacios en un 35-45%, beneficiando diariamente a cientos de estudiantes y optimizando las labores del personal bibliotecario.


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1 - Personal de Bibliotecas**:
Los sistemas utilizados para la administración de cubículos en bibliotecas universitarias no aprovechan las tecnologías actuales con las que contamos y presentan deficiencias en su rendimiento. Por ello, nuestra propuesta abordará esta brecha mediante un panel de administración integral que proporcione una gestión óptima y análisis de datos en tiempo real; además, estará dirigido al personal de la sede San Miguel de la UPC.<br>

**Problem Statement 2 - Estudiantes Universitarios:**
El estado actual para la reservación de espacios de estudio en bibliotecas universitarias se compone principalmente de procesos poco eficientes. Los servicios existentes no permiten que los estudiantes puedan revisar la disponibilidad de los cubículos o realizar reservas de manera rápida y cómoda. Por ello, nuestra propuesta abordará esta brecha mediante una plataforma digital integrada con dispositivos IoT y nuestro enfoque estará dirigido a estudiantes universitarios de la sede San Miguel de la UPC<br>

#### 1.2.2.2. Lean UX Assumptions

##### **Business Outcomes:**

- Aumento del 30% en la eficiencia de utilización de cubículos en las bibliotecas que adopten la solución.
- Reducción del 80% en el tiempo promedio de búsqueda de espacios de estudio disponibles.
- Incremento del 25% en la satisfacción de los estudiantes, medido a través de encuestas de experiencia.
- Reducción del 40% en incidencias por ocupación indebida y problemas de asignación de cubículos.
- Mejora del 35% en la planificación y distribución de recursos bibliotecarios.

##### **Users:**

Los usuarios se dividen en estos segmentos:

- Personal de biblioteca: Administradores y operadores de 25 a 55 años responsables de la gestión diaria de cubículos.
- Estudiantes universitarios: Jóvenes de 17 a 35 años que buscan espacios de estudio para optimizar su rendimiento académico y reunirse en equipo.

##### **User Outcomes & Benefits:**

Personal de Biblioteca:

- Control óptimo del uso y ocupación de cubículos en tiempo real.
- Acceso a estadísticas e informes detallados que faciliten la toma de decisiones estratégicas.
- Optimización en la distribución de recursos y planificación operativa.
- Escalabilidad para el registro de nuevos cubículos en el sistema

Estudiantes:

- Información precisa y en tiempo real sobre la disponibilidad de cubículos de estudio.
- Reducción significativa de tiempos de espera y búsqueda de espacios disponibles.
- Mejora en la planificación de sesiones de estudio mediante reservas anticipadas.
- Mayor certeza y tranquilidad al acceder a espacios de estudio cuando los necesitan.

##### **Feature Assumptions:**

- Visualización en tiempo real del estado de ocupación de cubículos individuales y grupales.
- Funcionalidad de reservas digitales con confirmación automática y recordatorios.
- Mapas interactivos de ubicación de cubículos disponibles por sede universitaria.
- Panel de gestión integral para administradores con métricas de utilización.
- Sistema de notificaciones push para estudiantes y personal administrativo.
- Integración con dispositivos IoT para detección automática de ocupación.

##### **Business Assumptions:**

1. El cliente necesita optimizar la gestión de los cubículos de estudio mediante un sistema automatizado que permita conocer la disponibilidad y administrar reservas en tiempo real, reduciendo la carga operativa del personal y mejorando la eficiencia general del servicio.
2. Las necesidades del cliente se resolverán mediante la implementación de una plataforma digital conectada con sensores IoT que detecten la ocupación de los cubículos, actualicen el estado en tiempo real y generen reportes automáticos para el análisis de uso.
3. Los clientes son (o serán) las instituciones universitarias, en particular el personal administrativo de las bibliotecas encargado de la asignación, control y monitoreo de los espacios de estudio.
4. El cliente quiere una herramienta confiable, rápida y moderna que le permita mejorar la eficiencia en la gestión, reducir errores humanos y ofrecer una mejor experiencia de servicio a los estudiantes.
5. El cliente también puede obtener informes detallados de ocupación, análisis de patrones de uso y datos estratégicos que le permitan planificar mejor la infraestructura y la demanda de espacios.
6. Conseguiré mi base de clientes mediante alianzas con universidades, demostraciones piloto, participación en ferias académicas y estrategias de marketing directo dirigidas a áreas administrativas y tecnológicas de instituciones educativas.
7. La financiación se obtendrá mediante la venta de licencias institucionales para el uso de la plataforma y servicios adicionales de instalación, soporte técnico y mantenimiento de la infraestructura IoT.
8. Mi principal competencia es los sistemas tradicionales de gestión manual de cubículos y las plataformas de reserva básicas que no cuentan con integración IoT ni análisis de datos en tiempo real.
9. Superaremos a la competencia mediante la optimización de procesos con tecnología IoT, una interfaz intuitiva y un sistema de reportes avanzados que permitan una gestión inteligente y una experiencia de usuario superior.
10. Mi mayor riesgo es la resistencia institucional a adoptar nuevas tecnologías y los costos iniciales asociados a la implementación de la solución.
11. Resolveremos este riesgo mediante la realización de pruebas piloto gratuitas, capacitaciones al personal, y la presentación de resultados tangibles que demuestren la eficiencia, el ahorro de tiempo y el retorno de inversión.
12. Los supuestos que, si resultan falsos, harán que el proyecto fracase son que las universidades no estén dispuestas a invertir en la modernización de sus sistemas de gestión, o que el personal administrativo no adopte de forma activa el uso de la plataforma digital.

##### **User Assumptions:**

¿Quién es el usuario?<br>
El usuario es tanto el personal administrativo de las bibliotecas universitarias, responsable de gestionar los espacios de estudio, como los estudiantes que utilizan los cubículos para sus actividades académicas diarias.

¿Dónde encaja nuestro producto en la vida (o trabajo) del usuario?<br>
Para el personal administrativo, se integra directamente en sus tareas diarias de control y asignación de espacios; para los estudiantes, se convierte en parte de su rutina académica al facilitar la búsqueda y reserva de cubículos de manera rápida y sencilla.

¿Qué problemas resuelve el producto para el usuario?<br>
Resuelve la falta de información en tiempo real sobre la disponibilidad de cubículos, los tiempos perdidos buscando espacios libres, y la frustración derivada de la desorganización en las reservas, mejorando la eficiencia y la satisfacción general.

¿En qué contexto el usuario utiliza el producto?<br>
Durante los horarios académicos, especialmente en épocas de alta demanda como exámenes o entregas de proyectos, tanto desde sus teléfonos móviles como desde computadoras o terminales ubicadas en la biblioteca.

¿Cómo debería verse y comportarse el producto?<br>
Debe tener una interfaz moderna, limpia y visualmente intuitiva, con navegación simple y tiempos de respuesta menores a dos segundos. El sistema debe ser estable, sincronizar datos entre dispositivos y ofrecer una experiencia fluida y confiable.

#### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 1:

Creemos que la eficiencia operativa de las bibliotecas mejorará significativamente si el personal administrativo logra incrementar en un 30% su eficiencia y reducir en un 40% las tareas manuales de gestión mediante una herramienta automatizada que centralice la administración de cubículos y genere reportes dinámicos en tiempo real.

Hypothesis Statement 2:

Creemos que la satisfacción y el uso eficiente de los espacios de estudio aumentarán si los estudiantes universitarios logran reducir en un 30% el tiempo de búsqueda de cubículos y mejorar en un 25% su satisfacción general mediante una aplicación web y móvil que les permita visualizar disponibilidad y realizar reservas fácilmente.

Hypothesis Statement 3:

Creemos que la utilización efectiva de los cubículos y el retorno de inversión de las bibliotecas mejorarán si el personal administrativo logra aumentar en un 30% la ocupación promedio de los espacios mediante la implementación de sensores IoT que transmitan datos en tiempo real a una plataforma centralizada de gestión.

Hypothesis Statement 4:

Creemos que la adopción y satisfacción de los usuarios aumentarán de forma sostenida si el personal administrativo y los estudiantes logran completar tareas básicas en la aplicación sin asistencia en al menos un 85% de los casos y mantener altos niveles de satisfacción mediante una interfaz digital intuitiva y amigable.

Hypothesis Statement 5:

Creemos que la eficiencia en la localización de espacios y la experiencia de los estudiantes mejorarán notablemente si los estudiantes universitarios logran reducir en un 60% el tiempo necesario para ubicar cubículos y aumentar en un 70% el uso de la funcionalidad mediante un sistema de mapas interactivos y navegación dentro de las bibliotecas.


#### 1.2.2.4. Lean UX Canvas

[![Group-1.png](https://i.postimg.cc/T11Txk4t/Group-1.png)](https://postimg.cc/YG55fxkF)

## 1.3. Segmentos objetivo

Para el desarrollo de nuestra propuesta, se han identificado dos segmentos objetivo principales que representan los stakeholders clave del sistema propuesto.

---

### Segmento 1: Personal de bibliotecas universitarias
Este segmento está conformado por el personal administrativo y operativo de las bibliotecas universitarias, quienes son responsables de la gestión diaria de los espacios de estudio y servicios bibliotecarios. Además, para este segmento se tomará como caso de prueba al personal de la Universidad Peruana de Ciencias Aplicadas en la sede San Miguel. Esto debido a su alta demanda como una de las mejores instituciones privadas en el Perú. 

#### Características Demográficas

- Edad: Personal adulto, entre los 25 y 55 años
- Educación: Técnica o universitaria
- Perfil: Personal con experiencia en gestión de servicios bibliotecarios y atención al usuario

#### Características Geográficas

- Ubicación: Lima, Perú


---

### Segmento 2: Estudiantes universitarios
Este segmento está compuesto por estudiantes que utilicen regularmente los espacios de estudio de las bibliotecas universitarias. Además, se tomará como caso de prueba a los estudiantes de la UPC. Esto debido a los casos recientes sobre el reporte de fallos con el nuevo sistema. 

#### Características Demográficas

- Edad: Principalmente entre los 17 y 35 años
- Educación: Estudiantes de pregrado y posgrado de diversas carreras profesionales
- Perfil: Estudiantes con familiaridad en el uso de aplicaciones móviles y sistemas digitales

#### Características Geográficas

- Ubicación: Lima, Perú

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Algunos de los competidores a los que Bib Flip podría enfrentarse son:

- **LibCal (Springshare):** Plataforma de gestión de espacios y reservas para bibliotecas que permite a los usuarios reservar salas de estudio, cubículos y equipos. LibCal se destaca por su integración con sistemas de bibliotecas académicas y herramientas de análisis, aunque su sistema depende de reservas manuales y no cuenta con detección automática de ocupación en tiempo real.

- **SpaceBooking:** Sistema de reserva de espacios para instituciones educativas que facilita la gestión de aulas, laboratorios y espacios de estudio. Ofrece una interfaz web y móvil para reservas, pero funciona principalmente con confirmación manual de ocupación por parte del personal.

- **Midas:** Sistema de reserva de salas y recursos basado en web, diseñado para gestionar la programación y reserva de espacios en diversas organizaciones, incluyendo bibliotecas. MIDAS ofrece gestión de reservas, programación y administración para salas de biblioteca, espacios de estudio, computadoras y otros recursos bibliotecarios, aunque opera principalmente con reservas manuales y no incluye detección automática de ocupación en tiempo real.

### 2.1.1. Análisis competitivo

<table><tr><th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th></tr>
<tr><td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?  </td><td colspan="7" valign="top">Este análisis se lleva a cabo para poder investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado de gestión de espacios bibliotecarios.</td></tr>
<tr><td colspan="6" valign="top"><p><b>Nombre</b></p><p></p></td><td colspan="3" valign="top"><b>Bib Flip</b></td><td colspan="3" valign="top"><b>LibCal</b></td><td colspan="3" valign="top"><b>SpaceBooking</b></td><td valign="top"><b>Midas</b></td></tr>
<tr><td colspan="6" valign="top"><b>Logo</b> </td><td colspan="3" valign="top"><img src="https://i.postimg.cc/vTPjbcpK/Captura-de-pantalla-2025-09-17-013901.png" width="100" height="80"></td><td colspan="3" valign="top"><img src="https://i.postimg.cc/Kzkt5y3C/libcal-logo.jpg" width="120" height="80"></td><td colspan="3" valign="top"><img src="https://i.postimg.cc/zXz08CS2/spacebooking-logo.png" width="120" height="80"><td valign="top"><img src="https://i.postimg.cc/W3b4wmDK/midas-logo.png" width="100" height="80"></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td><td colspan="3" rowspan="2" valign="top"><b>Overview</b></td><td colspan="3" rowspan="2" valign="top">Es una solución tecnológica integral basada en IoT, diseñada específicamente para bibliotecas universitarias. Utiliza sensores de ocupación para detectar automáticamente el uso de cubículos y actualiza esta información en tiempo real en una app web y móvil. El sistema también ofrece una interfaz administrativa completa para el personal de biblioteca, facilitando la gestión del flujo de estudiantes y optimizando la utilización de espacios.</td><td colspan="3" rowspan="2" valign="top">Es una plataforma de gestión de espacios bibliotecarios basada en la nube que permite manejar reservas de salas, cubículos, equipos y recursos. Su enfoque está en ofrecer una experiencia completa para bibliotecas académicas que desean profesionalizar la gestión de sus espacios, utilizando herramientas de análisis, reportes y integración con catálogos bibliotecarios.</td><td colspan="3" rowspan="2" valign="top">Es una solución de reserva de espacios para instituciones educativas que facilita la gestión centralizada de aulas, laboratorios, salas de conferencias y espacios de estudio. Los usuarios pueden buscar espacios disponibles, realizar reservas y gestionar recursos desde una plataforma web, aunque su enfoque principal está en espacios institucionales más que bibliotecarios específicamente.</td><td rowspan="2" valign="top">Es una aplicación que digitaliza el proceso de reserva de espacios académicos, incluyendo cubículos de biblioteca y salas de estudio. Los estudiantes pueden reservar espacios desde sus dispositivos y recibir confirmaciones, aunque el sistema depende de la actualización manual por parte del personal y no ofrece monitoreo automático de ocupación.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td><td colspan="3" rowspan="2" valign="top">Brinda información precisa y en tiempo real sobre la disponibilidad de cubículos, ayudando a estudiantes a evitar búsquedas infructuosas y optimizando su tiempo de estudio desde antes de llegar a la biblioteca.</td><td colspan="3" rowspan="2" valign="top">Permite gestionar reservas de múltiples recursos bibliotecarios de forma integrada y recibir estadísticas detalladas sobre el uso de espacios, facilitando la toma de decisiones administrativas.</td><td colspan="3" rowspan="2" valign="top">Facilita la reserva centralizada de diversos espacios institucionales de forma rápida y confiable, brindando acceso a una amplia variedad de recursos educativos en una sola plataforma.</td><td rowspan="2" valign="top">Reduce la incertidumbre sobre disponibilidad de espacios de estudio, permitiendo a los estudiantes planificar mejor sus sesiones académicas mediante reservas anticipadas.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td><td colspan="3" valign="top"><b>Mercado objetivo</b></td><td colspan="3" valign="top">Bibliotecas universitarias que buscan innovar en la gestión de espacios de estudio y mejorar la experiencia académica de sus estudiantes mediante tecnología avanzada e integración IoT.</td><td colspan="3" valign="top">Bibliotecas académicas y públicas que buscan mejorar su gestión de recursos y espacios. Su mercado abarca desde pequeñas bibliotecas universitarias hasta grandes sistemas bibliotecarios institucionales.</td><td colspan="3" valign="top">Instituciones educativas (universidades, colegios, institutos) que buscan gestionar eficientemente sus espacios académicos y optimizar la utilización de recursos físicos.</td><td valign="top">Universidades y bibliotecas académicas que buscan digitalizar sus procesos de reserva de espacios y mejorar la experiencia estudiantil en el acceso a recursos de estudio.</td></tr>
<tr><td colspan="3" valign="top"><b>Estrategias de Marketing</b></td><td colspan="3" valign="top"><p>Demostraciones en vivo para personal bibliotecario.</p><p>Alianzas estratégicas con universidades.</p><p>Marketing de contenidos educativos.</p><p>Participación en conferencias bibliotecarias.</p></td><td colspan="3" valign="top"><p>Marketing directo a bibliotecarios.</p><p>Participación en eventos del sector.</p><p>Programa de referencias.</p></td><td colspan="3" valign="top"><p>Marketing directo a instituciones educativas.</p><p>Demostraciones en ferias educativas.</p><p>Alianzas con proveedores de tecnología educativa.</p></td><td valign="top"><p>Pruebas gratuitas y pilotos.</p><p>Testimonios de universidades.</p><p>Marketing digital dirigido a estudiantes.</p></td></tr>
<tr><td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td><td colspan="3" valign="top"><b>Productos y Servicios</b></td><td colspan="3" valign="top">Solución basada en IoT que utiliza sensores de ocupación para detectar el uso de cubículos en tiempo real. Esta información se actualiza automáticamente en una app web y móvil, permitiendo a estudiantes ver disponibilidad antes de llegar. Incluye panel administrativo para gestión de espacios, reportes de utilización y análisis de patrones de uso estudiantil.</td><td colspan="3" valign="top">Proporciona un sistema de reservas bibliotecarias, gestión de equipos, herramientas de análisis de uso, integración con sistemas de bibliotecas (ILS), y funciones de calendario para eventos. También incluye módulos para gestión de salas de estudio grupales y recursos especializados.</td><td colspan="3" valign="top">Ofrece gestión centralizada de espacios institucionales, sistema de reservas multi-recurso, reportes de utilización, integración con sistemas académicos, y herramientas de administración para diferentes tipos de usuarios (estudiantes, profesores, personal).</td><td valign="top">Proporciona una aplicación móvil y web para reservas de espacios de estudio, sistema de notificaciones, gestión básica de disponibilidad, y herramientas simples de reporte para el personal bibliotecario.</td></tr>
<tr><td colspan="3" valign="top"><b>Precios y Costos</b></td><td colspan="3" valign="top">Ofrece un modelo de suscripción anual por biblioteca, con precios que varían según el número de cubículos y funcionalidades requeridas. Incluye costo inicial por instalación de sensores IoT. No cobra comisiones por reserva, siendo más rentable a largo plazo para instituciones con alto volumen de uso.</td><td colspan="3" valign="top">Sigue un modelo de suscripción anual, con precios desde $3,000 anuales dependiendo del tamaño de la biblioteca y módulos contratados. Los precios pueden incluir costos de implementación y capacitación del personal.</td><td colspan="3" valign="top">Opera con modelo de suscripción institucional, comenzando desde $2,500 anuales para instituciones pequeñas. Precios varían según número de usuarios y espacios gestionados. Incluye soporte e implementación básica.</td><td valign="top">Modelo de suscripción mensual desde $150 para bibliotecas pequeñas. Precios escalables según número de usuarios activos. No incluye hardware adicional, siendo la opción más económica pero con funcionalidades limitadas.</td></tr>
<tr><td colspan="3" valign="top"><b>Canales de distribución</b></td><td colspan="3" valign="top"><p>- Página web institucional</p><p>- Aplicaciones móviles iOS y Android</p><p>- Panel web para administradores</p></td><td colspan="3" valign="top"><p>- Página web</p><p>- Integración con sistemas bibliotecarios existentes</p><p>- Aplicaciones móviles</p></td><td colspan="3" valign="top"><p>- Plataforma web institucional</p><p>- APIs para integración</p><p>- Aplicaciones móviles</p></td><td valign="top"><p>- Página web</p><p>- Aplicaciones móviles iOS y Android</p></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td><td colspan="3" valign="top"><b>Fortalezas</b></td><td colspan="3" valign="top"><p>- Detección automática de ocupación en tiempo real.</p><p>- Especialización en bibliotecas universitarias.</p><p>- App ligera con actualizaciones rápidas.</p><p>- Instalación simple de sensores IoT.</p></td><td colspan="3" valign="top"><p>- Plataforma madura y establecida.</p><p>- Amplia integración con sistemas bibliotecarios.</p><p>- Funcionalidades completas de gestión.</p><p>- Base sólida de clientes académicos.</p></td><td colspan="3" valign="top"><p>- Versatilidad para diferentes tipos de espacios.</p><p>- Interfaz robusta y escalable.</p><p>- Buena integración institucional.</p><p>- Soporte técnico establecido.</p></td><td valign="top"><p>- Fácil de implementar y usar.</p><p>- Costos accesibles.</p><p>- Enfoque simple y directo.</p><p>- Sin requerimientos de hardware.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Debilidades</b></td><td colspan="3" valign="top"><p>- Requiere inversión en hardware IoT.</p><p>- Producto nuevo en el mercado.</p><p>- Necesidad de validación en más instituciones.</p></td><td colspan="3" valign="top"><p>- Sin detección automática de ocupación.</p><p>- Costos elevados para bibliotecas pequeñas.</p><p>- Interfaz compleja para usuarios básicos.</p></td><td colspan="3" valign="top"><p>- No especializado en bibliotecas.</p><p>- Falta de integración IoT.</p><p>- Menos enfocado en experiencia estudiantil.</p></td><td valign="top"><p>- Dependiente de actualización manual.</p><p>- Funcionalidades limitadas.</p><p>- Sin monitoreo automático.</p><p>- Reportes básicos.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Oportunidades</b></td><td colspan="3" valign="top"><p>- Expansión a bibliotecas públicas.</p><p>- Integración con sistemas académicos.</p><p>- Desarrollo de analíticas predictivas.</p><p>- Escalamiento internacional.</p></td><td colspan="3" valign="top"><p>- Adopción de tecnologías IoT.</p><p>- Expansión en mercados emergentes.</p><p>- Nuevos módulos especializados.</p></td><td colspan="3" valign="top"><p>- Especialización en sector bibliotecario.</p><p>- Integración de tecnologías emergentes.</p><p>- Alianzas con proveedores IoT.</p></td><td valign="top"><p>- Mejora con detección automática.</p><p>- Expansión de funcionalidades.</p><p>- Integración con sistemas bibliotecarios.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Amenazas</b></td><td colspan="3" valign="top"><p>- Competencia de plataformas establecidas.</p><p>- Resistencia al cambio en instituciones conservadoras.</p><p>- Posible copia del modelo por competidores.</p></td><td colspan="3" valign="top"><p>- Nuevas tecnologías disruptivas.</p><p>- Soluciones IoT más avanzadas.</p><p>- Reducción de presupuestos bibliotecarios.</p></td><td colspan="3" valign="top"><p>- Competencia especializada en bibliotecas.</p><p>- Tecnologías de automatización.</p><p>- Preferencias por soluciones integradas.</p></td><td valign="top"><p>- Soluciones con detección automática.</p><p>- Plataformas más completas.</p><p>- Cambios en preferencias institucionales.</p></td></tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Hemos empleado un análisis FODA para identificar las posibilidades y desafíos en el mercado de gestión de espacios bibliotecarios, así como para evaluar nuestras fortalezas y debilidades internas. Esta metodología nos ha permitido concebir estrategias y tácticas que se ajusten de manera coherente a nuestro entorno y a los recursos disponibles.

**Estrategia de diferenciación tecnológica:**

La principal estrategia de Bib Flip es posicionarse como la única solución en el mercado bibliotecario que incorpora tecnología IoT para detectar en tiempo real la ocupación de cubículos, eliminando completamente la dependencia de actualizaciones manuales o estimaciones. Esto permite ofrecer a estudiantes y personal bibliotecario información confiable y constante sobre disponibilidad, algo que nuestros competidores no logran con la misma precisión ni automatización.

**Estrategia de enfoque especializado en bibliotecas universitarias:**

Una estrategia clave es enfocarse específicamente en el área de bibliotecas universitarias, a diferencia de competidores que abordan múltiples tipos de espacios institucionales. Bib Flip se especializa en entender las necesidades únicas del entorno bibliotecario universitario, donde la alta rotación estudiantil, los períodos de exámenes y la necesidad de espacios silenciosos son fundamentales. De esta manera, podemos enfocarnos en priorizar la experiencia y otorgarle muchos más beneficios a nuestro público objetivo original.

**Estrategia de experiencia estudiantil superior:**

Bib Flip adopta una estrategia centrada en la experiencia del estudiante, ofreciendo una aplicación móvil intuitiva que no solo muestra disponibilidad sino que predice patrones de uso y sugiere mejores horarios. Además, se implementan notificaciones inteligentes y reservas con recordatorios automáticos.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

## **Personal de bibliotecas universitarias**

Buenas tardes, gracias por asistir a esta entrevista

### **Preguntas de presentación:**

1. ¿Podrías indicarnos tu nombre y edad?
2. ¿Qué puesto ocupas dentro del personal de la biblioteca?
3. ¿Desde cuándo trabajas en esta biblioteca y cuál es su capacidad aproximada?

### **Preguntas Específicas:**
1. ¿Cómo se gestionan actualmente las reservas y la disponibilidad de los cubículos?
2. ¿Cúales son los problemas más comunes que enfrenta la biblioteca con la ocupación de espacios durante épocas de alta demanda (exámenes, entregas)?
3. ¿Cuáles consideras que son las características más relevantes que debería incluir una plataforma de gestión de aforo para bibliotecas?
4. ¿Le parece interesante una solución tecnológica con dispositivos IOT para gestionar los espacios de estudio en tiempo real?
5. ¿Qué nivel de importancia le darías a la facilidad de instalación y mantenimiento del sistema?
6. ¿Cómo crees que la tecnología puede mejorar la experiencia de los estudiantes y optimizar la gestión de espacios de la biblioteca? 
7. ¿Qué datos o métricas les gustaría obtener sobre el uso de los cubículos estudiantiles?

---

## **Estudiantes universitarios**

Buenas tardes, gracias por asistir a esta entrevista

### **Preguntas de presentación:**
1. ¿Podrías indicarnos tu nombre y carrera?
2. ¿Cuál es tu edad?
3. ¿Con qué frecuencia sueles usar la biblioteca para estudiar?

### **Preguntas Específicas:**
1. ¿Cómo sueles verificar la disponibilidad de espacios de estudio antes de ir a la biblioteca?
2. ¿Para ti qué características debería tener una app de biblioteca para que la uses con frecuencia?
3. ¿Qué importancia le darías a la rapidez y facilidad de uso en una aplicación diseñada para gestionar tu experiencia de estudio en la reserva de cubículos estudiantiles?
4. ¿Te interesaría recibir notificaciones sobre la disponibilidad de tu cubículo o computadora preferida?
5. ¿Has tenido experiencias frustrantes buscando lugar para estudiar? ¿Podrías contarnos sobre ellas?
6. ¿Algo más que consideras importante para mejorar tu experiencia como usuario de la biblioteca?

---

### 2.2.2. Registro de entrevistas

Se realizaron tres entrevistas para cada segmento objetivo y estas se encuentran registradas en el siguiente enlace: [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218167_upc_edu_pe/EbipDl3neqpBkcsL2Ewh0tIBwZL3w3QbSfnV5e7A5g833w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=h1Nh0k`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218167_upc_edu_pe/EbipDl3neqpBkcsL2Ewh0tIBwZL3w3QbSfnV5e7A5g833w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=h1Nh0k)

### Entrevistas para el Segmento Objetivo 1 - Personal Bibliotecario

---

#### Entrevista N°1:

*Entrevistado:* Juan Carlos Villanueva<br>
*Sexo:* Masculino <br>
*Edad:* 39 años<br>
*Domicilio:* Lima<br>
*Inicio de la Entrevista:* 0:12<br>
*Fin de la Entrevista:* 4:44<br>

<a href="https://ibb.co/cc9QkCvm"><img src="https://i.postimg.cc/HW8V6RbH/Captura-de-pantalla-2025-09-17-211456.png" alt="Entrevista con Nasthya" style="width: 600px; height: auto;"><br></a>

*Resumen de la Entrevista:* <br>
Durante la entrevista con Juan Carlos Villanueva, miembro del personal administrativo de la biblioteca, se nos comenta que para la reserva de cubículos en la biblioteca de la UPC se viene utilizando la misma plataforma web desde hace unos años. Por ello, él considera interesante la adición de tecnologías IoT para mejorar la gestión y reserva de cubículos. Sin embargo, menciona que debería hacerse un estudio previo para analizar si la relación entre el beneficio y el costo es realmente positiva.


#### Entrevista N°2:

*Entrevistado:* Alonso Rafael<br>
*Sexo:* Masculino <br>
*Edad:* 26 años<br>
*Domicilio:* Lima<br>
*Inicio de la Entrevista:* 4:45<br>
*Fin de la Entrevista:* 7:50 <br>

[![image.png](https://i.postimg.cc/SxFB322F/image.png)](https://postimg.cc/Tp0NWPJC)

*Resumen de la Entrevista:* <br>
Durante la entrevista con Alonso Rafael, de 26 años y miembro del personal administrativo de la biblioteca, se nos indicó que uno de los aspectos que más le interesaría mejorar es la visualización del aforo en cada cubículo en tiempo real. Alonso considera que una solución tecnológica que permita conocer la disponibilidad inmediata de los espacios sería muy útil, especialmente en épocas de alta demanda. Según comenta, esto ayudaría a reducir significativamente los tiempos de espera para los estudiantes y permitiría una mejor organización del uso de los espacios dentro de la biblioteca.


#### Entrevista N°3:

*Entrevistado:* Jorge Luis Céspedes<br>
*Sexo:* Masculino <br>
*Edad:* 46 años<br>
*Domicilio:* Lima<br>
*Inicio de la Entrevista:* 7:51<br>
*Fin de la Entrevista:* 10:57<br>

[![Captura-de-pantalla-2025-09-18-150756.png](https://i.postimg.cc/DyN3Yskp/Captura-de-pantalla-2025-09-18-150756.png)](https://postimg.cc/SJcPnnKc)

*Resumen de la Entrevista:* <br>
Durante la entrevista con Jorge Luis Céspedes, de 46 años y parte del equipo de atención a estudiantes de la biblioteca, se destacó la necesidad de contar con un sistema más ágil y confiable para la gestión de espacios. Jorge, quien trabaja en la biblioteca desde hace 3 años, señaló que los principales problemas durante épocas de alta demanda incluyen la lentitud del sistema actual, reservaciones no utilizadas y reclamos de estudiantes que no logran acceder a espacios reservados. Considera muy importante que una solución IoT sea fácil de instalar y mantener, y destaca la necesidad de obtener métricas detalladas como horarios de mayor demanda, porcentaje de ocupación real y tiempo promedio de permanencia para optimizar la gestión de los espacios de estudio.



### Entrevista para el Segmento Objetivo 2 - Estudiantes Universitarios

---

#### Entrevista N°1:

*Entrevistado:* Nasthya del Carpio<br>
*Sexo:* Femenino <br>
*Edad:* 21 años<br>
*Domicilio:* La Perla<br>
*Inicio de la Entrevista:* 10:58<br>
*Fin de la Entrevista:* 15:32<br>

<a href="https://ibb.co/cc9QkCvm"><img src="https://i.ibb.co/C5yQmMtr/entrevista-na.png" alt="Entrevista con Nasthya" style="width: 600px; height: auto;"><br></a>


*Resumen de la Entrevista:* <br>
La entrevista con Nasthya del Carpio, estudiante de 21 años de Diseño de Interiores en la UPC, mostró que suele usar la biblioteca entre 2 y 4 veces por semana, pero enfrenta dificultades para verificar la disponibilidad de cubículos debido a la falta de información confiable. Destacó que una app debería ser rápida, sencilla y mostrar la ocupación en tiempo real, con funciones de reserva, cancelación y notificaciones personalizables. Compartió experiencias frustrantes al no encontrar espacios libres o al hallar ocupado un cubículo reservado, y resaltó la importancia de contar con un sistema de feedback y de garantizar la privacidad de los usuarios.

#### Entrevista N°2:
*Entrevistado:* David Rivas  
*Sexo:* Masculino  
*Edad:* 22 años  
*Domicilio:* San Miguel  
*Inicio de la Entrevista:* 15:37  
*Fin de la Entrevista:* 19:28  

[![Captura-de-pantalla-2025-09-18-114414.png](https://i.postimg.cc/pXpNDdVk/Captura-de-pantalla-2025-09-18-114414.png)](https://postimg.cc/XpSDW4Cy)

*Resumen de la Entrevista:*  
David Rivas, estudiante de 22 años de Ingeniería de Sistemas, utiliza la biblioteca principalmente durante épocas de exámenes y proyectos finales, visitándola aproximadamente 3 veces por semana. Su principal problema es la pérdida de tiempo al buscar cubículos disponibles, especialmente en horas pico. Considera esencial que una aplicación permita visualizar mapas de la biblioteca con disponibilidad en tiempo real y la posibilidad de reservar espacios por períodos específicos. Mencionó la importancia de tener filtros por tipo de espacio (silencioso, colaborativo, individual) y sugirió implementar un sistema de penalización para usuarios que no cancelen sus reservas. También valoró la integración con el calendario académico para anticipar períodos de alta demanda.


#### Entrevista N°3:
*Entrevistado:* Renzo Silva  
*Sexo:* Masculino  
*Edad:* 20 años  
*Domicilio:* Pueblo Libre  
*Inicio de la Entrevista:* 19:30  
*Fin de la Entrevista:* 22:27 

[![Captura-de-pantalla-2025-09-18-114011.png](https://i.postimg.cc/y8cF5FYd/Captura-de-pantalla-2025-09-18-114011.png)](https://postimg.cc/zyDbHHhZ)

*Resumen de la Entrevista:*  
Renzo Silva, estudiante de 20 años de Ing. de Software, frecuenta la biblioteca diariamente para estudios grupales e individuales. Su mayor frustración es encontrar cubículos reservados pero vacíos, lo que considera una pérdida de recursos. Propuso que la aplicación incluya verificación de ocupación mediante sensores o check-in manual, y un sistema de liberación automática si el usuario no confirma su llegada en un tiempo determinado. Destacó la necesidad de poder extender reservas desde la app y recibir recordatorios antes del vencimiento. También sugirió funciones sociales como compartir mesa con compañeros conocidos y un sistema de reputación para usuarios responsables. Consideró importante que la app funcione offline para mostrar reservas activas.

### 2.2.3. Análisis de entrevistas

#### Segmento Objetivo 1: Personal Bibliotecario

##### Insights principales:

- Tecnología actual limitada: El personal bibliotecario utiliza la misma plataforma web desde hace años, lo que indica una oportunidad de modernización.
- Apertura a la innovación: Juan Carlos muestra interés en la implementación de tecnologías IoT para mejorar la gestión de cubículos.
- Enfoque en cost-benefit: El personal administrativo prioriza un análisis previo que demuestre que la relación beneficio-costo es positiva antes de implementar nuevas soluciones.
- Experiencia operativa: Su conocimiento del sistema actual les permite identificar las limitaciones y oportunidades de mejora.

##### Necesidades identificadas:

- Sistema más eficiente para gestionar reservas
- Herramientas de monitoreo en tiempo real
- Justificación clara del retorno de inversión
- Integración con procesos administrativos existentes

---

#### Segmento Objetivo 2: Estudiantes Universitarios

##### Insights principales:

- Uso frecuente: Nasthya utiliza la biblioteca 2-4 veces por semana, indicando una alta demanda de estos espacios.
- Frustración con la disponibilidad: La falta de información confiable sobre ocupación genera experiencias negativas recurrentes.
- Expectativas de inmediatez: Los estudiantes esperan información en tiempo real y procesos rápidos y sencillos.
- Experiencias problemáticas: Situaciones donde encuentran cubículos ocupados a pesar de aparecer disponibles, o viceversa.

##### Necesidades identificadas:

Las necesidades fundamentales que se han detectado se enfocan en disponer de información real y actualizada sobre la disponibilidad de un cubículo, junto con un procedimiento de reserva eficaz y sencillo que permita la actualización del estado del cubículo.  Además, es necesario tener la opción de personalizar las notificaciones, contar con un sistema de retroalimentación que facilite el reporte de problemas e incidencias y disponer de garantías robustas en cuanto a la privacidad y seguridad del manejo de los datos del usuario.

---

#### Patrones comunes entre segmentos:

Ambos reconocen las limitaciones del sistema actual
Existe disposición para adoptar nuevas tecnologías
Se valora la eficiencia y la confiabilidad del sistema
Hay una necesidad compartida de información en tiempo real

## 2.3. Needfinding

### 2.3.1. User Personas

Personal Bibliotecario

[![user-persona-1.png](https://i.postimg.cc/gcwXNWjc/user-persona-1.png)](https://postimg.cc/Z0S55X6X)

Estudiantes Universitarios

[![user-persona-2.png](https://i.postimg.cc/SR5PhzzK/user-persona-2.png)](https://postimg.cc/y3mjhxjq)

### 2.3.2. User Task Matrix

**Personal Bibliotecario (Javier)**

| Tarea | Importancia | Frecuencia |
|:------|:------|:----------|
|Consultar el estado de ocupación de cubículos en tiempo real|Alta|Alta|
|Agregar/modificar cubículos desde el panel administrativo|Media|Media|
|Gestionar reservas y cancelaciones desde el panel|Alta|Alta|
|Configurar parámetros del sistema (horarios, límites de tiempo, etc.)|Media|Baja|
|Supervisar que el sistema de reservas funcione correctamente|Alta|Alta|
|Generar reportes de uso y estadísticas para gestión operativa|Alta|Media|
|Enviar notificaciones automáticas a estudiantes sobre sus reservas|Media|Media|

**Estudiantes Universitarios (Miriam)**

| Tarea | Importancia | Frecuencia |
|:------|:------|:----------|
|Consultar disponibilidad de cubículos en tiempo real|Alta|Alta|
|Reservar cubículos de estudio individual rápidamente|Alta|Alta|
|Acceder al sistema desde el celular de manera fácil|Alta|Alta|
|Recibir recordatorios de su reserva y tiempo restante|Alta|Media|
|Cancelar o modificar reservas existentes|Media|Media|
|Liberar cubículo antes del tiempo límite si terminan antes|Media|Media|
|Buscar cubículos disponibles por ubicación en la biblioteca|Media|Media|
| Disminuir la cantidad de pasos requeridos para efectuar la reserva | Alta | Alta

### 2.3.3. Empathy Mapping

[![Empathy-map-Javier.png](https://i.postimg.cc/pTGMBcph/Empathy-map-Javier.png)](https://postimg.cc/CBq2hNCS)

Estudiantes Universitarios

[![Empathy-map-Miriam.png](https://i.postimg.cc/FRsQ3XsX/Empathy-map-Miriam.png)](https://postimg.cc/DWDD3DXx)

### 2.3.4. As-is Scenario Mapping

Este mapeo "As-Is" presenta el escenario actual antes de la implementación de Bibflip, describiendo las experiencias problemáticas para nuestros dos segmentos. Para ello, se detallan acciones, pensamientos y emociones que reflejan las frustraciones y limitaciones del proceso actual.

### ¿Qué hace el Personal de la Biblioteca?

| **Phases** | **Gestión matutina** | **Supervisión de reservas** | **Atención al estudiante** | **Generación de reportes** |
|------------|---------------------|--------------------------|---------------------------|---------------------------|
| **Doing** | • Llega y revisa el estado de cubículos.<br>• Accede al sistema web convencional.<br>• Verifica reservas pendientes del día. | • Realiza rondas físicas por la biblioteca.<br>• Supervisa el uso adecuado de los cubículos.<br>• Contrasta información del sistema con la realidad. | • Recibe consultas sobre disponibilidad de cubículos.<br>• Media conflictos por dobles reservas.<br>• Proporciona información desactualizada. | • Compila estadísticas basándose en datos incompletos.<br>• Intenta generar reportes con información manual.<br>• Prepara informes para administración. |
| **Thinking** | "Necesito verificar manualmente todo porque el sistema no es confiable." <br> "Este proceso consume mucho tiempo cada mañana." | "El sistema no refleja la ocupación real de los cubículos." <br> "Tengo que caminar constantemente para verificar el uso apropiado." | "No puedo dar información precisa a los estudiantes." <br> "Estos conflictos se repiten por fallas del sistema." | "Los datos que manejo no reflejan la realidad del uso." <br> "¿Cómo justificar mejoras sin datos precisos?" |
| **Feeling** | • Resignación | • Cansancio | • Estrés | • Insatisfacción <br> • Preocupación |

### ¿Qué hace el Estudiante?

| **Phases** | **Descubrimiento del sistema** | **Proceso de reserva** | **Búsqueda física de cubículos** | **Uso del cubículo** |
|------------|------------------------------|------------------------|----------------------------------|-------------------|
| **Doing** | • Accede al sistema universitario complejo.<br>• Navega por múltiples interfaces. | • Completa formularios con muchos pasos.<br>• Escribe manualmente códigos de confirmación.<br>• Espera confirmaciones del sistema lento. | • Camina por toda la biblioteca buscando cubículos libres.<br>• Pregunta al personal sobre disponibilidad.<br>• Pierde tiempo verificando espacios ocupados. | • Llega y encuentra su cubículo ocupado por otros.<br>• Espera a que desocupen o busca alternativas.<br>• Negocia con otros estudiantes el uso del espacio. |
| **Thinking** | "Este sistema es muy complicado para algo tan simple." <br> "¿Por qué tantos pasos para reservar un cubículo?" | "Espero no olvidarme de escribir el código de confirmación." <br> "El proceso es demasiado largo." | "Ojalá hubiera una forma de saber qué está disponible sin caminar tanto." <br> "Estoy perdiendo tiempo valioso buscando." | "¿Cómo es posible que mi cubículo reservado esté ocupado?" <br> "En época de exámenes esto puede afectarme mucho." |
| **Feeling** | • Confusión <br> • Frustración | • Ansiedad <br> • Impaciencia | • Cansancio <br> • Desesperación | • Enojo <br> • Estrés |


# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
Este mapeo “To-Be” presenta el escenario ideal posterior a la implementación de Bibflip, describiendo cómo cambiarán las experiencias del propietario del centro de estudio y del usuario gracias a la solución IoT propuesta. Se detallan acciones, pensamientos y emociones alineadas a los beneficios que aporta el sistema.

### ¿Qué hace el  Administrador biblioteca universitarios?

| **Phases**                     | **Doing**                                                                                          | **Thinking**                                           | **Feeling**               |
|-------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------|---------------------------|
| **Registro del local**        | • Instala la app Bibflip.  <br> • Crea su cuenta como dueño del centro.  <br> • Registra su centro de estudio y sedes. | • “Qué bueno que puedo registrar todas mis sedes fácil.” <br> • “Ahora tengo visibilidad online.” | • Aliviado <br> • Organizado |
| **Gestión del aforo**         | • Consulta la ocupación en tiempo real de su sede. <br> • Revisa cada sede desde su celular o computadora.                    | • “Qué fácil es ver cuántos cubículos están ocupados.” <br> • “Ya no dependo del personal para esto.” <br>• “Qué accesible que pueda ver desde cualquier dispositivo la app de Bibflip.” | • En control <br> • Eficiente  |
| **Gestión del tiempo de espera** | • Ve cómo los estudiantes reservan online. <br> • Evita filas innecesarias en la entrada.                             | • “Qué bueno que ya no hay colas innecesarias.” <br> • “Mis usuarios llegan más contentos.”      | • Relajado <br> • Optimista   |
| **Monitoreo de cubículos**        | • Agrega o elimina cubículos. <br> • Coordina instalación de sensores IoT.                              | • “Wow, es sencillo gestionar los cubículos con ayuda.” <br> • “No imaginé tanta flexibilidad.”      | • Empoderado <br> • Innovador  |

### ¿Qué hace el Usuario?

| Phases | Descubrimiento de la aplicación | Registro de datos personales | Búsqueda de cubículos | Reserva de cubículo |
|--------|-------------------------------|----------------------------|------------------------|-------------------|
| **Doing** | • Descarga Bibflip desde la tienda de aplicaciones.<br>• Explora las funcionalidades principales. | • Registra sus datos en Bibflip.<br>• Configura sus centros favoritos. | • Utiliza la función de búsqueda por ubicación.<br>• Revisa la disponibilidad en tiempo real. | • Selecciona un cubículo disponible.<br>• Confirma la reserva para una hora específica. |
| **Thinking** | "Esta app me ayudará a no perder tiempo buscando cubículos disponibles." | "El proceso de registro es rápido." | "Me encanta poder ver exactamente dónde hay espacio antes de ir." | "La reserva fue sencilla y ahora tengo mi lugar asegurado." |
| **Feeling** | Curiosidad | Comodidad | Alivio | Satisfacción |


## 3.2. User Stories

## Epics
| Epic ID 	| Name 	|
|:---:	|:---:	|
| EPIC-LANDING-001 	| Funcionalidades landing page 	|
| EPIC-CLIENT-002 	| Funcionalidades user estudiante 	|
| EPIC-ADMIN-003 	| Funcionalidades user administrador 	|
| EPIC-SUPERADMIN-004 	| Funcionalidades user superadmin 	|
| EPIC-BOOKING-TECH 	| Funcionalidades de desarrolladores 	|

| Story ID 	| Título 	| Descripción 	| Epic ID 	| Usuario 	| Criterios de aceptación 	|
|---	|---	|---	|---	|---	|---	|
| US001 	| Ver sección "¿Qué es Bibflip?" 	| Como visitante de la página, quiero entender qué es Bibflip desde la landing page para conocer su propósito y cómo puede ayudarme como estudiante o administrador de un centro de estudio. 	| EPIC-LANDING-001 	| Visitante landing page 	| Escenario 1:<br>Dado que el visitante accede a la landing page,<br>Cuando hace scroll en "¿Qué es Bibflip?",<br>Entonces el sistema le muestra la sección donde se describe claramente el objetivo de la solución.<br><br>Escenario 2:<br>Dado que el visitante accede a la landing page,<br>Cuando hace click en "¿Qué es Bibflip?",<br>Entonces el sistema le muestra la sección donde se describe claramente el objetivo de la solución. 	|
| US002 	| Ver sección "Características clave" 	| Como visitante, quiero revisar una lista de características principales de Bibflip para evaluar si cubre mis necesidades como usuario final o administrador. 	| EPIC-LANDING-001 	| Visitante landing page 	| Escenario 1:<br>Dado que el usuario navega la landing,<br>Cuando cuando hace scroll a la sección "Características clave",<br>Entonces el sistema le muestra un resumen de las funcionalidades más importantes del sistema.<br><br>Escenario 2:<br>Dado que el visitante está en la landing,<br>Cuando da click sobre el botón "Características clave",<br>Entonces el sistema le muestra un resumen de las funcionalidades más importantes del sistema. 	|
| US003 	| Ver la galería virtual 	| Como visitante, quiero ver una galería virtual en la landing para visualizar cómo luce Bibflip, su interfaz y los sensores en acción. 	| EPIC-LANDING-001 	| Visitante landing page 	| Escenario 1:<br>Dado que el usuario navega la landing,<br>Cuando cuando hace scroll a la sección "Galería Virtual"<br>Entonces visualiza el contenido visual ilustrativo del sistema en uso<br><br>Escenario 2:<br>Dado que el usuario navega la landing,<br>Cuando cuando hace click a la sección "Galería Virtual"<br>Entonces visualiza el contenido visual ilustrativo del sistema en uso 	|
| US004 	| Usar el formulario de contacto 	| Como visitante interesado, quiero tener acceso a un formulario o medio de contacto en la landing para comunicarme con el equipo de Bibflip. 	| EPIC-LANDING-001 	| Visitante landing page 	| Escenario 1:<br>Dado que el visitante accede a "Contáctanos"<br>Cuando completa el formulario con sus datos<br>Entonces el sistema debe notificar al equipo de Bibflip<br><br>Escenario 2:<br>Dado que el visitante intenta enviar el formulario,<br>Cuando deja campos obligatorios vacíos,<br>Entonces el sistema debe mostrar mensajes de validación para completar la información. 	|
| US005 	| Ver menú digital de una sede 	| Como estudiante, quiero visualizar el reglamento o servicios del centro de estudio para conocer la oferta disponible antes de asistir. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que el estudiante accede a la plataforma,<br>Cuando le da click a la sección "Servicios",<br>Entonces el sistema debe mostrar la información completa de la sede.<br><br>Escenario 2:<br>Dado que el estudiante visualiza la lista,<br>Cuando selecciona una categoría como “Cubículos” o “Salas grupales”,<br>Entonces el sistema filtra los servicios mostrados según esa categoría. 	|
| US006 	| Visualizar reserva activa 	| Como estudiante, quiero poder visualizar mi reserva activa desde la aplicación, para confirmar los detalles de mi cubículo y el horario reservado antes de llegar al centro de estudio. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que el estudiante ha iniciado sesión en la plataforma<br>Y tiene al menos una reserva activa,<br>Cuando accede a la sección principal,<br>Entonces el sistema le muestra la información de la reserva actual incluyendo horario, sede y número de cubículo.<br><br>Escenario 2:<br>Dado que el estudiante visualiza su reserva,<br>Cuando esta ya ha expirado,<br>Entonces el sistema la remueve de la sección activa. 	|
| US007 	| Ver disponibilidad de cubículos en tiempo real 	| Como estudiante, quiero conocer la disponibilidad de cubículos para decidir a qué sede acudir. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que el estudiante accede a la plataforma<br>Cuando le da click a la sección "Explorar Sedes"<br>Entonces el sistema debe mostrarle la información de la sedes con sus respectivos aforos disponibles<br><br>Escenario 2:<br>Dado que el estudiante visualiza el estado de aforo de las sedes<br>Cuando hay una actualización desde los sensores<br>Entonces el sistema debe reflejar el nuevo estado en menos de 5 segundos<br><br>Escenario 3:<br>Dado que todos los cubículos están ocupados en una sede<br>Cuando el estudiante visualiza la disponibilidad<br>Entonces el sistema debe informar que no hay cubículos disponibles actualmente 	|
| US008 	| Reservar un cubículo 	| Como estudiante, quiero reservar un cubículo para asegurarme un lugar al llegar al centro de estudio. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que el estudiante selecciona una sede en la sección "Explorar Sedes"<br>Cuando el estudiante selecciona la hora aproximada de estadía<br>Y selecciona un cubículo disponible<br>Entonces el sistema debe permitir realizar la reserva<br><br>Escenario 2:<br>Dado que el estudiante ya tiene una reserva activa<br>Cuando intenta crear una nueva<br>Entonces el sistema debe evitarlo e informar que ya tiene una reserva activa 	|
| US009 	| Visualizar más sedes en un mapa 	| Como estudiante, quiero poder ver más sedes en el mapa para poder identificar la más cercana. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que el estudiante quiere ver más sedes<br>Cuando le da click a la sección "Sedes"<br>Entonces el sistema debe mostrar todas las sedes del centro de estudio<br><br>Escenario 2:<br>Dado que el estudiante se encuentra en la sección "Sedes"<br>Y puede ver todas las sedes<br>Cuando le da click al botón de "Ver en mapa"<br>Entonces el sistema muestra un pop up con la dirección en un mapa interactivo 	|
| US010 	| Registro de cuenta de estudiante 	| Como visitante, quiero poder registrarme como estudiante en el sistema Bibflip para poder acceder a las funcionalidades de reserva y visualización de cubículos. 	| EPIC-CLIENT-002 	| Visitante 	| Escenario 1:<br>Dado que un visitante accede a la plataforma<br>Cuando completa el formulario de registro con nombre y contraseña<br>Y acepta los términos y condiciones<br>Entonces el sistema debe crear una cuenta nueva<br>Y permitir el acceso a las funcionalidades de estudiante<br><br>Escenario 2:<br>Dado que un visitante intenta registrarse con un nombre de usuario ya usado,<br>Cuando envía el formulario,<br>Entonces el sistema debe impedir el registro y mostrar un mensaje de error indicando que el correo ya está registrado. 	|
| US011 	| Inicio de sesión de cuenta de estudiante 	| Como estudiante registrado, quiero poder iniciar sesión en el sistema para acceder a mis reservas y funcionalidades personalizadas. 	| EPIC-CLIENT-002 	| Estudiante 	| Escenario 1:<br>Dado que un estudiante registrado accede a la pantalla de login<br>Cuando ingresa sus credenciales correctas (email y contraseña)<br>Entonces el sistema debe autenticarlo<br>Y redirigirlo al dashboard principal<br><br>Escenario 2:<br>Dado que un usuario ingresa credenciales incorrectas<br>Cuando intenta iniciar sesión<br>Entonces el sistema debe mostrar un mensaje de error<br>Y permitir reintentar 	|
| US012 	| Agregar nuevos cubículos 	| Como administrador de sede, quiero agregar cubículos al sistema para gestionar mejor la ocupación. 	| EPIC-ADMIN-003 	| Administrador 	| Escenario 1:<br>Dado que el admin accede al panel de su sede<br>Cuando le da click a la sección "Gestión de Cubículos"<br>Y posteriormente a la opción "Agregar un nuevo cubículo"<br>Entonces el sistema le brinda un formulario simple de registro de cubículo.<br>Escenario 2:<br>Dado que el admin ingresa los datos correctos del cubículo como su identificador y capacidad<br>Y le da click al botón "Guardar"<br>Entonces el sistema guarda con su identificador y capacidad el cubículo registrado 	|
| US013 	| Visualizar reservas realizadas 	| Como administrador, quiero ver las reservas registradas en mi sede para planificar el servicio. 	| EPIC-ADMIN-003 	| Administrador 	| Escenario 1:<br>Dado que el administrador accede a su sede<br>Cuando le da clic a la sección "Visualizar Reservas"<br>Entonces el sistema debe mostrar las reservas con usuario, hora y cubículo<br><br>Escenario 2:<br>Dado que el administrador ha filtrado por persona o cubículo<br>Cuando aplica el filtro<br>Entonces el sistema debe mostrar solo las reservas que coinciden con los criterios seleccionados 	|
| US014 	| Ver la sede asignada 	| Como administrador, quiero confirmar qué sede tengo asignada para asegurarme de gestionar la correcta. 	| EPIC-ADMIN-003 	| Administrador 	| Escenario 1:<br>Dado que el administrador inicia sesión<br>Cuando accede a su información<br>Entonces el sistema debe mostrar la sede asociada a su cuenta<br><br>Escenario 2:<br>Dado que el administrador tiene asignada una sede<br>Cuando intenta acceder a otra sede que no le corresponde<br>Entonces el sistema le impide el acceso 	|
| US015 	| Eliminar cubículos 	| Como administrador, quiero poder eliminar cubículos que ya no están en uso en mi sede, para mantener el sistema actualizado y evitar asignaciones incorrectas. 	| EPIC-ADMIN-003 	| Administrador 	| Escenario 1:<br>Dado que el administrador ha iniciado sesión<br>Y se encuentra en la sección "Ver Cubículos"<br>Cuando selecciona un cubículo existente<br>Y confirma su eliminación<br>Entonces el cubículo es eliminado del sistema<br>Y deja de aparecer en la lista<br><br>Escenario 2:<br>Dado que el cubículo tiene una reserva activa<br>Cuando el administrador intenta eliminarlo<br>Entonces el sistema debe impedir la eliminación<br>Y mostrar un mensaje indicando que no puede eliminar cubículos con reservas activas 	|
| US016 	| Inicio de sesión de administrador 	| Como administrador, quiero poder iniciar sesión en el sistema con mis credenciales específicas para acceder al panel de administración de mi sede. 	| EPIC-ADMIN-003 	| Administrador 	| Escenario 1:<br>Dado que un administrador accede a la pantalla de login<br>Cuando ingresa sus credenciales válidas<br>Entonces el sistema debe autenticarlo<br>Y mostrar el panel de administración con las funcionalidades asociadas a su sede<br><br>Escenario 2:<br>Dado que un administrador ingresa credenciales incorrectas<br>Cuando intenta acceder<br>Entonces el sistema debe mostrar un mensaje de error<br>Y registrar el intento fallido por seguridad 	|
| US017 	| Registro de cuenta de administrador 	| Como superadministrador, quiero poder registrar administradores como administradores de una sede en el sistema Bibflip para que puedan acceder a las funcionalidades de ver reservas y la gestión de cubículos. 	| EPIC-SUPERADMIN-004 	| Superadmin 	| Escenario 1:<br>Dado que un superadmin se encuentra en su cuenta<br>Cuando se dirija a la sección de "Administradores"<br>Y da click a agregar administrador<br>Entonces puede registrar un administrador y asignarle una sede<br><br>Escenario 2:<br>Dado que un superadmin ha registrado a un administrador<br>Cuando se dirije a la sección de "Administradores"<br>Entonces puede visualizar los administradores que ha registrado 	|
| US018 	| Acceder a todos los módulos del sistema 	| Como superadmin, quiero tener acceso a todas las funcionalidades del sistema para realizar pruebas, crear sedes y admins. 	| EPIC-SUPERADMIN-004 	| Superadmin 	| Escenario 1:<br>Dado que el superadmin accede al sistema<br>Cuando desea visualizar sedes o usuarios<br>Entonces el sistema debe permitirle ver toda la información<br><br>Escenario 2:<br>Dado que el superadmin crea un nuevo admin o sede<br>Cuando registra los datos<br>Entonces el sistema debe almacenarlos y mostrar confirmación 	|




## Technical Stories

| Story ID     | Título                                     | Descripción                                                                                                                                      | Epic ID             | Usuario   | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                      |
|--------------|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TS001 | Implementar Endpoint para Obtener Cubículos | Como Developer, quiero implementar un endpoint de API que permita a las aplicaciones frontend obtener la lista de cubículos disponibles en una biblioteca específica, para que los usuarios puedan ver el estado de ocupación. | EPIC-BOOKING-TECH   | Developer | **Escenario 1: Obtener cubículos disponibles exitosamente**<br>Dado que existe una biblioteca con cubículos registrados<br>Cuando un cliente solicita la lista de cubículos para esa biblioteca<br>Entonces el sistema responde con un código 200 OK y una lista de cubículos con su estado de ocupación.<br><br>**Escenario 2: Biblioteca no encontrada**<br>Dado que se solicita una biblioteca que no existe<br>Cuando el sistema intenta obtener los cubículos<br>Entonces el sistema responde con un código 404 Not Found. |
| TS002 | Procesar Datos de Sensor de Ocupación       | Como Developer, quiero implementar la lógica de backend para recibir y procesar los datos de ocupación enviados por los sensores IoT, para que el sistema actualice el estado de los cubículos en tiempo real. | EPIC-IOT-PROCESSING | Developer | **Escenario 1: Datos de ocupación recibidos y procesados**<br>Dado que el Edge API recibe datos de ocupación de un sensor<br>Cuando el backend procesa estos datos<br>Entonces el estado del cubículo correspondiente se actualiza en la base de datos.<br><br>**Escenario 2: Datos inválidos recibidos**<br>Dado que el Edge API recibe datos con formato inválido<br>Cuando el backend intenta procesarlos<br>Entonces el sistema registra un error y descarta los datos inválidos. |
| TS003 | Implementar Lógica de Reserva de Cubículo API | Como Developer, quiero implementar la lógica de backend para gestionar el proceso de reserva de cubículos a través de la API, asegurando la disponibilidad y registrando la reserva correctamente. | EPIC-BOOKING-TECH   | Developer | **Escenario 1: Reserva de cubículo exitosa**<br>Dado que un usuario solicita reservar un cubículo disponible<br>Cuando la lógica de reserva valida la disponibilidad y registra la reserva<br>Entonces la reserva se crea en la base de datos y el estado del cubículo se actualiza a "Reservado".<br><br>**Escenario 2: Cubículo no disponible**<br>Dado que un usuario intenta reservar un cubículo ya ocupado o reservado<br>Cuando la lógica de reserva valida la disponibilidad<br>Entonces el sistema rechaza la reserva y responde con un mensaje de error de disponibilidad. |
| TS004 | Implementar Firmware para Dispositivo IoT   | Como Developer, quiero desarrollar el firmware para el dispositivo IoT que detecta la ocupación de cubículos, para transmitir datos al Edge API. | EPIC-IOT-DEVICE     | Developer | **Escenario 1: Lectura de sensor correcta**<br>Dado que el dispositivo está conectado correctamente<br>Cuando el sensor detecta presencia<br>Entonces el firmware genera un paquete de datos con el estado de ocupación y lo transmite al Edge API.<br><br>**Escenario 2: Fallo de lectura del sensor**<br>Dado un fallo de hardware<br>Cuando se intenta leer el sensor<br>Entonces el firmware registra el error sin transmitir datos. |
| TS005 | Integrar Firmware con Plataforma Embebida   | Como Developer, quiero integrar el firmware en la plataforma embebida para que pueda iniciar, procesar datos y comunicarse vía red con el Edge. | EPIC-IOT-DEVICE     | Developer | **Escenario 1: Inicio correcto del sistema**<br>Dado que el sistema embebido arranca con configuración válida<br>Cuando se enciende el dispositivo<br>Entonces el sistema inicializa sensores y red sin errores.<br><br>**Escenario 2: Error de red**<br>Dado que la conexión de red falla<br>Cuando el sistema intenta establecer conexión<br>Entonces se lanza un mensaje de error y se reinicia el intento. |
| TS006 | Implementar Recepción de Datos en Edge API  | Como Developer, quiero implementar la lógica en el Edge API que reciba los datos enviados por los sensores IoT, para enviarlos al backend. | EPIC-IOT-PROCESSING | Developer | **Escenario 1: Datos recibidos correctamente**<br>Dado que un dispositivo IoT transmite datos válidos<br>Cuando el Edge API recibe el paquete<br>Entonces lo reenvía al backend y responde con un 200 OK.<br><br>**Escenario 2: Datos con formato incorrecto**<br>Dado que se recibe un paquete con formato inválido<br>Cuando se intenta procesarlo<br>Entonces el sistema registra el error y descarta el paquete. |
| TS007 | Simular Sensores en Wokwi                  | Como Developer, quiero simular el comportamiento del dispositivo IoT en Wokwi, para validar la lectura del sensor y la comunicación con el Edge API. | EPIC-IOT-DEVICE     | Developer | **Escenario 1: Simulación de detección de ocupación**<br>Dado que se ejecuta el circuito simulado en Wokwi<br>Cuando un peso es detectado por el sensor virtual<br>Entonces el sistema envía correctamente el estado al Edge API simulado.<br><br>**Escenario 2: Sensor inactivo**<br>Dado que el sensor no detecta peso<br>Cuando se revisa el estado<br>Entonces no se envía ninguna actualización. |



## 3.3. Impact Mapping

## Segmento 1: Personal de biblioteca universitaria
[![Impactmapadmin.jpg](https://i.postimg.cc/XJ29TCsV/Impactmapadmin.jpg)](https://postimg.cc/ft93dJ4F)

## Segmento 2: Estudiantes universitarios
[![Impactmapestudiante.jpg](https://i.postimg.cc/HsTCS8fJ/Impactmapestudiante.jpg)](https://postimg.cc/147TXXRP)

<!-- Contenido de Impact Mapping -->

## 3.4. Product Backlog
| #  | Story ID | Título                                    | Descripción                                                                                                                                              | Story Points |
|:--:|----------|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1  | US008    | Reservar un cubículo                      | Como usuario, quiero reservar un cubículo para asegurarme un espacio al llegar a la biblioteca.                                                           | 13           |
| 2  | US018    | Acceder a todos los módulos del sistema   | Como superadmin, quiero tener acceso a todas las funcionalidades del sistema para realizar pruebas, crear bibliotecas y admins.                          | 13           |
| 3  | US007    | Ver disponibilidad de cubículos en tiempo real | Como usuario, quiero conocer la disponibilidad de cubículos para decidir qué biblioteca visitar.                                                           | 8            |
| 4  | US012    | Agregar nuevos cubículos                  | Como administrador de biblioteca, quiero agregar cubículos al sistema para gestionar mejor la ocupación.                                                  | 5            |
| 5  | US009    | Visualizar más bibliotecas en un mapa     | Como usuario, quiero poder ver más bibliotecas en el mapa para poder identificar la más cercana.                                                          | 5            |
| 6  | US006    | Visualizar reserva activa                 | Como usuario, quiero poder visualizar mi reserva activa desde la aplicación, para confirmar los detalles de mi cubículo y el horario reservado.           | 5            |
| 7  | US013    | Visualizar reservas realizadas            | Como administrador, quiero ver las reservas registradas en mi biblioteca para planificar el servicio.                                                     | 5            |
| 8  | US017    | Registro de cuenta de administrador       | Como superadmin, quiero poder registrar administradores como responsables de una biblioteca en el sistema Bib Flip para gestionar reservas y cubículos.      | 5            |
| 9  | US005    | Ver catálogo digital de la biblioteca     | Como usuario, quiero visualizar el catálogo de la biblioteca para conocer los recursos disponibles antes de asistir.                                       | 3            |
| 10 | US004    | Usar el formulario de contacto            | Como visitante interesado, quiero tener acceso a un formulario o medio de contacto en la landing para comunicarme con el equipo de Bib Flip.                 | 3            |
| 11 | US014    | Ver la biblioteca asignada                | Como administrador, quiero confirmar qué biblioteca tengo asignada para asegurarme de gestionar la correcta.                                               | 3            |
  | 12 | US015    | Eliminar cubículos                        | Como administrador, quiero poder eliminar cubículos que ya no están en uso en mi biblioteca, para mantener el sistema actualizado y evitar asignaciones incorrectas. | 3    |
| 13 | US010    | Registro de cuenta de usuario             | Como visitante, quiero poder registrarme como usuario en el sistema Bib Flip para poder acceder a las funcionalidades de reserva y visualización de cubículos. | 3    |
| 14 | US011    | Inicio de sesión de usuario               | Como usuario registrado, quiero poder iniciar sesión en el sistema para acceder a mis reservas y funcionalidades personalizadas.                          | 3            |
| 15 | US016    | Inicio de sesión de administrador         | Como administrador, quiero poder iniciar sesión en el sistema con mis credenciales específicas para acceder al panel de administración de mi biblioteca.   | 3            |
| 16 | US001    | Ver sección "¿Qué es Bib Flip?"             | Como visitante de la página, quiero entender qué es Bib Flip desde la landing page para conocer su propósito y cómo puede ayudarme como usuario o administrador de biblioteca. | 2 |
| 17 | US002    | Ver sección "Características clave"       | Como visitante, quiero revisar una lista de características principales de Bib Flip para evaluar si cubre mis necesidades como usuario o administrador.      | 2            |
| 18 | US003    | Ver la galería virtual                    | Como visitante, quiero ver una galería virtual en la landing para visualizar cómo luce Bib Flip, su interfaz y los sensores en acción.                       | 2            |

# Capítulo IV: Product Architecture Design
## 4.1. Design Concepts, ViewPoints & ER Diagrams
En este capítulo se presenta el diseño de la arquitectura del producto Bibflip aplicando la metodología ADD (Attribute Driven Design). Este método sistemático permite diseñar la arquitectura basándose en los atributos de calidad requeridos, asegurando que el sistema cumpla con los requisitos funcionales y posea cualidades de seguridad, usabilidad y mantenibilidad.
### 4.1.1. Principles Statements
Se definen los principios clave para Bibflip, los cuales actúan como pautas generales para alcanzar los objetivos de negocio a largo plazo y asegurar una solución tecnológica robusta y escalable.

- **Precisión en Tiempo Real mediante IoT:** El sistema priorizará los datos provenientes de los sensores físicos de peso para garantizar que la disponibilidad de los cubículos refleje la realidad instantánea, eliminando la incertidumbre del estudiante.
- **Arquitectura de Microservicios Desacoplada:** Se adoptará un enfoque basado en contextos delimitados (IAM, Booking, Cubicle, etc.), permitiendo que cada componente escale, se despliegue y se mantenga de forma independiente, lo que facilita la evolución continua del producto.
- **Eficiencia en el Procesamiento (Edge y Cloud):** Utilizaremos una separación de responsabilidades entre una Edge API para el análisis local de sensores y una Cloud API para la lógica de negocio central, optimizando los tiempos de respuesta y reduciendo la carga en la red.
- **Seguridad Integral y Gestión de Identidad (IAM):** La autenticación y autorización basada en roles (estudiante, administrador, superadmin) será un pilar fundamental para proteger la privacidad de los datos académicos y asegurar la integridad del proceso de reserva.
- **Infraestructura Cloud-Native con Azure:** La solución se apoyará en servicios de Microsoft Azure (IoT Hub, App Service, Azure MySQL) para garantizar alta disponibilidad, resiliencia y una gestión simplificada de los dispositivos IoT en múltiples sedes.
- **Usabilidad y Enfoque en el Estudiante:** El diseño arquitectónico debe orientarse a minimizar la fricción en el proceso de reserva y reducir drásticamente el tiempo de búsqueda de espacios de estudio, cumpliendo con la promesa de valor de la startup.
- **Consistencia Tecnológica y Mantenibilidad:** Se seguirán estándares definidos para cada capa:
  - **Backend:** Java Spring Boot para la nube y Python Flask para el Edge.
  - **Frontend:** Vue.js para la web y Flutter para la aplicación móvil.
  - **Persistencia:** MySQL en la nube para datos globales y SQLite en el Edge para almacenamiento local.
### 4.1.2. Approaches Statements Architectural Styles & Patterns
**Enfoques de Desarrollo y Diseño:**

- **Domain-Driven Design (DDD):** Adoptamos el enfoque DDD para gestionar la complejidad intrínseca del sistema de reservas y la integración IoT. Esto nos ha permitido identificar contextos delimitados clave (IAM, Booking, Cubicle, Branching e IoT Monitoring), asegurando que cada módulo represente fielmente un área lógica del negocio bibliotecario.
- **Attribute-Driven Design (ADD):** El diseño de la arquitectura de Bibflip se guía sistemáticamente por la metodología ADD, lo que garantiza que las decisiones técnicas se tomen para satisfacer atributos de calidad críticos como la precisión de datos en tiempo real y la escalabilidad.

**Estilos y Patrones Arquitectónicos:**

- **Arquitectura de Microservicios:** Se ha optado por un estilo de microservicios donde las funcionalidades se organizan en servicios independientes y desacoplados. Cada contexto delimitado de DDD se implementará como un servicio que puede escalarse y mantenerse de forma autónoma.
- **API Gateway:** Actuará como el punto de entrada unificado para la aplicación web y móvil. Este componente se encarga de enrutar las solicitudes de los estudiantes y administradores hacia los microservicios correspondientes, gestionando también la autenticación.
- **Arquitectura Edge-Cloud (IoT):** Bibflip utiliza un enfoque híbrido especializado para IoT. Una Edge API (desarrollada en Python Flask) se encarga del procesamiento local y análisis de los datos de los sensores de peso, mientras que una Cloud API (Java Spring Boot) centraliza la lógica de negocio y la persistencia global en Azure.
- **Layered Architecture (Arquitectura en Capas):** Internamente, cada microservicio sigue un patrón de capas (Interface, Application, Domain, Infrastructure) para promover la separación de preocupaciones y facilitar la mantenibilidad del código.
- **Patrón CQRS (Command Query Responsibility Segregation):** Aplicamos este patrón en la capa de aplicación para separar las operaciones de escritura (comandos) de las de lectura (consultas). Esto es vital para que la consulta de disponibilidad de cubículos en tiempo real sea extremadamente rápida sin interferir con los procesos de creación de reservas.
### 4.1.3. Context Diagram
Este diagrama de contexto ilustra cómo el sistema Bibflip encaja en su entorno, identificando a los actores que interactúan con la plataforma y los sistemas de software externos que complementan su funcionalidad.

**Sistema Central:**

- **Bibflip (Software System):** Es el núcleo de la solución, encargado de la reserva y gestión de cubículos de estudio, integrando datos de sensores para ofrecer información precisa en tiempo real.

**Actores (Personas):**

- **Estudiantes:** Son los usuarios principales que acceden a la aplicación para verificar la disponibilidad de espacios individuales o grupales y realizar sus reservas de estudio.
- **Administrador de Cubículos (Personal Bibliotecario):** Utiliza el sistema para gestionar la asignación de espacios, supervisar las reservas activas y asegurar que se cumplan las normativas de ocupación mínima (como el requisito de al menos 4 estudiantes para cubículos grupales).
- **Super Administrador (Equipo de Desarrollo):** Responsable del mantenimiento técnico, la configuración global de la plataforma y la actualización continua del sistema.

**Sistemas Externos (Software Systems):**

- **Red de Sensores IoT:** Sensores físicos instalados en cada cubículo que detectan automáticamente el peso y transmiten el estado de ocupación real hacia el sistema.
- **Twilio:** Servicio externo de mensajería utilizado por la plataforma para enviar notificaciones push, confirmaciones de reserva y recordatorios automáticos a los usuarios.

<img src="https://i.ibb.co/sJvQ95kz/Contexto.png" alt="System Context en C4" border="0">

### 4.1.4. Approach driven ViewPoints Diagrams
En esta sección se presentan las vistas arquitectónicas detalladas del sistema Bibflip utilizando el modelo C4 y notación UML para proporcionar una comprensión profunda de la estructura y el comportamiento de la solución.

**Diagrama de Contenedores (C4 Level 2)**

Este diagrama representa la forma en que el sistema se descompone en aplicaciones y servicios independientes que se comunican entre sí.

  - **Aplicaciones Frontend:** Los estudiantes y administradores interactúan con el sistema mediante una Web App desarrollada en Vue.js y una Mobile App en Flutter.
  - **API Gateway (Spring Boot):** Actúa como el punto de entrada unificado que redirige las solicitudes de los clientes hacia los servicios internos correspondientes, gestionando la seguridad y el enrutamiento.
  - **Cloud API (Java Spring Boot):** Concentra la lógica de negocio central, incluyendo la gestión de reservas, validación de reglas de ocupación mínima y persistencia global en una base de datos Azure MySQL.
  - **Edge API (Python Flask):** Un contenedor especializado que reside cerca de los dispositivos físicos para procesar y analizar los datos de los sensores de peso antes de enviarlos a la nube, utilizando una base de datos local SQLite para resiliencia.
  - **IoT App (Azure IoT):** Gestiona la comunicación directa con la red de sensores instalados en los cubículos físicos.

<img src="https://i.ibb.co/XfP0RfQ6/container.png" alt="Container en C4" border="0">

**Diagramas de Componentes (C4 Level 3)**

Se detallan los componentes internos de los microservicios clave definidos mediante DDD:

  - **IAM Management Component Diagram:** Describe los componentes encargados de la autenticación, gestión de roles (estudiante, administrador, superadmin) y generación de tokens JWT.

  <img src="https://i.ibb.co/TMsPNKjt/iam.png" alt="IAM BC Component Diagram" border="0">

  - **Booking Management Component Diagram:** Detalla la lógica para la creación de reservas, gestión de slots de tiempo y validación de disponibilidad.

  <img src="https://i.ibb.co/qYs1Jsgy/booking.png" alt="Booking BC Component Diagram" border="0">

  - **Cubicle Management Component Diagram:** Gestiona el inventario de espacios físicos y traduce los datos de los sensores en estados de ocupación comprensibles para el negocio.

  <img src="https://i.ibb.co/35bgDmwJ/cubicule.png" alt="Cubicle Management BC Component Diagram" border="0">

  - **Branching Management Component Diagram:** Este diagrama detalla la estructura interna del microservicio encargado de la administración de las sedes o bibliotecas. 

  <img src="https://i.ibb.co/Xrc92kfY/branching.png" alt="Branching BC Component Diagram" border="0">




**Diagrama de Actividades (UML)**

Este diagrama ilustra el flujo operativo de Bibflip desde la perspectiva del estudiante:

  - El estudiante consulta la disponibilidad en tiempo real mediante el mapa interactivo.
  - Selecciona un cubículo y define el horario de reserva.
  - El sistema valida la reserva y actualiza el estado del cubículo automáticamente mediante la integración IoT.
  - Se envía una notificación de confirmación a través de Twilio.

**Diagrama de Estados (UML)**

Define el ciclo de vida de una reserva en Bibflip, el cual puede transitar entre los estados: Pendiente, Confirmada, Cancelada, En Curso y Completada. Asimismo, define los estados de los cubículos físicos: Disponible, Ocupado, Reservado y En Mantenimiento.

**Diagrama de Clases (UML)**
Presenta la estructura estática del dominio, destacando las entidades principales y sus relaciones:

- **User y Role:** Para la gestión de identidad.
<img src="https://i.postimg.cc/0N4x32Xx/Captura-de-pantalla-2025-09-18-181543.png" alt="IAM BC Domain Layer Class Diagram" border="0">

- **Headquarter:** Representa las sedes con sus horarios y ubicaciones.
<img src="https://i.postimg.cc/cH8ZNyP3/Captura-de-pantalla-2025-09-18-181621.png" alt="Branching BC Domain Layer Class Diagram" border="0">

- **Cubicle y Seat:** Modelan los espacios físicos y sus asientos individuales monitoreados por sensores.

<img src="https://i.ibb.co/JwN8RhhW/cubicule-clase.jpg" alt="Cubicle Management BC Domain Layer Class Diagram" border="0">

- **Booking y TimeSlot:** Gestionan la ocupación temporal de los espacios.

<img src="https://i.postimg.cc/VvQwfZcV/Captura-de-pantalla-2025-09-18-181709.png" alt="Booking BC Domain Layer Class Diagram"/><br>

### 4.1.5. Relational/Non Relational Database Diagram

<img src="https://i.postimg.cc/FHJ5w0MF/Diagrama-Base-de-datos-Bibflip.png" alt="Database Diagram"/><br>

### 4.1.6. Design Patterns

A continuación, se presentan los patrones de diseño que se emplearán en el desarrollo de Bibflip para asegurar una implementación coherente con el estilo de microservicios y la metodología DDD:

  - **CQRS (Command Query Responsibility Segregation):** Este patrón es fundamental en la arquitectura de Bibflip para separar las operaciones de escritura (comandos como crear una reserva) de las de lectura (consultas como ver disponibilidad de cubículos). Al usar modelos diferentes para cada sección, optimizamos el rendimiento de las consultas en tiempo real sin comprometer la integridad de las transacciones de reserva.
  - **DTO (Data Transfer Object):** Utilizaremos objetos planos (DTOs) para el intercambio de datos entre el backend (Spring Boot) y las interfaces de usuario (Vue.js/Flutter). Esto nos permite desacoplar la capa de presentación del modelo de dominio, evitando exponer directamente entidades sensibles de la base de datos y mejorando la seguridad de la información.
  - **Assembler / Mapper:** Implementaremos clases especializadas (como UserResourceFromEntityAssembler o BookingResourceFromEntityAssembler) encargadas de transformar las entidades del dominio en recursos (DTOs) y viceversa. Esto asegura que la lógica de transformación esté centralizada y no contamine los controladores o servicios.
  - **Facade (Context Facade / ACL):** Para gestionar la comunicación entre microservicios, emplearemos fachadas de contexto como CubicleManagementContextFacade y HeadquarterContextFacade. Estas actúan como una capa de anticorrupción (ACL), simplificando la interacción entre contextos delimitados (ej. cuando el microservicio de Reservas necesita consultar datos de una Sede o Sede) sin crear un acoplamiento rígido.
  - **Dependency Injection (Inyección de Dependencias):** Utilizaremos este patrón nativo de Spring Boot para gestionar las dependencias entre controladores, servicios y repositorios. Esto facilita la creación de pruebas unitarias y promueve un código más flexible y fácil de mantener.
  - **Repository:** Aplicaremos este patrón mediante Spring Data JPA para abstraer la lógica de persistencia en la base de datos Azure MySQL. Los repositorios permitirán a la capa de aplicación interactuar con los datos como si fueran colecciones de objetos en memoria, independientemente del motor de base de datos subyacente.
  - **Builder:** Este patrón será de gran utilidad para la creación paso a paso de objetos complejos del dominio, como Booking o Headquarter, que poseen múltiples campos y validaciones obligatorias antes de ser instanciados.

### 4.1.7. Tactics

En esta sección se describen las tácticas arquitectónicas empleadas para satisfacer los atributos de calidad de Bibflip, asegurando que el sistema sea robusto, seguro y eficiente.

**Disponibilidad (Availability)**

  - **Redundancia y Tolerancia a Fallos:** Se utiliza una infraestructura Cloud-Native en Azure con replicación activa para la base de datos Azure MySQL, asegurando que el sistema siga operativo ante fallos en una instancia.
  - **Resiliencia en el Borde (Edge Resilience):** La implementación de una Edge API con base de datos local SQLite permite que las lecturas de los sensores IoT continúen procesándose y almacenándose localmente incluso si se pierde la conexión temporal con la nube [Turno 5, Turno 7].
  - **Detección de Fallos:** Implementación de "heartbeats" en el firmware de los dispositivos IoT para monitorear constantemente el estado de los sensores y emitir alertas automáticas al panel del administrador ante cualquier desconexión.

**Seguridad (Security)**

  - **Autenticación y Autorización Robusta:** Uso del módulo IAM (Identity & Access Management) para centralizar la gestión de identidades mediante tokens JWT, asegurando que solo usuarios autenticados accedan a las funciones de reserva.
  - **Control de Acceso Basado en Roles (RBAC):** Se aplican permisos diferenciados para estudiantes, administradores de cubículos y superadministradores, limitando el acceso a módulos críticos según el perfil del usuario.
  - **Protección de Datos Sensibles:** Cifrado de contraseñas de usuarios en la base de datos y uso de protocolos seguros (HTTPS/TLS) para todas las comunicaciones entre las aplicaciones cliente, la API Gateway y los microservicios.

**Rendimiento (Performance)**

  - **Baja Latencia en Tiempo Real:** Optimización del flujo de datos IoT para que el estado de ocupación de los cubículos se actualice en las interfaces de usuario en un tiempo menor a 5 segundos tras la detección de cambio de peso.
  - **Separación de Responsabilidades (CQRS):** El uso del patrón CQRS permite que las consultas de disponibilidad (lecturas masivas) se realicen de forma independiente a las transacciones de reserva (escrituras), evitando cuellos de botella en horas pico de matrícula o exámenes [Turno 2, Turno 8].
  - **Comunicación Eficiente:** Uso de formatos ligeros como JSON para el intercambio de datos entre el backend y las aplicaciones móviles/web, minimizando el consumo de ancho de banda.

**Usabilidad (Usability)**

  - **Visualización Intuitiva:** Implementación de un mapa interactivo en tiempo real que permite al estudiante ubicar geográficamente los cubículos disponibles, reduciendo drásticamente el tiempo de búsqueda física en la biblioteca.
  - **Reducción de Fricción:** Diseño de un proceso de reserva simplificado con confirmaciones automáticas y recordatorios a través de Twilio, mejorando la experiencia del usuario y la planificación de sus sesiones de estudio.
  - **Accesibilidad Multiplataforma:** Desarrollo de interfaces consistentes tanto en la Web App (Vue.js) como en la Mobile App (Flutter), permitiendo al usuario gestionar sus espacios de estudio desde cualquier dispositivo.

## 4.2. Architectural Drivers
### 4.2.1. Design Purpose

El propósito del proceso de diseño de la arquitectura de Bibflip es establecer un ecosistema tecnológico robusto, escalable y eficiente que resuelva la ineficacia en la gestión de espacios de estudio en las bibliotecas universitarias peruanas. El diseño busca integrar armónicamente dispositivos físicos (sensores IoT) con una plataforma digital (Web y Móvil) para eliminar la incertidumbre del estudiante y optimizar la labor administrativa del personal bibliotecario.

Alineación de drivers con la arquitectura:

  - Eficiencia Operativa: El diseño se orienta a incrementar en un 30% la eficiencia en la utilización de cubículos y reducir en un 80% el tiempo de búsqueda de espacios para los estudiantes.
  - Precisión en Tiempo Real: La arquitectura prioriza la captura y procesamiento de datos de sensores de peso para reflejar la disponibilidad real en un tiempo menor a 5 segundos.
  - Escalabilidad y Mantenibilidad: Se adopta un enfoque de microservicios y DDD para asegurar que cada contexto (IAM, Booking, Cubicle, Branching e IoT) pueda evolucionar independientemente según crezca la demanda institucional.

Coherencia con modelos y vistas arquitectónicas:

  - Hibridación Edge-Cloud: Se define una separación clara entre la Edge API (procesamiento local de sensores) y la Cloud API (lógica de negocio en Azure) para garantizar disponibilidad y resiliencia incluso ante inestabilidad de red.
  - Seguridad y Control: El diseño arquitectónico implementa un microservicio de IAM centralizado que garantiza que solo usuarios autorizados realicen reservas, protegiendo la integridad de los datos académicos.
  - Persistencia Especializada: Se utiliza una base de datos relacional (Azure MySQL) para la consistencia de las reservas globales y una base de datos ligera (SQLite) en el borde para la persistencia inmediata de las lecturas de sensores.
  - Experiencia de Usuario Superior: El diseño de los contenedores frontend (Vue.js y Flutter) se alinea con el driver de Usabilidad, proporcionando un mapa interactivo que facilita la visualización geográfica de las sedes y su aforo actual.
### 4.2.2. Primary Functionality (Primary User Stories)
En este apartado se identifican las funcionalidades de mayor prioridad que definen la estructura de la aplicación y soportan los procesos clave del negocio de gestión bibliotecaria.

**Requerimientos funcionales de mayor prioridad**

| Categoría                         | ID      | Título                                                  |
|-----------------------------------|---------|---------------------------------------------------------|
| Gestión de Reservas (Estudiantes) | RF-RE01 | Consulta de disponibilidad en tiempo real (IoT).        |
|                                   | RF-RE02 | Proceso de reserva de cubículos individuales/grupales.  |
|                                   | RF-RE03 | Visualización y seguimiento de reserva activa.          |
| Gestión Administrativa (Personal) | RF-AD01 | Gestión de inventario de cubículos (CRUD).              |
|                                   | RF-AD02 | Monitoreo y filtrado de reservas de la sede.            |
| Gestión Global (Superadmin)       | RF-SA01 | Registro y asignación de administradores a sedes.       |
|                                   | RF-SA02 | Configuración global de sedes y parámetros del sistema. |


**Historias de Usuario Primarias**

Estas historias describen los servicios fundamentales que requieren una coordinación entre los microservicios de IAM, Booking, Cubicle y Branching.

| User Story ID | Título                            | Descripción                                                                                                                                              |
|---------------|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| US007         | Ver disponibilidad en tiempo real | Como estudiante, quiero conocer la disponibilidad de cubículos mediante el mapa interactivo para decidir a qué sede acudir sin perder tiempo.            |
| US008         | Reservar un cubículo              | Como estudiante, quiero reservar un cubículo para asegurar un lugar al llegar al centro de estudio, respetando la capacidad mínima permitida.            |
| US006         | Visualizar reserva activa         | Como estudiante, quiero visualizar mi reserva activa para confirmar detalles de sede, cubículo y horario antes de mi llegada.                            |
| US012         | Agregar nuevos cubículos          | Como administrador de sede, quiero agregar cubículos al sistema con su capacidad y ubicación para gestionar mejor la ocupación de mi biblioteca.         |
| US013         | Visualizar reservas realizadas    | Como administrador, quiero ver la lista de reservas en mi sede (filtradas por usuario o fecha) para planificar eficientemente el servicio bibliotecario. |
| US017         | Registro de administrador         | Como superadmin, quiero registrar nuevos administradores y asignarles una sede específica para delegar la gestión operativa de los espacios.             |
| US018         | Acceso total a módulos            | Como superadmin, quiero tener acceso a todas las funcionalidades del sistema para realizar pruebas técnicas y configurar sedes nuevas.                   |


### 4.2.3. Quality Attribute Scenarios

En esta sección se presentan los escenarios de atributos de calidad que actúan como requisitos técnicos específicos para validar la robustez de la arquitectura de Bibflip.

| ID   | Atributo de Calidad | Fuente de Estímulo                           | Estímulo                                                                                 | Entorno                                                   | Artefacto                             | Respuesta                                                                                                 | Medida de Respuesta                                                                                                   |
|------|---------------------|----------------------------------------------|------------------------------------------------------------------------------------------|-----------------------------------------------------------|---------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| QA-1 | Disponibilidad      | Red de Sensores IoT                          | Un sensor detecta un cambio de peso en un asiento del cubículo,.                         | Operación normal con tráfico constante de datos.          | Edge API y Cloud API                  | El sistema procesa la lectura y actualiza el estado de ocupación en el mapa interactivo,.                 | El estado de disponibilidad debe actualizarse en la aplicación en menos de 5 segundos,.                               |
| QA-2 | Seguridad           | Usuario no autenticado                       | Intento de acceder a la gestión de cubículos o realizar una reserva sin un token válido. | Operación normal, el sistema recibe una petición externa. | Microservicio de IAM                  | El sistema bloquea la petición, deniega el acceso y solicita credenciales válidas,.                       | El acceso debe ser denegado y notificado al usuario en menos de 100ms.                                                |
| QA-3 | Rendimiento         | 1,300 estudiantes (población universitaria). | Aumento masivo de consultas de disponibilidad durante la semana de exámenes finales.     | Carga máxima del sistema (sobrecarga).                    | API Gateway y Azure MySQL             | El sistema prioriza las consultas mediante CQRS, separando las lecturas de las transacciones de reserva,. | El tiempo de respuesta para el 95% de las consultas de disponibilidad debe ser ≤ 2 segundos.                          |
| QA-4 | Usabilidad          | Estudiante universitario.                    | Deseo de reservar un cubículo específico tras visualizarlo en el mapa.                   | Interacción mediante la Mobile App (Flutter).             | Interfaz de Usuario (Frontend)        | El sistema guía al usuario por un flujo intuitivo de selección y confirmación de reserva,.                | El estudiante debe poder completar la reserva en menos de 3 clics desde la pantalla principal.                        |
| QA-5 | Modificabilidad     | Equipo de Desarrollo (Superadmin).           | Necesidad de agregar una nueva sede universitaria con reglas de capacidad distintas.     | Entorno de mantenimiento y actualización.                 | Microservicio de Branching Management | El desarrollador agrega el nuevo módulo o configuración sin afectar el funcionamiento de IAM o Reservas,. | Los cambios deben implementarse y desplegarse en el entorno cloud sin generar tiempos de inactividad (Zero Downtime). |
| QA-6 | Interoperabilidad   | Sistema Externo (Twilio)                     | Necesidad de enviar una notificación de confirmación tras una reserva exitosa.           | Transacción completada en el microservicio de Booking.    | Cloud API                             | El sistema se comunica mediante API REST para enviar los datos de la reserva al proveedor de mensajería.  | La notificación debe ser recibida por el estudiante en menos de 10 segundos tras confirmar la reserva.                |

### 4.2.4. Constraints

Se identifican los factores tecnológicos y de entorno que imponen restricciones a la arquitectura de Bibflip, limitando las opciones de diseño para garantizar la coherencia con los estándares institucionales y la infraestructura en la nube.

| ID    | Factor                       | Restricción                                                                                                                                                                                                                 |
|-------|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CON-1 | Topología de la red          | La arquitectura debe garantizar baja latencia mediante una red distribuida en Microsoft Azure, con balanceadores de carga para asegurar que las actualizaciones de los sensores IoT lleguen a la aplicación en tiempo real. |
| CON-2 | Proveedor de Base de Datos   | Es obligatorio el uso de Azure MySQL para la persistencia global de reservas e identidad, y de SQLite en el borde (Edge) para la resiliencia de datos de sensores locales.                                                  |
| CON-3 | Entorno Web y Lenguajes      | El desarrollo del backend está restringido al uso de Java Spring Boot para los microservicios en la nube y Python Flask para el procesamiento en el Edge. El frontend debe implementarse en Vue.js (Web) y Flutter (Móvil). |
| CON-4 | Servidores e Infraestructura | El despliegue debe realizarse mandatoriamente en la plataforma Azure, utilizando App Service para alojar las APIs y Azure IoT Hub para la gestión de la comunicación con los dispositivos físicos.                          |
| CON-5 | Software de Terceros         | El sistema debe integrarse con la API de Twilio para el envío de notificaciones de confirmación de reserva y con Google Maps API para la geolocalización de las sedes universitarias.                                       |
| CON-6 | Cumplimiento de Normas       | La aplicación debe cumplir con las regulaciones de protección de datos personales y normativas de seguridad informática académica, asegurando la privacidad de la información gestionada por el microservicio de IAM.       |

### 4.2.5. Architectural Concerns

| ID    | Título                                        | Architectural Concerns                                                                                                                                                                                                                            | Driver Asociado             |
|-------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|
| CRN-1 | Sincronización de Datos IoT en Tiempo Real    | **Preocupación:** Garantizar que los datos de peso capturados por los sensores se procesen en la Edge API y se reflejen en la Cloud API y la interfaz del usuario en menos de 5 segundos para evitar discrepancias entre el estado real y el digital. | Rendimiento / Precisión     |
| CRN-2 | Resiliencia ante Fallos de Conectividad       | **Preocupación:** Asegurar que el sistema de monitoreo de cubículos no se detenga si se pierde la conexión con Azure. Se debe garantizar la persistencia local en el borde (Edge SQLite) y la sincronización posterior.                               | Disponibilidad              |
| CRN-3 | Seguridad y Privacidad de Datos Académicos    | **Preocupación:** Proteger la identidad de los estudiantes y la integridad de las reservas mediante el microservicio IAM, utilizando tokens JWT y cifrado para evitar accesos no autorizados a la gestión de espacios.                                | Seguridad                   |
| CRN-4 | Escalabilidad ante Picos de Demanda           | **Preocupación:** Soportar el aumento masivo de tráfico durante semanas de exámenes finales (considerando la población de 1.3 millones de estudiantes de pregrado en el país) sin degradar los tiempos de respuesta del sistema de reservas.          | Rendimiento / Escalabilidad |
| CRN-5 | Interoperabilidad con Servicios Externos      | **Preocupación:** Mantener una integración fluida y desacoplada con Twilio para notificaciones y con la infraestructura física de sensores, asegurando que fallos en terceros no bloqueen la lógica core de la aplicación.                            | Interoperabilidad           |
| CRN-6 | Mantenibilidad de Microservicios Desacoplados | **Preocupación:** Facilitar la evolución independiente de los contextos (Booking, Cubicle, Branching) y su despliegue continuo en Azure App Service sin generar tiempos de inactividad durante las actualizaciones.                                   | Modificabilidad             |


## 4.3. ADD Iterations
### 4.3.1. Iteration 1: <Bibflip Foundation & Security Enhancement>
#### 4.3.1.1. Architectural Design Backlog 1
En esta primera iteración, el Architectural Design Backlog se establece como la hoja de ruta para definir los elementos base de Bibflip. Se prioriza la creación de un entorno seguro y una estructura organizativa sólida (sedes), lo cual es requisito indispensable antes de implementar la lógica compleja de reservas e IoT.
Las tareas arquitectónicas priorizadas para este backlog son:

  1. **Establecimiento de Metas de Diseño:** Definir los objetivos de la iteración basándose en los drivers de Seguridad (IAM), Disponibilidad y Modificabilidad.
  2. **Refinamiento de Elementos del Sistema:** Seleccionar y detallar los contextos delimitados de IAM Management y Branching Management como los componentes primarios a refinar.
  3. **Selección de Conceptos de Diseño:** Elegir los patrones y estilos que satisfagan los drivers, tales como la Arquitectura de Microservicios, el uso de un API Gateway y la autenticación mediante JWT.
  4. **Instanciación de Elementos Arquitectónicos:** Asignar responsabilidades específicas a las entidades de User, Role y Headquarter, asegurando que el modelo de dominio sea consistente.
  5. **Definición de Interfaces y Fachadas:** Establecer cómo se comunicarán estos módulos con el resto del sistema a través de REST APIs y el patrón Context Facade (ACL).
  6. **Documentación de Vistas y Decisiones:** Realizar el bosquejo de los diagramas de contenedores (C4 Level 2) y de componentes (C4 Level 3) para los módulos de identidad y sedes.
  7. **Gestión de Cambios en Kanban Board:** Registrar todas las decisiones arquitectónicamente relevantes para asegurar la trazabilidad en futuras iteraciones.
#### 4.3.1.2 Establish Iteration Goal by Selecting Drivers
El objetivo central de esta primera iteración es garantizar una base técnica sólida, segura y escalable para los servicios de identidad (IAM) y la estructura organizativa de las bibliotecas (Branching). Al establecer estos cimientos, aseguramos que el sistema pueda soportar posteriormente la lógica crítica de reservas e integración de sensores IoT sin comprometer la integridad de los datos académicos.

**Identificación de Drivers**

Para esta iteración, se han seleccionado los siguientes drivers que guiarán el diseño de los módulos iniciales:

  - **Seguridad (Security):** Es el driver de mayor prioridad. Se debe asegurar que el acceso a la gestión de cubículos y la información personal de los estudiantes esté protegida mediante autenticación y autorización por roles (estudiante, administrador y superadmin).
  - **Disponibilidad (Availability):** El sistema debe garantizar que los servicios de gestión de sedes y perfiles de usuario estén accesibles en la nube de Azure, permitiendo que el personal bibliotecario configure los espacios en cualquier momento operativo.
  - **Modificabilidad (Modificability):** Al adoptar una arquitectura de microservicios, buscamos que los contextos de IAM y Branching puedan evolucionar o ser actualizados de forma independiente sin afectar el desarrollo futuro de los módulos de reservas o monitoreo IoT.
  - **Interoperabilidad (Interoperability):** Se debe establecer una comunicación estandarizada y eficiente entre el API Gateway y los microservicios iniciales utilizando protocolos REST y formato JSON, facilitando la integración con las aplicaciones web y móviles.

**Enfoque de la Iteración**

Con estos drivers definidos, el diseño se centrará en:

  - **Gestión de Identidad Robusta:** Implementar el microservicio de IAM para manejar el ciclo de vida del usuario, desde el registro de estudiantes (US010) hasta el control total por parte del superadmin (US018).
  - **Estructura Jerárquica de Sedes:** Diseñar el microservicio de Branching para modelar las bibliotecas universitarias (US014), permitiendo que cada administrador gestione exclusivamente su área de responsabilidad.
  - **Estabilidad de la Infraestructura Cloud:** Configurar los recursos base en Microsoft Azure (App Services y Azure MySQL) para asegurar que la plataforma sea resiliente desde su despliegue inicial.
#### 4.3.1.3 Choose One or More Elements of the System to Refine

En esta iteración, se han seleccionado los elementos del sistema que constituyen el "esqueleto" funcional y el perímetro de seguridad de la plataforma. La refinación de estos componentes es crítica para asegurar que el sistema sea confiable antes de integrar la lógica de sensores IoT.

Elementos seleccionados para refinamiento:

  - **Microservicio de IAM (Identity & Access Management):** Se prioriza este elemento para satisfacer el driver de Seguridad. El refinamiento se centrará en la lógica de autenticación y la gestión de roles (estudiante, administrador de sede y superadmin), asegurando que el acceso a los datos académicos y operativos esté protegido desde el inicio.
  - **Microservicio de Branching Management:** Se selecciona este componente para establecer la estructura organizativa de las bibliotecas universitarias. Refinaremos la gestión de sedes, horarios operativos y geolocalización, lo cual es fundamental para que el resto de los servicios (como Reservas) tengan un contexto físico donde operar.
  - **API Gateway (Java Spring Boot):** Actuará como el punto de entrada único para el sistema. Se refinará su capacidad para enrutar peticiones de forma eficiente hacia los microservicios de IAM y Branching, gestionando además la validación centralizada de tokens de seguridad para cumplir con el driver de Interoperabilidad.
  - **Capa de Persistencia Global (Azure MySQL):** Se refinará el diseño de las tablas base para usuarios y sedes. Esto asegura que la base de datos centralizada en la nube de Azure proporcione la Disponibilidad necesaria para los administradores y estudiantes en cualquier momento.
  - **Interfaces y Fachadas de Contexto (ACL):** Refinaremos la comunicación entre el microservicio de IAM y Branching mediante fachadas (Context Facade), lo que garantiza un bajo acoplamiento y facilita la Modificabilidad futura del sistema cuando se agreguen nuevos subdominios.

La elección de estos elementos permite mitigar el riesgo de vulnerabilidades de acceso y asegura que la configuración de las sedes universitarias sea estable. Al refinar estos componentes primero, creamos un entorno donde la posterior integración de los sensores de peso (en la Iteración 2) se realice sobre una arquitectura ya validada y segura.

#### 4.3.1.4 Choose One or More Design Concepts That Satisfy the Selected Drivers
A continuación, se presentan los conceptos de diseño elegidos para asegurar que los cimientos del sistema cumplan con los atributos de calidad requeridos:

  - **Seguridad (Security):**
      - **Autenticación y Autorización basada en Roles (RBAC) con JWT:** Se implementará un sistema de control de acceso en el microservicio de IAM donde los usuarios (Estudiantes, Administradores y Superadmins) recibirán un token JWT tras autenticarse. Este token permitirá validar permisos de forma centralizada en el API Gateway antes de redirigir las peticiones a módulos sensibles.
      - **Cifrado de Credenciales:** Se utilizará el algoritmo BCrypt dentro de la capa de infraestructura del IAM para encriptar las contraseñas antes de su persistencia en la base de datos, garantizando la protección de los datos académicos.
      - **Comunicación Segura:** Todas las interacciones entre los dispositivos del usuario, el API Gateway y los servicios en la nube se realizarán exclusivamente mediante protocolos cifrados como HTTPS/TLS.
  - **Disponibilidad (Availability):**
      - **Infraestructura Cloud-Native (Microsoft Azure):** Se opta por desplegar los microservicios en Azure App Service y utilizar Azure Database for MySQL. Estos servicios gestionados proveen alta disponibilidad intrínseca y escalado automático, asegurando que la gestión de sedes y el login estén siempre operativos para la comunidad universitaria.
      - **Persistencia Desacoplada:** Siguiendo el principio de microservicios, cada contexto tendrá su propio esquema de datos, lo que evita que un fallo en la base de datos de un módulo afecte la disponibilidad de los demás.
  - **Modificabilidad (Modificability):**
      - **Arquitectura de Microservicios basada en DDD:** El sistema se organiza en Contextos Delimitados (IAM, Branching, etc.), permitiendo que cada uno evolucione independientemente. Esto facilita añadir nuevas sedes o cambiar reglas de autenticación sin impactar al resto de la plataforma.
      - **Capa de Anticorrupción (ACL) y Facade:** Se utilizarán facade como HeadquarterContextFacade para que otros módulos consulten datos de las sedes de forma simplificada, manteniendo un bajo acoplamiento entre servicios.
  - **Interoperabilidad (Interoperability):**
      - **API Gateway como Punto de Entrada Único:** Se utilizará un Gateway (desarrollado en Spring Boot) para orquestar los requests de las aplicaciones web y móviles, estandarizando la comunicación mediante APIs RESTful.
      - **Intercambio de Datos en JSON:** Se adopta el formato JSON para todas las respuestas de la API, asegurando una integración fluida y ligera con el frontend de Vue.js y Flutter.
#### 4.3.1.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces
1. **Microservicio de IAM (Identity & Access Management)** <br>
Este módulo es el pilar de la Seguridad y gestiona el ciclo de vida del usuario y sus permisos.

  - **Elementos Arquitectónicos y Responsabilidades:**
      - Agregado User: Responsable de encapsular la lógica de autenticación, almacenamiento seguro de credenciales (hashing) y la gestión de la relación con los roles asignados.
      - Entidad Role: Define los privilegios específicos para los roles de Estudiante, Administrador y Superadmin.
      - UserCommandService: Orquesta los procesos de registro (sign-up) y autenticación (sign-in), coordinando con el servicio de tokens JWT.
      - IAM Context Facade (ACL): Actúa como la interfaz de control de acceso para que otros microservicios validen si un usuario tiene los permisos necesarios para realizar una acción.

  - **Definición de Interfaces (API REST):**
      - `POST /api/v1/authentication/sign-up`: Registro de nuevos estudiantes y administradores.
      - `POST /api/v1/authentication/sign-in`: Validación de credenciales y emisión del token JWT.
      - `GET /api/v1/users/{userId}`: Consulta de perfil y roles para personalización de la interfaz.

2. **Microservicio de Branching Management** <br>
Encargado de la estructura organizativa de las sedes, cumpliendo con el driver de Modificabilidad.

  - **Elementos Arquitectónicos y Responsabilidades:**
      - Agregado Headquarter: Responsable de mantener la integridad de los datos de la sede, incluyendo geolocalización (latitud/longitud) y datos de contacto.
      - Entidad Schedule: Gestiona los horarios de apertura y cierre de las bibliotecas, así como los intervalos de tiempo permitidos para las reservas.
      - HeadquarterRepository: Gestiona la persistencia en Azure MySQL, asegurando que no existan sedes duplicadas en la misma ubicación geográfica.
  - **Definición de Interfaces (API REST e Inter-contexto):**
      - `GET /api/v1/headquarters`: Lista de todas las sedes para el mapa interactivo del estudiante.
      - `POST /api/v1/headquarters`: Configuración de nuevas sedes por parte del Superadmin.
      - HeadquarterContextFacade.existsHeadquarter(id): Interfaz interna para que el microservicio de Reservas valide si una sede es válida antes de procesar un slot.

3. **API Gateway y Capa de Infraestructura**

  - API Gateway (Spring Boot): Responsable de centralizar los requests, realizar la validación del token JWT de forma global y redirigir el tráfico hacia el microservicio correspondiente.
  - HashingService: Responsable de aplicar el algoritmo BCrypt a las contraseñas antes de que lleguen a la base de datos.
#### 4.3.1.6 Sketch Views (C4 & UML) and Record Design Decisions
#### 4.3.1.7 Analysis of Current Design and Review Iteration Goal (Kanban Board) 

### 4.3.2. Iteration 2: <Booking Management & IoT Integration>
#### 4.3.2.1. Architectural Design Backlog 2
En esta etapa, el backlog se centra en refinar los procesos críticos que permiten al estudiante asegurar un espacio de estudio y al sistema reflejar la ocupación física real. Las tareas priorizadas son:

  1. **Refinamiento del Subdominio Core:** Detallar la lógica de negocio para la creación de reservas y validación de reglas (como la ocupación mínima).
  2. **Diseño de la Arquitectura IoT:** Definir el flujo de datos desde los sensores físicos hasta la interfaz de usuario.
  3. **Optimización del Rendimiento:** Implementar el patrón CQRS para asegurar que las consultas masivas de disponibilidad no afecten la creación de reservas.
  4.  **Resiliencia en el Borde:** Configurar la interacción entre la Edge API y la Cloud API para mantener la captura de datos ante fallos de red.

#### 4.3.2.2 Establish Iteration Goal by Selecting Drivers

El objetivo de esta iteración es optimizar el rendimiento en tiempo real y la precisión de la disponibilidad, consolidando una arquitectura híbrida que soporte tanto la lógica de negocio compleja como la telemetría de sensores.

**Drivers seleccionados:**

  - **Rendimiento (Performance):** El estado de disponibilidad debe actualizarse en menos de 5 segundos tras la detección de cambio de peso por los sensores.
  - **Disponibilidad (Availability):** El sistema debe ser capaz de recolectar datos localmente en el borde (Edge) mediante SQLite incluso si la nube de Azure no está disponible temporalmente.
  - **Usabilidad (Usability):** Facilitar al estudiante la reserva mediante un mapa interactivo intuitivo que reduzca el tiempo de búsqueda física en un 80%.

#### 4.3.2.3 Choose One or More Elements of the System to Refine

Se han seleccionado los componentes que gestionan la "inteligencia" y la "presencia física" del sistema:

  - **Microservicio de Booking Management:** Responsable del ciclo de vida de las reservas y la gestión de slots de tiempo.
  - **Contexto de IoT Device Monitoring:** Encargado de interpretar las señales de peso de los sensores para determinar el estado "Ocupado" o "Libre".
  - **Edge API (Python Flask):** Elemento que reside cerca de los sensores para procesar datos antes de enviarlos a la nube.
  - **Contexto de Cubicle Management (Refinamiento):** Para sincronizar el inventario físico con los datos provenientes de IoT.

#### 4.3.2.4. Choose One or More Design Concepts That Satisfy the Selected Drivers

Se aplican los siguientes conceptos técnicos para cumplir con los drivers:

  - **Patrón CQRS:** Separa el modelo de comandos (CreateBooking) del modelo de consultas (GetAvailability), permitiendo lecturas extremadamente rápidas para el mapa en tiempo real.
  - **Arquitectura Híbrida Edge-Cloud:** Utiliza procesamiento en el borde para reducir la latencia y el tráfico hacia la nube, cumpliendo con el driver de rendimiento.
  - **Capa de Anticorrupción (ACL):** El microservicio de IoT provee datos técnicos que el microservicio de Cubicle adapta para no contaminar su lógica administrativa.
  - **Notificaciones Asíncronas:** Uso de Twilio para confirmar reservas sin bloquear el flujo principal de la aplicación.

#### 4.3.2.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

Se definen los componentes internos y sus interacciones:

  - **Agregado Booking:** Gestiona la consistencia de la reserva, validando que el usuario sea válido y el slot esté libre.
  - **Entidad AvailabilitySlot:** Modela los bloques de tiempo de cada cubículo y su estado (Disponible/Reservado).
  - **Componente IoT Gateway:** Recibe lecturas de los sensores en el borde y aplica filtros de ruido antes de reportar a la nube.

  - **Interfaces de Comunicación:**
      - `GET /api/v1/cubicles/{id}/schedule`: Consulta de slots para el mapa interactivo.
      - `POST /api/v1/bookings`: Creación de reserva con validación de capacidad (mínimo 3-4 estudiantes).

#### 4.3.2.6. Sketch Views (C4 & UML) and Record Design Decisions
https://postimg.cc/FY2Lc4m2
https://i.postimg.cc/nLLYyFWc/image.png
#### 4.3.2.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)
