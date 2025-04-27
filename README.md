![img.png](Assets/img.png)
# Universidad Peruana de Ciencias Aplicadas
- Carrera de Ingeniería de Software - Septimo ciclo
- Curso: 1ASI0572 -  Desarrollo de Soluciones IOT
- NRC: 15185
- Profesor: Marco Antonio Leon Baca
# Informe del Trabajo Final
- Nombre Startup: IoTech
- Nombre Producto: SmartSign
## Relación de integrantes:

| Alumno                           | Código     |
|----------------------------------|------------|
| Alvaro Esteban Crispin Ccancce   | u202020328 |
| Jesús Andres Godoy Santillan     | u20251c350 |
| Jorge David Orrego Noriega       | u201921734 |
| Miguel Angel Huaman Cataño       | u202120615 |
| Frank Junior Salazar Saldarriaga | u20181h103 |

Abril, 2025

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|----------------------------|
| 1.0 | 17/04/2025 | Grupo IoTech | Se creó el documento de desarrollo del informe |
| 2.0 | 26/04/2025 | Grupo IoTech | Se terminó el desarrollo de la TB1 |

# Project Report Collaboration Insights

**TB1:**

**Colocar al final capturas de los commits**

# Student Outcome

**ABET – EAC - Student Outcome 5:** Capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio Especifico                                                                             | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Conclusiones                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                | **TB1:** <br> Jorge Orrego: <br> He trabajado con mis compañeros de manera cercana en el desarrollo del diseño de desarrollo de software, en el cual pudimos delegar equitativamente la carga de trabajo. <br>**TB1:** <br> Frank Salazar: <br> Se trabajó con el equipo la estructura del proyecto para poder delegar funciones en el desarrollo del proyecto y mejorar el trabajo en equipo <br> **TB1:** <br> Alvaro Crispin: <br> Coordiné con el equipo la definición y redacción de las User Stories y del Product Backlog, asegurando una visión compartida de los requerimientos, Propuse y validé la estructura del modelo C4 general, guiando a mis compañeros durante su elaboración. Finalmente, asistí en la creación del Bounded Context de Translation, fomentando la participación activa de todos. | **TB1:** <br> Se logró implementar drinámicas para que todos en el equipo tuvieran la oportunidad de liderar y aportar con lo que más sepan. <br> **TB1:** <br> Frank Salazar <br>Se logró desarrollar la primera parte del proyecto, hablando del documentado, de manera satisfactoria, gracias a la correcta delegación de funciones que se realizó. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1:** <br> Jorge Orrego: <br> Junto a mis compañeros pude definir objetivos y fechas límite de entrega de las partes que les tocaba a cada uno, con el objetivo de poder revisar con más detenimiento lo que hemos avanzado antes de la entrega oficial.  <br>  **TB1:** <br> Frank Salazar: <br> En trabajo con mis compañeros, pudimos establecer funciones, plazos y reuniones a realizar para el desarrollo del proyecto. <br> **TB1:** <br> Alvaro Crispin: <br> Fui responsable de cada artefacto (User Stories, Backlog, C4, Bounded Context), Implementé sprints cortos con entregables parciales y seguimiento del avance. Finalmente, realicé demos internas del Bounded Context de Translation, recogiendo feedback y ajustando el plan de trabajo.                                                   | **TB1:** <br> Se pudo realizar dinámicas entre el equipo (reuniones en discord) para planificar y mostrar nuestro progreso en lo que cada uno esté avanzando. <br>  **TB1:** <br> Frank Salazar <br> La correcta delegación del proyecto, junto a las reuniones, plazos y funciones permitieron llevar un orden en el desarrollo del proyecto.         |


# Contenido

## Tabla de Contenidos

## [Capítulo I: Introducción](#capitulo-i-introduccion)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#1.1.1.descripcion-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#1.1.2.perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problematica)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-problem-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-problem-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-problem-canvas)
- [1.3. Segmentos objetivo](#13-segmento-objetivo)
## [Capítulo II: Requirements Elicitation & Analysis](#capitulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competivio](#211-análisis-competivio)
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

## [Capítulo III: Requirements Specification](#capitulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Solution Software Design](#capitulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Diven Design](#41-strategic-level-domain-diven-design)
    - [4.1.1. Event Storming](#411-event-storming-) 
        - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
        - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
        - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Achitecture](#413-software-achitecture)
        - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
        - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
        - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
        - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design-cuatro-bounded-contexts-)
    - [4.2.1. Bounded Context: Authentication](#421-bounded-context-authorization-) 
        - [4.2.1.1. Domain Layer.](#4211-domain-layer)
        - [4.2.1.2. Interface Layer](#4212-interface-layer)
        - [4.2.1.3. Application Layer](#4213-application-layer)
        - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
        - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.1.6.1 Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
            - [4.2.1.6.2 Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2. Bounded Context: Learning](#422-bounded-context-learning-) 
        - [4.2.2.1. Domain Layer.](#4221-domain-layer)
        - [4.2.2.2. Interface Layer](#4222-interface-layer)
        - [4.2.2.3. Application Layer](#4223-application-layer)
        - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
        - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.2.6.1 Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
            - [4.2.2.6.2 Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3. Bounded Context: Translation](#423-bounded-context-translation) 
        - [4.2.3.1. Domain Layer.](#4231-domain-layer)
        - [4.2.3.2. Interface Layer](#4232-interface-layer)
        - [4.2.3.3. Application Layer](#4233-application-layer)
        - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
        - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.3.6.1 Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
            - [4.2.3.6.2 Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
    - [4.2.4. Bounded Context: Record](#424-bounded-context-record) 
        - [4.2.4.1. Domain Layer.](#4241-domain-layer)
        - [4.2.4.2. Interface Layer](#4242-interface-layer)
        - [4.2.4.3. Application Layer](#4243-application-layer)
        - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
        - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.4.6.1 Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
            - [4.2.4.6.2 Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)

## Capítulo I: Introduccion
### 1.1. Startup Profile
#### 1.1.1 Descripcion de la Startup
SmartSign fue creada con el principal objetivo de facilitar la vida a aquellas personas las cuales cuentan con la discapacidad del habla o discapacidad auditiva, ya que se les dificulta un factor importante para poder vivir en sociedad, la comunicación. Buscamos solucionar este problema mediante la implementación de tecnologías de IoT para la creación de un guante con sensores que pueda traducir el lenguaje de señas en forma de audio y así poder facilitar su comunicación. La solución propuesta por SmartSign permitirá facilitar la comunicación y por la tanto sentirse incluidas socialmente a las personas con discapacidad auditiva, pero también facilitará la enseñanza a aquellas instituciones derivadas a brindar conocimientos a las personas con esta discapacidad.

Misión:
Facilitar la comunicación e inclusión social de las personas con discapacidad auditiva y del habla, desarrollando soluciones tecnológicas innovadoras basadas en IoT que transformen la lengua de señas en lenguaje audible, generando independencia, integración y calidad de vida.

Visión:
Ser reconocidos como líderes en innovación tecnológica en inclusión social en el Perú, convirtiéndonos en el referente nacional en soluciones accesibles e inteligentes que derriban barreras de comunicación para personas con discapacidad auditiva y del habla, promoviendo una sociedad más equitativa y conectada.

#### 1.1.1 Perfiles de integrantes del equipo

<table>
  <tr>
    <td rowspan="3"><img src="Assets/frankprofile.png" alt="Descripción" width="800"></td>
    <td>Frank Junior Salazar Saldarriaga (u20181h103)</td>
  </tr>
  <tr>
        <td>Ingenieria de Software</td>
  </tr>
    <tr>
    <td>Soy Frank Salazar, tengo 24 años y tengo una gran devoción por la programación, desde los 8 años me gustó programar, iniciando por algoritmos sencillos, hasta la recreación de videojuegos. Hace unos años decidí centrarme mucho en el desarrollo Backend y frontend, pero también le he agarrado mucho gusto a la data science. Actualmente soy programador en Yape, BCP. Soy asistente desde el año pasado, pero comencé como practicando desde agosto del 2023.</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="Assets/alvaroprofile.png" alt="Descripción" width="800"></td>
    <td>Alvaro Esteban Crispin Ccancce (u202020328)</td>
  </tr>
  <tr>
        <td>Ingenieria de Software</td>
  </tr>
    <tr>
    <td>Soy Alvaro Crispin, tengo 22 años y me encanta ser innovador, buscar nuevas ideas, crear soluciones y asumir retos. Desde pequeño me interesó mucho lo que son las computadoras a nivel hardware y sobre la ciberseguridad. Actualmente me encanta todo lo relacionado a soldar, crear, programar y manipular artefactos electrónicos como chips, sensores, redes, etc.</td>
  </tr>
<tr>
    <td rowspan="3"><img src="Assets/Perfil_Jorge.png" alt="Descripción" width="800"></td>
    <td>Orrego Noriega, Jorge David (u201921734)</td>
  </tr>
  <tr>
        <td>Ingenieria de Software</td>
  </tr>
    <tr>
    <td>Estudio actualmente la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas y la razón por la cual me encuentro estudiando esta carrera es porque siempre he tenido un interés particular por la tecnología, con un mayor énfasis en el software.</td>
  </tr>
<tr>
    <td rowspan="3"><img src="Assets/Perfil_Jesus.png" alt="Descripción" width="800"></td>


</td>
    <td>Jesús Andres Godoy Santillan (u20251c350)</td>
  </tr>
  <tr>
        <td>Ingenieria de Software</td>
  </tr>
    <tr>
    <td> Soy Jesús, tengo 22 años, me gusta mucho programar desde pequeño haciendo pequeños proyectos en videojuegos hasta lo último que hice que fue un gran proyecto  en un evento online con creadores de contenido, patrocinadores y premios. Actualmente no trabajo formalmente pero ayudo a mi padre y junto a mi hermano haciendo sistemas y programas de una empresa que tiene junto a su amigo relacionado con la agroindustria y con el conocimiento que tengo de tecnología y solución de problemas también asesoró o ayudó a amigos de mi padre que tienen problemas técnicos relacionados con la tecnología ya sea personales o de trabajo.  
</td>
  </tr>
<tr>
    <td rowspan="3"><img src="Assets/miguelprofile.png" alt="Descripción" width="800"></td>
    <td>Miguel Angel Huaman Cataño (u202120615)</td>
  </tr>
  <tr>
        <td>Ingenieria de Software</td>
  </tr>
    <tr>
    <td>Soy Miguel Ángel Huamán Cataño, tengo 21 años y soy estudiante de ingeniería de software. Disfruto trabajar con empeño para alcanzar mis objetivos y nunca me rindo a pesar de los momentos difíciles. Haré todo lo posible para seguir mejorando en este largo camino de ser un buen profesional. </td>
  </tr>
</table>


### 1.2. Solution Profile
Nuestra propuesta es la creación de una solución IOT, la cual tiene como objetivo principal facilitar la comunicación de las personas con discapacidad auditiva con el resto de personas, aplicando tecnologías de IOT y Deep Learning.

#### 1.2.1 Antecedentes y problematica
What?

Según datos del Instituto Nacional de Estadística e Informática (INEI, 2017), en el Perú existen alrededor de 232,000 personas con discapacidad auditiva, de las cuales muchas enfrentan limitaciones importantes en su interacción cotidiana debido a barreras de comunicación. El principal problema que enfrentan estas personas es la dificultad para comunicarse de forma efectiva con quienes no dominan la lengua de señas, afectando significativamente su integración social, educativa y laboral.

When?

La problemática surge continuamente durante las interacciones sociales cotidianas, situaciones educativas y laborales, donde las personas con discapacidad auditiva o del habla requieren comunicarse con otras personas que desconocen la lengua de señas.

Where?

El problema está presente en todo el Perú, particularmente en instituciones educativas, centros laborales, hospitales y entornos públicos donde las personas con discapacidad auditiva o del habla necesitan interactuar constantemente y encuentran barreras para una comunicación efectiva.

Who?

Los usuarios afectados principalmente son personas con discapacidad auditiva y del habla, así como también sus familias, docentes y profesionales de la salud. Los beneficiarios directos serán las instituciones educativas especializadas y centros de rehabilitación que requieren herramientas tecnológicas efectivas para mejorar la inclusión y educación de personas con discapacidad auditiva y del habla.

Why?

Las principales causas del problema radican en la falta de soluciones tecnológicas accesibles que faciliten la comunicación entre personas que usan la lengua de señas y aquellas que no la dominan. Esto genera exclusión social, limitaciones educativas y barreras laborales significativas.

How?

La solución propuesta consiste en la implementación de un dispositivo inteligente basado en tecnología IoT, específicamente un guante equipado con sensores que traducen movimientos y posiciones de la lengua de señas peruana en audio. Este dispositivo facilitará la comunicación directa y clara en tiempo real, mejorando significativamente la interacción social, educativa y laboral.

How much?

¿Cuánto afecta este problema?:
La falta de comunicación efectiva afecta al 100% de las personas con discapacidad auditiva o del habla, reduciendo sus oportunidades educativas, laborales y de inclusión social, según la Defensoría del Pueblo del Perú (2024).

¿Cuánto costará resolver este problema?

El costo dependerá principalmente del desarrollo de la tecnología, la adquisición de sensores especializados y componentes IoT, así como los costos asociados al mantenimiento del software y hardware involucrados.

¿Cuántas personas se beneficiarán?

Se estima que inicialmente se beneficiarían alrededor del 50% de las personas con discapacidad auditiva y del habla en las principales ciudades del Perú, además de docentes y profesionales en centros especializados que trabajen directamente con estas poblaciones.

Conclusiones de 5w y 2h:

En conclusión, mediante el análisis con las 5W's y 2H's, se ha identificado claramente la problemática principal que afecta a personas con discapacidad auditiva y del habla en Perú. SmartSign implementará una solución tecnológica innovadora, accesible y efectiva, que facilitará la inclusión y comunicación, beneficiando directamente a personas con discapacidad auditiva y del habla, así como a instituciones educativas y de rehabilitación.

#### 1.2.2 Lean UX Process
##### 1.2.2.1 Lean UX Problem Statements
**Problem Statement:**
En SmartSign, reconocemos que en el Perú existe una importante población con discapacidad auditiva y del habla, para quienes la comunicación representa una barrera significativa en su vida diaria, limitando su integración social, educativa y laboral.

**Problema:** Muchas personas con discapacidad auditiva o del habla enfrentan dificultades en su comunicación diaria debido a que el entorno social generalmente no domina la lengua de señas, lo que ocasiona exclusión social, aislamiento y dificultades en el aprendizaje.

**Impacto:** Esta solución genera un impacto social altamente positivo al facilitar la inclusión social, educativa y laboral, permitiendo que las personas con discapacidad auditiva y del habla puedan comunicarse de manera efectiva y autónoma en diversos contextos.

##### 1.2.2.2 Lean UX Problem Assumptions
###### Business Outcomes:
- Incremento del 40% en la efectividad de comunicación de los usuarios durante interacciones cotidianas.
- Reducción del 50% en el tiempo requerido para establecer comunicación efectiva en entornos laborales y educativos.
- Aumento del 30% en la inclusión laboral de personas con discapacidad auditiva y del habla en organizaciones que adopten SmartSign.
- Disminución del 40% en la dependencia de intérpretes especializados durante situaciones cotidianas.
- Aumento del 60% en la satisfacción percibida en las interacciones sociales por parte de los usuarios.

###### Users:
- Personas con discapacidad auditiva y del habla.
- Familiares y cuidadores.
- Instituciones educativas especializadas.
- Centros de rehabilitación y salud.

###### User Outcomes & Benefits:
- Usuarios con discapacidad auditiva y del habla: Mayor autonomía e independencia comunicativa, integración social efectiva y acceso mejorado a oportunidades educativas y laborales.
- Instituciones educativas y centros de rehabilitación: Acceso a una herramienta tecnológica efectiva para mejorar los procesos educativos, comunicativos y terapéuticos. 
###### Feature Assumptions:
- Traducción en tiempo real del lenguaje de señas a audio.
- Interfaz de usuario intuitiva y accesible.
- Funcionalidades adicionales como almacenamiento y análisis de datos para monitorear el progreso comunicativo.
- Alertas personalizadas que indican claridad en la traducción y precisión de movimientos.
###### Business Assumptions:
- Creemos que los usuarios necesitan una solución tecnológica innovadora que les permita comunicarse de forma autónoma y efectiva en situaciones cotidianas, educativas y laborales.
- Nuestros clientes serán personas con discapacidad auditiva y del habla, sus familias y centros especializados que busquen facilitar la inclusión social.
- El valor más importante para nuestros usuarios es la independencia en la comunicación y la reducción de barreras sociales.
- Obtendremos a nuestros clientes mediante campañas en redes sociales, convenios con instituciones educativas y de rehabilitación, y participación en eventos enfocados en inclusión social.
- Generaremos ingresos mediante la venta directa del dispositivo y suscripciones mensuales al servicio de soporte técnico y mantenimiento.
- Nuestra ventaja frente a la competencia es la precisión y rapidez en la traducción del lenguaje de señas, combinada con una interfaz amigable y soporte continuo.
- El mayor riesgo del servicio es la resistencia inicial en la adopción tecnológica por parte de usuarios o instituciones. Esto lo resolveremos mediante demostraciones prácticas, testimonios y soporte personalizado constante.
###### User Assumptions:
- **¿Quién es el usuario?**

Los usuarios principales son personas con discapacidad auditiva y del habla, además de instituciones especializadas en educación y rehabilitación.

- **¿Qué problemas resuelve nuestro producto?**

El producto resuelve la barrera comunicativa entre usuarios que utilizan lenguaje de señas y aquellos que no lo dominan.

- **¿Qué características son importantes?**

Las características clave son la traducción precisa en tiempo real, facilidad de uso, portabilidad, alertas de precisión en el movimiento y soporte constante para los usuarios.

- **¿Dónde encaja nuestro producto en su vida diaria?**

Encaja en cualquier situación cotidiana, laboral o educativa que requiera comunicación inmediata y efectiva.

- **¿Cuándo y cómo es usado nuestro producto?**

El producto será utilizado constantemente en entornos sociales, laborales y educativos durante cualquier interacción comunicativa necesaria.

- **¿Cómo debe verse nuestro producto y cómo debe comportarse?**

Debe tener una interfaz visual sencilla, accesible, intuitiva, precisa en su traducción y con tiempos de respuesta rápidos, siendo práctico y portátil.

##### 1.2.2.3 Lean UX Problem Hypothesis Statements

***Hypothesis Statement 1***

**Creemos** que las personas con discapacidad auditiva necesitan una funcionalidad que traduzca rápidamente el lenguaje de señas en audio para comunicarse efectivamente.

**Sabremos** que hemos tenido éxito:

**Cuando** el 90% de los usuarios reporten mayor independencia comunicativa y una mejora significativa en interacciones sociales.

***Hypothesis Statement 2***

**Creemos** que las instituciones educativas y centros de rehabilitación necesitan una herramienta tecnológica que facilite la enseñanza y terapia del lenguaje de señas.

**Sabremos** que hemos tenido éxito:

**Cuando** las instituciones reporten un aumento del 40% en la eficiencia y efectividad en sus programas educativos y terapéuticos.

***Hypothesis Statement 3***

**Creemos** que los usuarios requieren alertas y guías visuales sobre la precisión en sus movimientos para mejorar la exactitud de la traducción.

**Sabremos** que hemos tenido éxito:

**Cuando** el 85% de los usuarios logren perfeccionar significativamente su comunicación con el uso continuo del dispositivo.

***Hypothesis Statement 4***

**Creemos** que la interfaz amigable y accesible será crucial para la adopción masiva de nuestra solución.

**Sabremos** que hemos tenido éxito:

**Cuando** el 95% de los usuarios realicen tareas básicas sin asistencia adicional y manifiesten comodidad y satisfacción con el uso del producto.

##### 1.2.2.4 Lean UX Problem Canvas

![bc_auth.png](Assets/canva.png)


### 1.3. Segmento Objetivo
Según datos del Instituto Nacional de Estadística e Informática (INEI, 2017), en el Perú existen alrededor de 232,000 personas con discapacidad auditiva, enfrentando diariamente desafíos significativos en su comunicación e integración social debido a la falta de herramientas adecuadas para facilitar la interacción efectiva.

Nuestros principales segmentos objetivo son:

**Personas con discapacidad auditiva y del habla:**

Este segmento es clave para nuestra solución, ya que representa a los usuarios directos del dispositivo SmartSign. Estas personas requieren soluciones innovadoras y accesibles que les permitan comunicarse de forma clara y efectiva en cualquier contexto, facilitando su inclusión social, educativa y laboral.

**Instituciones educativas especializadas y centros de rehabilitación:**

Las instituciones educativas especializadas y los centros de rehabilitación constituyen otro segmento objetivo esencial, dado que necesitan herramientas tecnológicas eficientes para mejorar sus procesos educativos y terapéuticos. La implementación del dispositivo SmartSign permitirá realizar evaluaciones en tiempo real, facilitar el aprendizaje del lenguaje de señas y mejorar significativamente la comunicación en entornos educativos y de rehabilitación.
## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
Luego de realizar una investigación del mercado peruano e internacional de soluciones tecnológicas para personas con discapacidad auditiva, hemos identificado los siguientes competidores potenciales para SmartSign:
<ul>
    <li>
        <b>SignAloud:  </b>Es un guante inteligente desarrollado por investigadores estadounidenses que traduce lenguaje de señas a texto y voz. Aunque no está específicamente adaptado al lenguaje de señas peruano, su tecnología basada en sensores de movimiento representa una competencia directa en el mercado global de dispositivos de traducción para personas con discapacidad auditiva. Su principal limitación en el contexto peruano es la falta de adaptación cultural y lingüística específica a las señas utilizadas en el país.
    </li>
    <li>
        <b>Hand Talk: </b> Aplicación móvil brasileña que utiliza un avatar 3D para traducir texto y voz al lenguaje de señas. Aunque se enfoca principalmente en el mercado brasileño y utiliza LIBRAS (Lengua Brasileña de Señas), su presencia creciente en Latinoamérica y su modelo de negocio basado en suscripciones institucionales la convierten en un competidor relevante en el segmento de soluciones de comunicación para personas con discapacidad auditiva.
    </li>
    <li>
        <b>IRIS Project: </b> Iniciativa peruana desarrollada por la Universidad Nacional de Ingeniería que consiste en un dispositivo wearable que traduce texto a lenguaje de señas peruano mediante un sistema de proyección holográfica. A diferencia de SmartSign, se enfoca en la dirección inversa de la comunicación (de oyentes a personas sordas), pero compite en el mismo espacio de mercado de tecnologías asistivas para la comunidad con discapacidad auditiva en Perú.
    </li>
</ul>

#### 2.1.1. Análisis competivio
<table><tr><th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th></tr>
<tr><td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?  </td><td colspan="7" valign="top"> Este análisis se concretó teniendo como finalidad identificar a nuestros potenciales competidores en el mercado de soluciones para personas con discapacidad auditiva en Perú e idear estrategias y tácticas para diferenciarnos de ellos, aprovechando nuestras ventajas competitivas en el sector IoT. td></tr>
<tr><td colspan="6" valign="top"><p><b>Nombre</b></p><p></p></td><td colspan="3" valign="top"><b>SmartSign </b></td><td colspan="3" valign="top"><b>SignAloud</b></td><td colspan="3" valign="top"><b>HandTalk</b></td><td valign="top"><b> IRIS Project </b></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td><td colspan="3" rowspan="2" valign="top"><b>Overview</b></td><td colspan="3" rowspan="2" valign="top"> </b> SmartSign se destaca por su enfoque específico en mejorar la comunicación de personas con discapacidad auditiva en Perú mediante tecnologías IoT y Deep Learning. Ofrece un guante equipado con sensores que traduce movimientos y posiciones de la lengua de señas peruana en audio en tiempo real.
</td><td colspan="3" rowspan="2" valign="top">Es un guante inteligente desarrollado por investigadores estadounidenses que traduce lenguaje de señas a texto y voz. Utiliza sensores de movimiento avanzados y algoritmos de reconocimiento para identificar gestos y convertirlos en palabras. Aunque tiene reconocimiento internacional, no está adaptado específicamente a la lengua de señas peruana ni considera factores culturales locales.</td><td colspan="3" rowspan="2" valign="top">Hand Talk es una aplicación móvil brasileña que utiliza un avatar 3D para traducir texto y voz al lenguaje de señas. Con presencia creciente en Latinoamérica, se enfoca principalmente en LIBRAS (Lengua Brasileña de Señas) y opera mediante un modelo de suscripciones institucionales. A diferencia de SmartSign, traduce en dirección contraria (de voz/texto a señas).</td><td rowspan="2" valign="top">IRIS Project es una iniciativa peruana desarrollada por la Universidad Nacional de Ingeniería que consiste en un dispositivo wearable que traduce texto a lenguaje de señas peruano mediante un sistema de proyección holográfica. Se enfoca en la comunicación de oyentes hacia personas sordas, complementando pero no compitiendo directamente con la función de SmartSign.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td><td colspan="3" rowspan="2" valign="top">SmartSign se destaca por su enfoque localizado en el lenguaje de señas peruano, lo que permite una adaptación precisa a las necesidades de la comunidad con discapacidad auditiva nacional. Además, su integración con tecnologías IoT y Deep Learning ofrece una experiencia más confiable y personalizada, brindando traducción en tiempo real con alta precisión y capacidad de aprendizaje continuo
</td><td colspan="3" rowspan="2" valign="top">SignAloud sobresale por su tecnología de sensores altamente sensibles y su reconocimiento internacional como solución pionera en la traducción de lenguaje de señas. Su principal ventaja es la madurez del producto y el respaldo de instituciones de investigación estadounidenses.</td><td colspan="3" rowspan="2" valign="top">Hand Talk ofrece una ventaja competitiva a través de su avatar 3D visualmente atractivo y su enfoque en instituciones educativas. Su modelo de negocio basado en suscripciones y su facilidad de implementación en dispositivos existentes (smartphones) lo hacen accesible para entornos educativos.</td><td rowspan="2" valign="top">IRIS Project destaca por ser una iniciativa local peruana con comprensión del contexto cultural nacional y por su innovadora tecnología de proyección holográfica. Su relación con la Universidad Nacional de Ingeniería le proporciona respaldo académico y facilidad de pruebas con usuarios locales.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td><td colspan="3" valign="top"><b>Mercado objetivo</b></td><td colspan="3" valign="top">SmartSign tiene como mercado objetivo principal a las personas con discapacidad auditiva en Perú (aproximadamente 232,000 personas según INEI), sus familias y cuidadores, así como instituciones educativas especializadas, centros de rehabilitación y organizaciones dedicadas a la inclusión social. El enfoque está en usuarios que buscan autonomía comunicativa en entornos cotidianos, educativos y laborales. </td><td colspan="3" valign="top">SignAloud está dirigido principalmente al mercado estadounidense e internacional, enfocándose en personas con discapacidad auditiva y del habla, instituciones educativas y centros médicos especializados. Su orientación es más global y menos adaptada al contexto latinoamericano o peruano.</td><td colspan="3" valign="top">Hand Talk se dirige principalmente a instituciones educativas, empresas comprometidas con la inclusión y órganos gubernamentales en Brasil y otros países latinoamericanos. Su enfoque está en proveer soluciones institucionales más que dispositivos personales para usuarios finales.</td><td valign="top"> IRIS Project se orienta a personas oyentes que necesitan comunicarse con personas sordas en Perú, incluyendo familiares, docentes, personal médico e instituciones gubernamentales. El enfoque es complementario al de SmartSign, abordando el otro lado de la comunicación.</td></tr>
<tr><td colspan="3" valign="top"><b>Estrategias de Marketing</b></td><td colspan="3" valign="top"><p>SmartSign: Publicidad dirigida en redes sociales y plataformas especializadas en accesibilidad, colaboración con asociaciones peruanas de personas sordas, y demostraciones prácticas en instituciones educativas y eventos de tecnología inclusiva.</p></td><td colspan="3" valign="top"><p>SignAloud: Marketing digital internacional, participación en conferencias científicas y de tecnología asistiva, y colaboraciones con universidades e instituciones de investigación.</p></td><td colspan="3" valign="top">Hand Talk: Enfoque en marketing B2B dirigido a instituciones, creación de material educativo sobre accesibilidad, y programas de responsabilidad social corporativa.</td><td valign="top"><p>IRIS Project: Difusión académica a través de la universidad, participación en eventos de innovación social, y alianzas con entidades gubernamentales peruanas..</p><p></p></td></tr>
<tr><td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td><td colspan="3" valign="top"><b>Productos y Servicios</b></td><td colspan="3" valign="top">SmartSign ofrece un guante inteligente IoT equipado con sensores de movimiento, flexión y posición que traduce la lengua de señas peruana a audio en tiempo real. Incluye una plataforma de aprendizaje continuo basada en Deep Learning que mejora progresivamente la precisión de la traducción, además de soporte técnico especializado y capacitación para usuarios e instituciones.</td><td colspan="3" valign="top">SignAloud proporciona guantes con tecnología de sensores que reconocen gestos de lenguaje de señas americano (ASL) y los traduce a texto y voz. Su enfoque está en la precisión del reconocimiento mediante algoritmos avanzados, pero con menor adaptabilidad cultural a variantes regionales de lenguajes de señas.</td><td colspan="3" valign="top">Hand Talk ofrece una aplicación móvil con un avatar 3D llamado "Hugo" que traduce texto y voz a LIBRAS (lengua de señas brasileña) y parcialmente a otras variantes latinoamericanas. Proporciona planes de suscripción para instituciones y herramientas de integración web para sitios corporativos.</td><td valign="top">IRIS Project desarrolla un dispositivo wearable con sistema de proyección holográfica que traduce texto ingresado por usuarios oyentes al lenguaje de señas peruano. Incluye una biblioteca de gestos específicamente adaptada al contexto cultural nacional.</td></tr>
<tr><td colspan="3" valign="top"><b>Precios y Costos</b></td><td colspan="3" valign="top"> SmartSign ofrece un modelo mixto: venta del dispositivo hardware (guante inteligente) con precio Para instituciones educativas y centros de rehabilitación existen planes corporativos con descuentos por volumen. Los costos principales incluirían el desarrollo de hardware, investigación en Deep Learning, y adaptación cultural del sistema.</td><td colspan="3" valign="top">SignAloud tiene un modelo de venta directa del dispositivo con precios entre $1,800-$2,500 USD, significativamente más costoso que las alternativas locales. No ofrece planes de suscripción pero cobra por actualizaciones mayores de software.</td><td colspan="3" valign="top">Hand Talk utiliza un modelo de suscripción pura, con planes que van desde $300 a $1,200 USD anuales para instituciones según el número de usuarios. No requiere inversión en hardware específico al funcionar como aplicación móvil.</td><td valign="top"><p>IRIS Project se encuentra en fase piloto con un modelo tentativo de venta de dispositivo entre S/. 900-1,100, con énfasis en acuerdos institucionales y potencial financiamiento universitario para investigación adicional.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Canales de distribución</b></td><td colspan="3" valign="top"><p>- SmartSign distribuye sus dispositivos a través de su sitio web oficial, alianzas con asociaciones de personas sordas, y acuerdos directos con instituciones educativas y rehabilitadoras. Ofrece demostraciones presenciales y posibilidad de prueba del dispositivo antes de la compra.</p><p></p></td><td colspan="3" valign="top"><p>- SignAloud se distribuye principalmente a través de su plataforma web internacional y distribuidores especializados en tecnología asistiva. Su presencia física en Perú es limitada.</p></td><td colspan="3" valign="top"><p>- Hand Talk se distribuye exclusivamente como aplicación móvil a través de tiendas de aplicaciones (Google Play y App Store) y mediante ventas corporativas directas para planes institucionales.</p></td><td valign="top"><p>- IRIS Project tiene distribución limitada a través de canales universitarios y proyectos piloto con instituciones seleccionadas, sin presencia comercial masiva todavía.</p></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td><td colspan="3" valign="top"><b>Fortalezas</b></td><td colspan="3" valign="top"><p>- SmartSign: Enfoque localizado en lenguaje de señas peruano, tecnología IoT integrada con Deep Learning, colaboración con instituciones locales, y solución portable que no requiere instalaciones fijas.</p></td><td colspan="3" valign="top"><p>- SignAloud: Reconocimiento internacional, tecnología de sensores avanzada, respaldo de investigación académica, y mayor tiempo en el mercado.</p></td><td colspan="3" valign="top"><p>- Hand Talk: Facilidad de implementación al no requerir hardware adicional, avatar visual atractivo, y modelo de negocio escalable basado en suscripciones.</p></td><td valign="top"><p>- IRIS Project: Conocimiento específico del contexto peruano, tecnología innovadora de proyección holográfica, y respaldo académico de la Universidad Nacional de Ingeniería.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Debilidades</b></td><td colspan="3" valign="top"><p>- Competencia feroz</p><p>- SmartSign: Costos iniciales de hardware relativamente altos, dependencia de actualizaciones de software para mejorar precisión, y necesidad de adaptación continua al evolucionar el lenguaje de señas peruano.</p></td><td colspan="3" valign="top"><p>- SignAloud: Falta de adaptación al contexto cultural peruano, precio elevado para el mercado local, y enfoque limitado a la traducción sin considerar aspectos educativos.</p><p>- Calidad de las reseñas</p><p>- Competencia</p></td><td colspan="3" valign="top"><p>- Hand Talk: Dependencia de dispositivos móviles con buena conectividad, enfoque en dirección contraria a la traducción (de texto a señas, no de señas a texto), y adaptación parcial al contexto latinoamericano fuera de Brasil.</p></td><td valign="top"><p>- IRIS Project: Producto en fase temprana de desarrollo, limitaciones en la portabilidad del sistema de proyección, y enfoque exclusivo en la comunicación de oyentes hacia personas sordas.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Oportunidades</b></td><td colspan="3" valign="top"><p>- SmartSign: Crecimiento del mercado de tecnologías inclusivas en Perú, políticas gubernamentales favorables para la inclusión, posibilidad de expansión a otros países latinoamericanos con adaptaciones culturales, y alianzas con sistema de salud público/privado.</p></td><td colspan="3" valign="top"><p>- SignAloud: Potencial adaptación al mercado latinoamericano, desarrollo de versiones más económicas, y colaboraciones con universidades locales para investigación.</p></td><td colspan="3" valign="top"><p>- Hand Talk: Expansión de biblioteca de señas para incluir más variantes regionales latinoamericanas, desarrollo de funcionalidades offline, y alianzas con fabricantes de smartphones.</p></td><td valign="top"><p>- IRIS Project: Complementariedad con otras soluciones como SmartSign, potencial comercialización internacional de la tecnología de proyección, y oportunidades de financiamiento para investigación adicional.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Amenazas</b></td><td colspan="3" valign="top"><p>- SmartSign: Entrada de competidores internacionales con mayor capital de inversión, cambios regulatorios en tecnologías IoT, y resistencia a la adopción tecnológica en comunidades tradicionales.</p></td><td colspan="3" valign="top"><p>- SignAloud: Soluciones locales mejor adaptadas culturalmente, barreras de entrada por precio elevado, y posibles restricciones de importación.</p></td><td colspan="3" valign="top"><p>- Hand Talk: Dependencia de políticas de tiendas de aplicaciones, competencia creciente de soluciones similares, y limitaciones en la precisión de la traducción inversa.</p></td><td valign="top"><p>- IRIS Project: Desafíos en la transición de proyecto académico a producto comercial, limitaciones de financiamiento para expansión, y competencia de soluciones más maduras.</p></td></tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

**Diferenciación de Producto:**

Estrategia: SmartSign se enfocará en resaltar su adaptación específica al lenguaje de señas peruano y su implementación de tecnologías IoT y Deep Learning que permiten una traducción más precisa y contextualizada.
Tácticas: Para llevar a cabo esta estrategia, se desarrollará una biblioteca especializada de gestos específicos del lenguaje de señas peruano, se implementarán actualizaciones trimestrales del algoritmo de Deep Learning basadas en datos recopilados de usuarios reales peruanos, y se crearán materiales de marketing que destaquen casos de éxito locales y testimonios de usuarios.

**Desarrollo Continuo:**

Estrategia: El startup se comprometió a la mejora constante de la tecnología mediante la integración de avances en IoT y aprendizaje automático, manteniendo el enfoque en las necesidades específicas de la comunidad peruana con discapacidad auditiva.
Tácticas: Para implementar esta estrategia, se establecerá un programa de "beta testers" con miembros de la comunidad sorda peruana para probar nuevas funcionalidades, se implementará un sistema de retroalimentación directa donde los usuarios puedan reportar errores de traducción, y se desarrollará un plan de actualización trimestral del firmware del dispositivo.

**Colaboraciones Estratégicas:**

Estrategia: Se buscarán asociaciones con instituciones educativas especializadas, organizaciones de personas sordas y entidades gubernamentales para fortalecer la presencia en el mercado y mejorar continuamente la adaptación cultural del producto.
Tácticas: Para ejecutar esta estrategia, se establecerán convenios con instituciones educativas especializadas en Lima y provincias, se desarrollará un programa de embajadores dentro de la comunidad de personas sordas, y se colaborará con el CONADIS para alinear el desarrollo del producto con las políticas nacionales de inclusión.

**Enfoque en la Experiencia del Usuario:**

Estrategia: La prioridad será la satisfacción del usuario y la facilidad de uso del dispositivo, considerando las necesidades específicas de personas con discapacidad auditiva en el contexto peruano.
Tácticas: Para lograr esta estrategia, se realizarán pruebas de usabilidad trimestrales con grupos diversos de usuarios, se implementará un programa de capacitación personalizada para nuevos usuarios, y se desarrollarán materiales de soporte en formatos accesibles, incluyendo tutoriales en lengua de señas peruana.

**Accesibilidad y Modelo de Negocio Inclusivo:**

Estrategia: Se desarrollará un modelo de precios que permita el acceso a la tecnología por parte de diversos segmentos socioeconómicos, maximizando el impacto social sin comprometer la sostenibilidad del negocio.
Tácticas: Para implementar esta estrategia, se establecerá un programa de subsidio cruzado donde las ventas institucionales permitan ofrecer precios reducidos a usuarios individuales de bajos recursos, se desarrollará un modelo de leasing para instituciones educativas, y se creará un fondo de impacto social en colaboración con ONGs y empresas privadas.

**Análisis Competitivo Continuo:**

Estrategia: El startup se comprometió a monitorear continuamente el mercado de tecnologías asistivas tanto a nivel local como internacional, adaptando su estrategia según la evolución del ecosistema competitivo.
Tácticas: Para llevar a cabo esta estrategia, se realizarán informes trimestrales de benchmarking, se implementará un sistema de alertas para monitorear avances tecnológicos relevantes, y se participará activamente en conferencias y eventos internacionales sobre tecnologías asistivas para identificar tendencias emergentes.

### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas

<h3>Preguntas Generales</h3>
<ol>
    <li>¿Cuál es su nombre?</li>
    <li>¿Cuántos años tiene?</li>
    <li>¿En qué ciudad y distrito reside?</li>
    <li>¿A qué se dedica actualmente?</li>
</ol>

<h3>Segmento 1: Personas con discapacidad auditiva y del habla (Cuidadores)</h3>
<ol>
    <li>¿Cuál es su relación con la persona con discapacidad auditiva o del habla que cuida?</li>
    <li>¿Qué estrategias o métodos utiliza actualmente para comunicarse con ella?</li>
    <li>¿En qué tipo de situaciones suele haber más dificultades de comunicación (visitas médicas, trámites, tiendas, transporte, etc.)?</li>
    <li>¿Con qué tipo de personas se presentan mayores barreras (familiares, profesores, personal de atención al cliente, desconocidos)?</li>
    <li>¿Utilizan actualmente algún tipo de tecnología o aplicación para facilitar la comunicación? ¿Cuál ha sido su experiencia?</li>
    <li>¿Qué limitaciones ha encontrado en las herramientas existentes para ayudar en la comunicación?</li>
    <li>¿Ha presenciado o vivido junto con la persona bajo su cuidado situaciones de exclusión o malentendidos debido a la barrera del lenguaje?</li>
    <li>¿Cómo se sienten usted y la persona que cuida cuando no pueden hacerse entender en ciertos contextos?</li>
    <li>¿Considera que la sociedad en general está preparada para interactuar adecuadamente con personas con discapacidad auditiva o del habla?</li>
    <li>¿Cree que esta situación afecta las oportunidades educativas, sociales o laborales de la persona que cuida?</li>
    <li>¿Qué tipo de funcionalidades esperaría de un dispositivo o aplicación para facilitar la comunicación?</li>
    <li>¿Qué tipo de mensajes o expresiones serían más útiles que se pudieran traducir automáticamente con la ayuda de un dispositivo?</li>
    <li>¿En qué espacios le gustaría que esta herramienta sea especialmente útil (hospitales, bancos, centros educativos, etc.)?</li>
</ol>

<h3>Segmento 2: Instituciones educativas especializadas y centros de rehabilitación</h3>
<ol>
    <li>¿Cuál es su rol dentro de la institución?</li>
    <li>¿Cuántos estudiantes o pacientes con discapacidad auditiva o del habla atienden en promedio?</li>
    <li>¿Qué métodos utilizan actualmente para facilitar la enseñanza o terapia del lenguaje de señas?</li>
    <li>¿Han utilizado tecnología para mejorar la comunicación o el aprendizaje de sus estudiantes? ¿Cuál fue su experiencia?</li>
    <li>¿Qué dificultades enfrentan sus estudiantes o pacientes al interactuar con personas fuera del entorno institucional?</li>
    <li>¿Considera que el lenguaje de señas se enseña de forma adecuada en los niveles educativos actuales?</li>
    <li>¿Qué limitaciones tienen actualmente en cuanto a recursos tecnológicos para mejorar sus procesos de enseñanza?</li>
    <li>¿Qué tipo de dispositivo o aplicación cree que sería útil para reforzar la enseñanza del lenguaje de señas?</li>
    <li>¿Le gustaría contar con una herramienta que permita evaluar en tiempo real la expresión en señas de los estudiantes?</li>
</ol>

<h3>Validación de la propuesta</h3>
<ol>
    <li>Se presenta al entrevistado la idea del proyecto SmartSign y sus principales funcionalidades (traducción en tiempo real de señas a texto o voz y viceversa, uso de IA para mejorar la precisión, compatibilidad con dispositivos móviles y wearables).</li>
    <li>¿Qué le parece la propuesta de SmartSign?</li>
    <li>¿Cree que podría ser útil en su vida diaria o en su entorno educativo/laboral?</li>
    <li>¿Alguna vez ha usado una tecnología similar?</li>
    <li>¿Cuál es el aspecto que más le llama la atención de esta propuesta?</li>
    <li>¿Qué sugerencias o mejoras le gustaría que tenga el dispositivo o la aplicación?</li>
    <li>¿En qué escenarios le gustaría poder utilizar esta solución?</li>
</ol>


#### 2.2.2. Registro de entrevistas

Entrevistado #1:
Isaac Burgos

● Sexo: Masculino

● Edad: 22 años

● Distrito en el que vive: Breña

● Ocupación: Comerciante

● Link: [Click para ver entrevista](https://youtu.be/oU4ckNnNtoU)


![image](https://github.com/user-attachments/assets/ce124bd4-7f88-4bae-b596-1fe1a8c3c2cf)

Resumen:

<p align="justify"> Isaac Burgos, comerciante de 22 años, compartió su experiencia sobre la vida de su hermano, quien tiene discapacidad del habla. Isaac destacó las dificultades que enfrenta su hermano tanto en la escuela como en su vida diaria debido a esta discapacidad. Sin embargo, en el entorno familiar han logrado adaptarse y comunicarse de forma más fluida. Isaac aprendió lenguaje de señas para mejorar la comunicación con su hermano. A pesar de los avances familiares, mencionó que la sociedad aún no está completamente preparada para fomentar la inclusión de personas con discapacidades del habla. Isaac subrayó que un dispositivo inteligente que facilite la vida de estas personas sería un gran avance para la inclusión social. </p>

Entrevistado #2:

Yasmin Díaz

● Sexo: Femenino

● Edad: 20 años

● Distrito en el que vive: San Martín de Porres

● Ocupación: Estudiante

● Link: [Click para ver entrevista](https://youtu.be/WRmBH8R3Po0)

![image](https://github.com/user-attachments/assets/f7d9fe7b-7f99-4824-bc26-a7747ffdba80)

Resumen:

<p align="justify"> Yasmin Díaz, estudiante de Publicidad, compartió su experiencia sobre su hermano, quien sufrió una enfermedad que le causó la discapacidad del habla. A pesar de que Yasmin aprendió lenguaje de señas, la comunicación en la familia no ha sido completamente fluida ya que no todos lograron aprenderlo adecuadamente. Por ello, la familia optó por usar aplicaciones de mensajería como WhatsApp, Facebook e Instagram para comunicarse. A pesar de la discapacidad, su hermano ha logrado conseguir trabajo en un almacén y desempeñar sus tareas de manera efectiva. Yasmin expresó el deseo de que existieran tecnologías o dispositivos que facilitaran la comunicación de personas con discapacidad del habla, especialmente en citas médicas o laborales. </p>

Entrevistado #3:

Emilio Alexander

● Sexo: Masculino

● Edad: 23 años

● Distrito en el que vive: Cercado de Lima

● Ocupación: Estudiante

● Link: [Click para ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20181h103_upc_edu_pe/EUhrCY-bJoxBgf1cCl3CcBoBsoBB5oHdv9-r7w4upVl8Zg?e=FDXc1b&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

![image](https://github.com/user-attachments/assets/26abf731-5843-4cfb-82b8-8f5cc8542ecf)

Resumen:

<p align="justify"> Emilio Alexander, estudiante de la UNMSM, nos habló sobre su sobrino, quien tiene discapacidad auditiva y del habla. Emilio mencionó que la familia ha podido comunicarse con cierta facilidad usando aplicaciones de mensajería como WhatsApp o Messenger, aunque reconoció que este tipo de comunicación no es ideal debido a la falta de inmediatez y espontaneidad. A pesar de no haber vivido situaciones de discriminación, Emilio apoya la idea de que se desarrollen tecnologías que permitan una comunicación instantánea y eficiente para personas con discapacidades, ya que esto contribuiría significativamente a la inclusión social. </p>

Entrevistado #4:

Luis Fernando Rivas

● Sexo: Masculino

● Edad: 25 años

● Distrito en el que vive: San Martín de Porres

● Ocupación: Estudiante Universitario

● Link: [Click para ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120615_upc_edu_pe/EdBS2d5cOS1CqWnHhxXhXNABy0G0QRaGoQFGigH4O-izhw?e=QbYcnf&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

![image](https://github.com/user-attachments/assets/7c0fe1ff-4776-42dc-af75-32d86597aa59)

Resumen:

<p align="justify"> Luis Fernando Rivas, estudiante universitario y voluntario en talleres para personas con discapacidad auditiva, comentó sobre las dificultades que enfrentan sus estudiantes para comunicarse fuera del entorno de los talleres, ya que el acceso a tecnologías adaptadas es limitado. Además, mencionó que el lenguaje de señas no se enseña adecuadamente en los colegios. Luis considera que una herramienta como SmartSign, que traduzca las señas a audio en tiempo real, sería muy útil, especialmente si fuera fácil de usar y económica. Luis expresó que le gustaría aplicar esta herramienta en talleres, en la universidad y en espacios públicos. </p>

Entrevistado #5:

Sebastián Ríos

● Sexo: Masculino

● Edad: 20 años

● Distrito en el que vive: Santiago de Surco

● Ocupación: Estudiante Universitario

● Link: [Click para ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120615_upc_edu_pe/EUPC6b4_4ehLpOeKO_wyZ3wBz-WQOWnvEljuSGk_OD1UrA?e=8YED8e&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

![image](https://github.com/user-attachments/assets/7c9a7668-06ae-4b7e-91bd-8b13fc7589b0)

Resumen:

<p align="justify"> Sebastián Ríos, estudiante de Psicología y voluntario en talleres de apoyo a personas con discapacidad auditiva, compartió su experiencia trabajando con estudiantes que, fuera del entorno de los talleres, se sienten incomprendidos debido a la falta de acceso a tecnologías adaptadas. Sebastián destacó la importancia de que el lenguaje de señas se enseñe adecuadamente en las escuelas y expresó que una aplicación divertida o un dispositivo que traduzca las señas en tiempo real sería una excelente herramienta para mejorar la inclusión. También mencionó que la propuesta de SmartSign, con su capacidad de traducción instantánea, es una solución muy prometedora, especialmente si es personalizable y compatible con asistentes virtuales. </p>

#### 2.2.3. Análisis de entrevistas

Análisis de las Entrevistas: Familiares de Personas con Discapacidad Auditiva:

Los entrevistados han tenido que adaptarse a la situación, principalmente aprendiendo el lenguaje de señas o utilizando aplicaciones de mensajería como WhatsApp y Facebook para facilitar la comunicación. Sin embargo, destacan que estas soluciones no son óptimas debido a que no permiten una comunicación espontánea e inmediata. Los entrevistados señalan la falta de inclusión social como un problema persistente, aunque mencionan casos de integración laboral exitosa a pesar de las limitaciones. Coinciden en que la sociedad no está preparada para fomentar una inclusión completa de las personas con discapacidad auditiva, creando barreras comunicacionales en diversos contextos. Consideran que una herramienta como SmartSign representaría un avance significativo hacia la inclusión social al eliminar las barreras comunicacionales existentes.

Análisis de las Entrevistas: Educadores y Voluntarios que Trabajan con Personas con Discapacidad Auditiva:

Los entrevistados destacan las limitaciones de los métodos actuales, que se basan principalmente en recursos manuales como cartillas visuales, juegos y videos, con un acceso muy limitado a tecnologías adaptadas al contexto peruano. Los educadores coinciden en señalar deficiencias sistemáticas en la enseñanza del lenguaje de señas en las instituciones educativas regulares, lo que perpetúa las dificultades de comunicación e integración social. Observan que sus estudiantes experimentan aislamiento y frustración cuando intentan comunicarse fuera de los entornos controlados de los talleres. Respecto a SmartSign, ambos voluntarios evalúan positivamente la propuesta, especialmente la capacidad de traducción en tiempo real de señas a audio. Sugieren características importantes como facilidad de uso, accesibilidad económica


### 2.3. Needfinding
En esta sección presentamos los resultados de nuestro proceso de investigación y análisis de necesidades para el proyecto SmartSign. 
#### 2.3.1. User Personas
Basados en la información recopilada durante nuestras entrevistas y análisis competitivo, hemos desarrollado User Personas representativas de nuestros segmentos objetivo. 

Segmento 1: Personas con discapacidad auditiva y del habla:
![image](https://github.com/user-attachments/assets/3d35ad00-29c4-415f-bb3a-1fdc2dafc12d)

Segmento 2: Instituciones educativas especializadas y centros de rehabilitación:
![image](https://github.com/user-attachments/assets/eb39cfe6-c3c3-479a-afc3-36024250726c)


#### 2.3.2. User Task Matrix
En esta sección se describen las tareas realizadas por los distintos segmentos objetivos.

Segmento 1: Personas con discapacidad auditiva y del habla:

| Tarea                                                      | Frecuencia | Importancia |
|------------------------------------------------------------|------------|-------------|
| Comunicarse con compañeros de clase que no conocen lengua de señas | Alta       | Alta        |
| Participar en discusiones grupales en clase                 | Alta       | Alta        |
| Expresar preguntas o dudas durante las clases               | Alta       | Alta        |
| Comunicarse con profesores durante asesorías                | Media      | Alta        |
| Interactuar con personal administrativo de la universidad   | Media      | Alta        |
| Participar en actividades sociales universitarias           | Media      | Alta        |
| Comunicarse con personas en transporte público              | Alta       | Media       |
| Realizar trámites en instituciones públicas o privadas      | Baja       | Alta        |
| Comunicarse en situaciones de emergencia                    | Baja       | Crítica     |
| Participar en entrevistas laborales o prácticas             | Baja       | Alta        |
| Interactuar con dependientes en tiendas o restaurantes      | Alta       | Media       |
| Comunicarse con familiares que no dominan lengua de señas   | Alta       | Alta       |


Segmento 2: Instituciones educativas especializadas y centros de rehabilitación:

| Tarea                                                        | Frecuencia | Importancia |
|--------------------------------------------------------------|------------|-------------|
| Comunicarse efectivamente con estudiantes con discapacidad auditiva | Alta       | Crítica     |
| Explicar conceptos complejos a estudiantes con discapacidad auditiva | Alta       | Alta        |
| Evaluar la comprensión de estudiantes con discapacidad auditiva | Alta       | Alta        |
| Facilitar la interacción entre estudiantes con y sin discapacidad | Alta       | Alta        |
| Informar a padres sobre el progreso de estudiantes con discapacidad | Media      | Alta        |
| Adaptar material educativo para estudiantes con discapacidad auditiva | Alta       | Alta        |
| Coordinar con intérpretes de lengua de señas                 | Media      | Media       |
| Gestionar situaciones de emergencia con estudiantes con discapacidad | Baja       | Crítica     |
| Participar en reuniones con otros docentes sobre inclusión   | Media      | Media       |
| Capacitarse en nuevas metodologías de enseñanza inclusiva    | Media      | Alta        |
| Documentar necesidades específicas de comunicación de cada estudiante | Media      | Alta        |
| Mediar en conflictos derivados de barreras de comunicación   | Media      | Alta        |



#### 2.3.3. User Journey Mapping

En esta sección presentamos los User Journey Maps para nuestros segmentos objetivo. Estos mapas ilustran el recorrido end-to-end que experimentan actualmente nuestros usuarios.

Segmento 1: Personas con discapacidad auditiva y del habla:

![image](https://github.com/user-attachments/assets/4cbdf297-c191-4b8a-b68e-a8ae5c21a22e)


Segmento 2: Instituciones educativas especializadas y centros de rehabilitación:

![image](https://github.com/user-attachments/assets/2a410488-96b5-446c-a72f-06b6d67c5974)


#### 2.3.4. Empathy Mapping
En esta sección presentamos los Empathy Maps desarrollados para cada uno de nuestros User Personas. 

Segmento 1: Personas con discapacidad auditiva y del habla:

![image](https://github.com/user-attachments/assets/61e1e76f-803a-4906-ba9b-5d0848b099e4)


Segmento 2: Instituciones educativas especializadas y centros de rehabilitación:

![image](https://github.com/user-attachments/assets/84a8a7fc-a0e5-4807-b0c2-6ef7afc6ee41)



#### 2.3.5. As-is Scenario Mapping

Esta sección muestra los As-Is Scenario Maps elaborados para cada User Persona, proporcionando una representación visual de las experiencias actuales de nuestros usuarios. 

Segmento 1: Personas con discapacidad auditiva y del habla:

![image](https://github.com/user-attachments/assets/006db391-d6af-41f6-b9ae-9366064541a5)


Segmento 2: Instituciones educativas especializadas y centros de rehabilitación:

![image](https://github.com/user-attachments/assets/90531be7-076b-4b57-91c2-9b9339bb43b4)


### 2.4. Ubiquitous Language

En esta sección presentamos el glosario de términos y conceptos fundamentales del dominio de negocio relacionados con nuestra solución SmartSign. 

| Término                      | Definición |
|-------------------------------|------------|
| Sign Language (Lengua de Señas) | Sistema lingüístico visual-gestual utilizado por personas con discapacidad auditiva o del habla, que emplea configuraciones de manos, movimientos, orientaciones y expresiones faciales para transmitir significados. |
| Peruvian Sign Language (Lengua de Señas Peruana) | Variante específica de la lengua de señas utilizada en Perú, con características léxicas y gramaticales propias que la distinguen de otras lenguas de señas. |
| Hearing Impairment (Discapacidad Auditiva) | Disminución total o parcial de la capacidad de percibir sonidos, que puede variar en grados desde leve hasta profunda, afectando la comunicación verbal. |
| Inclusive Education (Educación Inclusiva) | Enfoque educativo que reconoce la diversidad de necesidades y capacidades de todos los estudiantes, adaptando metodologías y recursos para garantizar su participación efectiva. |
| Gesture Recognition (Reconocimiento de Gestos) | Tecnología que permite a dispositivos electrónicos identificar y clasificar movimientos específicos de las manos, brazos y cuerpo para su interpretación como comandos o lenguaje. |
| Haptic Feedback (Retroalimentación Háptica) | Sistema de respuesta que utiliza el sentido del tacto mediante vibraciones o fuerzas para comunicar información al usuario de un dispositivo. |
| Communication Barrier (Barrera de Comunicación) | Obstáculo que dificulta o impide la transmisión efectiva de información entre un emisor y un receptor, especialmente relevante en contextos de discapacidad sensorial. |
| Real-time Translation (Traducción en Tiempo Real) | Proceso de conversión inmediata de un sistema de comunicación a otro, sin retrasos significativos que afecten la fluidez de la interacción. |
| Social Inclusion (Inclusión Social) | Proceso que asegura que todas las personas, independientemente de sus capacidades, tengan las mismas oportunidades de participar plenamente en todos los aspectos de la sociedad. |
| Assistive Technology (Tecnología Asistiva) | Dispositivos, software o equipos diseñados para mantener, aumentar o mejorar las capacidades funcionales de personas con discapacidad. |
| Smart Glove (Guante Inteligente) | Dispositivo wearable equipado con sensores que detecta movimientos y posiciones de la mano y dedos para capturar e interpretar gestos específicos. |
| Sensor Calibration (Calibración de Sensores) | Proceso de ajuste de los sensores del dispositivo para adaptarse a las características específicas del usuario, mejorando la precisión en la detección de gestos. |
| Communication Autonomy (Autonomía Comunicativa) | Capacidad de una persona para expresarse e interactuar independientemente con otros, sin necesidad de intermediarios o asistencia constante. |


## Capítulo III: Requirements Specification
### 3.1. To-Be Scenario Mapping
### 3.2. User Stories
| Story ID | Título                               | Descripción                                                                                                                                           | Criterios de Aceptación                                                                 | Relacionado con (Epic ID)                        |
|:--------:|:--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|--------------------------------------------------|
|   US01   | Comunicación en conversaciones cotidianas | Como persona con discapacidad auditiva, quiero poder comunicarme fácilmente con personas que no conocen lengua de señas, para sentirme incluida.      | Se identifica la barrera de comunicación en interacciones sociales básicas.            | EPIC-01            |
|   US02   | Expresión en entornos públicos       | Como persona con discapacidad del habla, quiero poder expresar mis ideas de forma clara en entornos públicos, para no sentirme ignorado.             | Se manifiesta la necesidad de expresar ideas sin restricciones en lugares comunes.     | EPIC-01            |
|   US03   | Socialización con nuevas personas    | Como persona con discapacidad auditiva, quiero poder conocer nuevas personas y socializar sin barreras, para desarrollar una vida social activa.      | Se evidencia el aislamiento social por falta de comunicación.                          | EPIC-01            |
|   US04   | Autonomía en trámites administrativos | Como persona con discapacidad auditiva, quiero tener más autonomía en trámites administrativos, para evitar depender de familiares o intérpretes.     | Se enfatiza la necesidad de independencia en gestiones formales.                       | EPIC-01            |
|   US05   | Comprensión por parte del entorno    | Como persona con discapacidad auditiva, quiero que las personas sin experiencia en lengua de señas puedan entenderme fácilmente, para evitar malentendidos. | Se refleja la necesidad de una comprensión generalizada en el entorno.             | EPIC-01            |
|   US06   | Comunicación en emergencias          | Como persona con discapacidad auditiva, quiero poder pedir ayuda en situaciones de emergencia, para sentirme seguro y protegido.                      | Se indica la importancia de la comunicación rápida en emergencias.                     | EPIC-02           |
|   US07   | Comunicación en centros de salud     | Como persona con discapacidad auditiva, necesito comunicar síntomas o dolencias en centros de salud, para recibir atención médica adecuada.           | Se identifica la barrera crítica en el acceso a servicios de salud.                    | EPIC-02           |
|   US08   | Participación en actividades recreativas | Como persona con discapacidad auditiva, deseo participar plenamente en actividades recreativas y culturales, para disfrutar de una vida plena.         | Se destaca la exclusión de actividades culturales y de ocio.                           | EPIC-02           |
|   US09   | Interacción en espacios educativos   | Como persona con discapacidad auditiva, deseo interactuar en espacios educativos donde no todos conocen lengua de señas.                             | Se muestra la desigualdad en contextos educativos comunes.                             | EPIC-03                     |
|   US10   | Comprensión rápida de estudiantes    | Como docente, quiero entender rápidamente lo que un estudiante con discapacidad auditiva necesita comunicar.                                          | Se visualiza la necesidad de respuesta inmediata ante la comunicación estudiantil.     | EPIC-03                     |
|   US11   | Participación en clases regulares    | Como profesor, deseo facilitar la participación de estudiantes con discapacidad auditiva.                                                             | Se muestra el desafío de integrar a estudiantes con discapacidades en clases comunes.  | EPIC-03                     |
|   US12   | Interacción entre estudiantes        | Como institución educativa, queremos mejorar la interacción entre estudiantes con y sin discapacidad auditiva.                                       | Se manifiesta la brecha en comunicación entre estudiantes diversos.                    | EPIC-03                     |
|   US13   | Prevención de frustraciones en clase | Como profesor, deseo recibir información inmediata sobre lo que intenta comunicar un estudiante.                                                      | Se identifica la necesidad de comprensión rápida en contextos educativos.              | EPIC-03                     |
|   US14   | Identificación de dudas en clase     | Como docente, quiero identificar rápidamente si un estudiante con discapacidad auditiva presenta dudas o dificultades.                               | Se refleja la necesidad de atención inmediata y adaptada.                              | EPIC-03                     |
|   US15   | Validación de aprendizaje            | Como profesor, quiero disponer de métodos para validar el contenido enseñado a estudiantes con discapacidad auditiva.                                | Se necesita retroalimentación efectiva en el proceso educativo.                        | EPIC-03                     |
|   US16   | Participación en reuniones laborales | Como persona con discapacidad auditiva, necesito participar activamente en reuniones laborales.                                                       | Se reconoce la falta de inclusión laboral por barreras comunicativas.                  | EPIC-04         |
|   US17   | Entrevistas laborales inclusivas     | Como organización inclusiva, quiero facilitar entrevistas laborales a personas con discapacidad auditiva.                                            | Se reconoce la importancia de inclusión desde el proceso de contratación.              | EPIC-04         |
|   US18   | Evaluación de habilidades comunicativas | Como centro de rehabilitación, necesitamos herramientas para evaluar habilidades comunicativas.                                                      | Se identifica la necesidad de monitoreo continuo y específico.                         | EPIC-05       |
|   US19   | Reducción de dependencia de intérpretes | Como institución, queremos reducir la dependencia de intérpretes externos.                                                                           | Se subraya la búsqueda de soluciones sostenibles e internas.                           | EPIC-05       |
|   US20   | Inclusión en eventos y talleres      | Como organización, necesitamos mejorar la comunicación en eventos con público diverso.                                                               | Se menciona la exclusión de usuarios en eventos masivos.                               | EPIC-05       |


### 3.3. Impact Mapping
### 3.4. Product Backlog
| # Orden | User Story Id | Título                                 | Descripción                                                                                                                                                                                                                             | Story Points |
|---------|----------------|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1       | US01           | Comunicación en conversaciones cotidianas | Como persona con discapacidad auditiva, quiero poder comunicarme fácilmente con personas que no conocen lengua de señas, para sentirme incluida en conversaciones cotidianas.                     | 3            |
| 2       | US02           | Expresión en entornos públicos         | Como persona con discapacidad del habla, quiero poder expresar mis ideas de forma clara en entornos públicos, para no sentirme ignorado o incomprendido.                                         | 3            |
| 3       | US06           | Comunicación en emergencias            | Como persona con discapacidad auditiva, quiero poder pedir ayuda en situaciones de emergencia, para sentirme seguro y protegido.                                                                  | 5            |
| 4       | US07           | Comunicación en centros de salud       | Como persona con discapacidad auditiva, necesito comunicar síntomas o dolencias en centros de salud, para recibir atención médica adecuada y oportuna.                                           | 5            |
| 5       | US10           | Comprensión rápida de estudiantes      | Como docente en una institución inclusiva, quiero entender rápidamente lo que un estudiante con discapacidad auditiva necesita comunicar, para apoyarlo en su aprendizaje.                        | 3            |
| 6       | US11           | Participación en clases regulares      | Como profesor, deseo facilitar la participación de estudiantes con discapacidad auditiva en clases regulares, para promover un entorno educativo inclusivo.                                       | 3            |
| 7       | US14           | Identificación de dudas en clase       | Como docente, quiero identificar rápidamente si un estudiante con discapacidad auditiva presenta dudas o dificultades, para poder apoyarlo de manera oportuna.                                   | 2            |
| 8       | US13           | Prevención de frustraciones en clase   | Como profesor de educación especial, deseo recibir información inmediata sobre lo que intenta comunicar un estudiante, para evitar frustraciones o malentendidos durante la clase.                | 2            |
| 9       | US03           | Socialización con nuevas personas      | Como persona con discapacidad auditiva, quiero poder conocer nuevas personas y socializar sin barreras, para desarrollar una vida social activa.                                                 | 3            |
| 10      | US04           | Autonomía en trámites administrativos  | Como persona con discapacidad auditiva, quiero tener más autonomía en trámites administrativos, para evitar depender de familiares o intérpretes.                                                | 3            |
| 11      | US18           | Evaluación de habilidades comunicativas| Como centro de rehabilitación, necesitamos herramientas que ayuden a evaluar las habilidades comunicativas de nuestros pacientes, para diseñar mejores programas de intervención.                 | 5            |
| 12      | US09           | Interacción en espacios educativos     | Como persona con discapacidad auditiva, deseo interactuar en espacios educativos donde no todos conocen lengua de señas, para acceder a las mismas oportunidades de aprendizaje.                  | 2            |
| 13      | US08           | Participación en actividades recreativas| Como persona con discapacidad auditiva, deseo participar plenamente en actividades recreativas y culturales, para disfrutar de una vida plena.                                                   | 2            |
| 14      | US05           | Comprensión por parte del entorno      | Como persona con discapacidad auditiva, quiero que las personas sin experiencia en lengua de señas puedan entenderme fácilmente, para evitar malentendidos en mi vida diaria.                     | 2            |
| 15      | US15           | Validación de aprendizaje              | Como profesor, quiero disponer de métodos para validar que el contenido enseñado ha sido entendido por estudiantes con discapacidad auditiva, para asegurar su aprendizaje.                        | 3            |
| 16      | US12           | Interacción entre estudiantes          | Como institución educativa, queremos mejorar la interacción entre estudiantes con y sin discapacidad auditiva, para fomentar la integración social en el aula.                                    | 2            |
| 17      | US16           | Participación en reuniones laborales   | Como persona con discapacidad auditiva, necesito participar activamente en reuniones laborales, para no perder oportunidades profesionales debido a la falta de comunicación.                     | 3            |
| 18      | US17           | Entrevistas laborales inclusivas       | Como organización inclusiva, quiero facilitar entrevistas laborales a personas con discapacidad auditiva, para promover la equidad en los procesos de selección.                                  | 3            |
| 19      | US19           | Reducción de dependencia de intérpretes| Como institución, queremos reducir la dependencia de intérpretes externos en actividades diarias, para hacer nuestros servicios más accesibles de manera autónoma.                               | 2            |
| 20      | US20           | Inclusión en eventos y talleres        | Como organización, necesitamos mejorar la comunicación en talleres, charlas y eventos con público diverso, para incluir activamente a personas con discapacidad auditiva.                          | 2            |

## Capítulo IV: Solution Software Design
### 4.1. Strategic-Level Domain-Diven Design

#### 4.1.1. Event Storming 

La herramienta Event Storming nos permite descubrir y describir el comportamiento del negoció evaluado, con la que se recopila información acerca de los procesos, actores y necesidades más importantes. Para realizar esta actividad se tuvo que realizar entrevistas a los sectores objetivo que nuestra aplicación atenderá, por lo cual es de suma importancia haber recopilado las necesidades expresadas por los usuarios. 

Se realizaron en total nueve pasos para elaborar correctamente el Event Storming, la cual se desarrolló con la herramienta LucidSpark: 

[Enlace al diagrama en LucidSpark](https://lucid.app/lucidspark/96218482-eb0b-4133-bbab-5d65836f3c77/edit?viewport_loc=-6667%2C-1729%2C21589%2C7733%2C0_0&invitationId=inv_5aa15ac8-83a1-4a10-a458-319a7ef0772a)

**Paso 1: Unstructured Exploration**

En este paso se insertaron en desorden los eventos del dominio que pueden suceder dentro de la aplicación, con el objetivo de delimitar luego estas ideas en estructuras más organizadas. 

![unstructured_exp.png](Assets/unstructured_exp.png)

**Paso 2: Timelines** 

En este paso se agruparon los eventos en subgrupos, los cuales tienen un evento principal como parte de su jerarquía. Se empieza a describir el flujo de eventos de las funcionalidades de la aplicación. 

![paso2.png](Assets/paso2.png)

**Paso 3: Pain Points**

Se identifican los puntos de los flujos de eventos en los que el usuario final pueda tener dificultad interactuando y se indaga el cómo se podría solucionar ese problema. 

![paso3.png](Assets/paso3.png) 

**Paso 4: Pivotal Points**

Se identificaron los eventos que son claves para el desarrollo del negocio para luego priorizarlas durante el desarrollo de la solución. 

![paso4.png](Assets/paso4.png)

**Paso 5: Commands** 

En este paso se identificaron los comandos o acciones que los actores del sistema (en este caso los usuario) pueden ejecutar. 

![paso5.png](Assets/paso5.png)

**Paso 6: Policies** 

Se identificaron las reglas de negocio con las que ciertos flujos de eventos deberán que cumplir obligatoriamente para funcionar acorde con lo esperado. 

![paso6.png](Assets/paso6_i.png)
![paso6.png](Assets/paso6_ii.png)

**Paso 7: Read Models** 

Se definen los Read Models o vistas del sistema con las que los usuarios interactuarán en la aplicación. 

![paso7.png](Assets/paso7_i.png)
![paso7.png](Assets/paso7_ii.png)

**Paso 8: External Systems** 

Se definen los servicios externos de los cuales varios eventos dependerán para su funcionalidad. 

![paso8.png](Assets/paso8_i.png)
![paso8.png](Assets/paso8_ii.png)

**Paso 9: Aggregates**

Al final, se identificaron agregados que agruparán a todos los comandos y eventos que restén relacionados. 

![paso9.png](Assets/paso9_i.png)
![paso9.png](Assets/paso9_ii.png)


##### 4.1.1.1. Candidate Context Discovery

En base del Event Storming anterior, se identificó 4 Boundend Context: 

* Authentication 
* Translation
* Learning 
* Record

**Bounded Context: Authentication**

![bc_auth.png](Assets/bc_auth.png)

**Bounded Context: Translation**

![bc_trans.png](Assets/bc_trans.png)

**Bounded Context: Learning**

![bc_learn.png](Assets/bc_learn.png)

**Bounded Context: Record**

![bc_rec.png](Assets/bc_rec.png)

**Vista general de los Bounded Contexts**

![bc_general.png](Assets/bc_general.png)


##### 4.1.1.2. Domain Message Flows Modeling

En esta sección se describe cómo los bounded context interactúan entre sí para resolver una necesidad del negocio. Se utilizó la técnica de Domain Storytelling para representar gráficamente la interacción entre bounded contexts entre los demás componentes y actores del sistema. 

**Escenario 1: Crear una cuenta**

![escenario1.png](Assets/dmfs1.png)

**Escenario 2: Iniciar Sesión** 

![escenario2.png](Assets/dmfs2.png)

**Escenario 3: Traducir Gestos**

![escenario3.png](Assets/dmfs3.png)

**Escenario 4: Traducir texto a gestos**

![escenario4.png](Assets/dmfs4.png)

**Escenario 5: Obtener material de aprendizaje**

![escenario5.png](Assets/dmfs5.png)

**Escenario 6: Consultar Historial de Traducciones**

![escenario6.png](Assets/dmfs6.png)

##### 4.1.1.3. Bounded Context Canvases

En este segmento se crearán los Bounded Context Canvases, los cuales detallan cómo estos funcionan dentro del proyecto, los elementos que interactúan con ellos y cómo interactúan entre sí. 


**Bounded Context Canvas: Authentication**

![bc_canvas_auth.png](Assets/bc_canvas_auth.png)

**Bounded Context Canvas: Translation**

![bc_canvas_trans.png](Assets/bc_canvas_trans.png)

**Bounded Context Canvas: Learning**

![bc_canvas_learn.png](Assets/bc_canvas_learn.png)

**Bounded Context Canvas: Record**

![bc_canvas_rec.png](Assets/bc_canvas_rec.png)

#### 4.1.2. Context Mapping
En esta sección, se analizan las relaciones entre los bounded contexts identificados en el sistema SmartSign y se asignan los patrones de context mapping adecuados para cada uno, asegurando una arquitectura bien delimitada, desacoplada y flexible frente a cambios tecnológicos o funcionales.
Customer/Supplier
Descripción: En esta relación, un contexto actúa como Cliente (Customer) y otro como Proveedor (Supplier). El contexto Cliente necesita servicios o datos del contexto Proveedor. Esta relación establece una dependencia directa donde el proveedor suministra información o servicios necesarios para el correcto funcionamiento del cliente.
Mobile App es Cliente de Wearable Context. El guante inteligente proporciona los datos sensoriales en tiempo real para su posterior procesamiento.


Mobile App es Cliente de Translation Context. Este último traduce los movimientos en lenguaje de señas a texto o audio.


Monitoring Context es Cliente de Translation Context, ya que se alimenta de los resultados traducidos para generar reportes y métricas de uso.



Open/Host Service (OHS)
Descripción: En este patrón, un contexto expone un servicio bien definido que otros contextos pueden consumir sin tener que interactuar con su lógica interna. Es ideal para servicios compartidos como autenticación, permisos o envío de notificaciones.
El contexto Authentication Context actúa como Host, ofreciendo servicios de autenticación y autorización para los usuarios del sistema.


El contexto Notification Context también actúa como Host, permitiendo que otros módulos generen retroalimentación auditiva o visual al usuario final.


Anticorruption Layer (ACL)
Descripción: Este patrón se utiliza cuando un contexto necesita proteger su propio modelo de dominio frente a la influencia de otro contexto externo. Se emplea una capa de traducción o adaptación para evitar un acoplamiento directo con la lógica del contexto externo.
Mobile App Context implementa un ACL para interactuar con el Wearable Context, aislando posibles cambios en el protocolo de comunicación del guante sin afectar su lógica interna.


Monitoring Context utiliza un ACL frente a los datos generados por el Translation Context, garantizando que su modelo de dominio estadístico se mantenga independiente de los cambios en el sistema de reconocimiento basado en IA.
![4 1 2 - Context Mapping](https://github.com/user-attachments/assets/ea447fdd-e654-44b8-9e9b-ef31ff12eb95)


#### 4.1.3. Software Achitecture

##### 4.1.3.1. Software Architecture System Landscape Diagram
En este nivel de diseño podemos ver el panorama general del sistema SmartSign y su relación con otros sistemas externos. Aquí podemos identificar la plataforma central (SmartSign) que traduce el lenguaje de señas a audio en tiempo real y está está conectada con sistemas externos que ayudan a la interacción de los usuarios. Tenemos los sistemas de servicio de Email y el sistema de servicio de plataforma cloud. Ambos trabajan de manera independiente, el primero envía notificaciones a usuarios y administradores. El último gestiona los modelos de aprendizaje y datos de configuración.
![img.png](Assets/landscape.png)
##### 4.1.3.2. Software Architecture Context Level Diagrams
Este diagrama descompone SmartSign en las partes técnicas principales que realizan diferentes procesos dentro de la solución. Primero, tenemos el dispositivo IoT (Guante Inteligente) que captura todos los movimientos de señas. Luego, encontramos la aplicación móvil que tiene una interfaz visual para los usuarios y administradores. Adicionalmente, tenemos el backend en donde tenemos el API Gateway que centraliza todas las solicitudes y servicios adicionales como autenticación, traducción (IA), monitoreo y notificaciones que ayudan a tener una mejor integración en todos los procesos. Finalmente, encontramos las bases de datos que almacenan la información de los usuarios y métricas.
![img.png](Assets/context.png)
##### 4.1.3.3. Software Architecture Container Level Diagrams
Este diagrama sirve para incrementar el sistema del software mostrando los contenedores (aplicaciones, microservicios, base de datos, entre otros) de los cuales está compuesto el sistema del software. Además, se puede visualizar todas las relaciones de las entidades externas con las entidades propias del software.
![img.png](Assets/container.png)

##### 4.1.3.4. Software Architecture Deployment Diagrams

En esta sección se definen los diagramas del despliegue de la aplicación, en los que se ilustra cómo las instancias de los sistemas de software (bases de datos, aplicaciones web y móviles, etc.) se desplegarán en entornos físicos y/o en la nube. 

![soft_deployment_diag.png](Assets/soft_deployment_diag.png)


### 4.2. Tactical-Level Domain-Driven Design (Cuatro Bounded Contexts) 

#### 4.2.1. Bounded Context: Authorization 
#### 4.2.1.1. Domain Layer.
Se identificó en la capa del dominio tres entidades/aggregates necesarias para el control de acceso a información confidencial y autenticación de los usuarios: User, Permission y Role. 

#### Aggregate User: 

| Nombre | Tipo | Propósito |
|-|-|-|
| User | Aggregate/Entity | Define los datos esenciales del usuario dentro de la plataforma | 

**Atributos de User:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del usuario dentro de la plataforma.  |
| name | String | Private | Nombre del usuario |
| lastName | String | Private | Apellido del usuario |
| email | String | Private | Correo electrónico del usuario| 
| password | String | Private | Contraseña del usuario |
| createdAt | LocalDateTime | Private | Fecha de creación del usuario |

**Métodos de User:** 

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|- |
| User | Void | Public | Constructor de la clase User.  |
| authenticateUser | Boolean | Public | Autentica al usuario utilizando su correo y contraseña |

#### Aggregate Permission: 

| Nombre | Tipo | Propósito |
|-|-|-|
| Permission | Aggregate/Entity | Define los permisos que puede tener un usuario dentro del sistema. |

**Atributos de Permission:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del permiso asignado.  |
| permissionName | String | Private | Nombre del permiso a asignar (ej. Ver Historial de Traducciones, Crear Nueva Traducción) |

**Métodos de Permission:**

 Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| Permission | Void | Public | Constructor de la clase Permission.  |
| definePermission | Void | Public | Define los permisos que se pueden otorgar a los usuarios. |

#### Aggregate Role: 

| Nombre | Tipo | Propósito |
|-|-|-|
| Role | Aggregate/Entity | Define los roles que los usuarios pueden tener dentro de la aplicación. |

**Atributos de Permission:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del rol asignado.  |
| roleName | String | Private | Nombre del rol del usuario a asignar (usuario común, administrador, etc.) |

**Métodos de Permission:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| Role | Void | Public | Constructor de la clase Role.  |
| defineRole | Void | Public | Se define el rol que toma un usuario en el sistema. |

##### 4.2.1.2. Interface Layer.

En la capa de interfaces se definen los controladores que se comunicarán con la interfaz de usuario con el objetivo de manejar los permisos y la autenticación del usuario. 

**Controller UserController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| UserController | Controller | Controlador de los métodos CRUD de la clase User. |

**Atributos de UserController:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| userService | UserService | Private | Servicio encargado de manejar la lógica de la autenticación.  |

**Métodos de UserController:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| authUser | ResponseEntity | Public | Método para autenticar al usuario (inicio de sesión) dentro de la aplicación.  |
| registerUser | ResponseEntity | Public | Método para la creación de un usuario en la aplicación. |
| getUser | ResponseEntity | Public | Método para obtener un usuario en específico según su id. |
| updateUser | ResponseEntity | Public | Método para modificar datos de un usuario en específico. |
| deleteUser | ResponseEntity | Public | Método para borrar un usuario del registro. |

**Controller PermissionController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| PermissionController | Controller | Controlador para el manejo de los permisos de usuario dentro de la aplicación. |

**Atributos de PermissionController:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| permissionService | PermissionService | Private | Servicio encargado de manejar la lógica del manejo de permisos.  |

**Métodos de PermissionController:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| assignPermissionToUser | ResponseEntity | Public | Método para asignar un permiso a un usuario en específico.  |
| removePermissionToUser | ResponseEntity | Public | Método para quitarle un permiso a un usuario en específico.  |
| getAllPermissions | ResponseEntity | Public | Método para obtener todos los permisos válidos en la aplicación. |

**Controller RoleController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| RoleController | Controller | Controlador para el manejo de los roles de usuario dentro de la aplicación. |

**Atributos de RoleController:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| roleService | RoleService | Private | Servicio encargado de manejar la lógica del manejo de roles.  |

**Métodos de RoleController:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| assignRoleToUser | ResponseEntity | Public | Método para asignar un rol a un usuario en específico.  |
| removeRoleToUser | ResponseEntity | Public | Método para quitarle un rol a un usuario en específico.  |
| getAllRoles | ResponseEntity | Public | Método para obtener todos los roles válidos en la aplicación. |

##### 4.2.1.3. Application Layer.

En la capa de aplicación se definirán las clases que manejarán los flujos de procesos de la funcionalidad de Autenticación. 

**Service UserService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| UserService | Service | Servicio para el manejo de la gestión de usuarios |

**Atributos de UserService:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| userRepository | UserRepository | Private | Repositorio encargado de las operaciones CRUD de los usuarios.  |

**Métodos de UserService:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| authUser | ResponseEntity | Public | Método para autenticar al usuario (inicio de sesión) dentro de la aplicación.  |
| registerUser | ResponseEntity | Public | Método para la creación de un usuario en la aplicación. |
| getUser | ResponseEntity | Public | Método para obtener un usuario en específico según su id. |
| updateUser | User | Public | Método para modificar datos de un usuario en específico. |
| deleteUser | ResponseEntity | Public | Método para borrar un usuario del registro. |

**Service PermissionService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| PermissionService | Service | Servicio para el manejo de los permisos de usuario dentro de la aplicación. |

**Atributos de PermissionService:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| permissionRepository | PermissionRepository | Private | Repositorio encargado de las operaciones CRUD de los permisos.  |

**Métodos de PermissionService:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| assignPermissionToUser | ResponseEntity | Public | Método para asignar un permiso a un usuario en específico.  |
| removePermissionToUser | ResponseEntity | Public | Método para quitarle un permiso a un usuario en específico.  |
| getAllPermissions | List | Public | Método para obtener todos los permisos válidos en la aplicación. |


**Service RoleService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| RoleService | Service | Servicio para el manejo de los roles de usuario dentro de la aplicación. |

**Atributos de RoleService:**

| Nombre | Tipo de dato | Visibilidad |  Propósito |
|-|-|-|-|
| roleRepository | RoleRepository | Private | Repositorio encargado de las operaciones CRUD de los roles.  |

**Métodos de RoleService:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| assignRoleToUser | ResponseEntity | Public | Método para asignar un rol a un usuario en específico.  |
| removeRoleToUser | ResponseEntity | Public | Método para quitarle un rol a un usuario en específico.  |
| getAllRoles | List | Public | Método para obtener todos los roles válidos en la aplicación. |

##### 4.2.1.4. Infrastructure Layer.

En la capa de infraestructura se manejarán las clases que accedan a servicios externos de la aplicación como la base de datos, con el objetivo de validad las credenciales y permisos del usuario. 

**Repository UserRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| UserRepository | Service | Repositorio que maneja la persistencia y recuperación de datos de la enitidad User de la base de datos.|

**Métodos de UserRepository:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| findById | Optional | Public | Método para encontrar a un usuario según su Id.  |
| existsById | Boolean | Public | Método para verificar la existencia de un usuario según su Id. |
| findByEmail | Optional | Public | Método para encontrar a un usuario según su correo  |
| existsByEmail | Boolean | Public | Método para verificar la existencia de un usuario según su correo.  |
| save | User | Public | Método para guardar los datos de un nuevo usuario. |
| deleteById | Void | Public | Método para borrar un usuario según su Id. |

**Repository PermissionRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| PermissionRepository | Repository | Repositorio que maneja la persistencia y recuperación de datos de la enitidad Permission de la base de datos. |

**Métodos de PermissionRepository:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| findByPermissionName | Optional | Public | Método para encontrar a un servicio según su nombre.  |
| existsByPermissionName | Boolean | Public | Método para verificar la existencia de un permiso según su Id. |
| findById | Optional | Public | Método para encontrar a un servicio según su Id.  |
| existsById | Boolean | Public | Método para verificar la existencia de un permiso según su Id. |
| save | Permission | Public | Método para guardar los datos de un nuevo permiso. |
| deleteById | Void | Public | Método para borrar un permiso según su Id. |


**Repository RoleRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| RoleRepository | Repository | Repositorio que maneja la persistencia y recuperación de datos de la enitidad Role de la base de datos. |

**Métodos de RoleRepository:**

| Nombre | Tipo de retorno | Visibilidad |  Propósito |
|-|-|-|-|
| findByRoleName | Optional | Public | Método para encontrar a un rol según su nombre.  |
| existsByRoleName | Boolean | Public | Método para verificar la existencia de un rol según su Id. |
| findById | Optional | Public | Método para encontrar a un rol según su Id.  |
| existsById | Boolean | Public | Método para verificar la existencia de un rol según su Id. |
| save | Role | Public | Método para guardar los datos de un nuevo rol. |
| deleteById | Void | Public | Método para borrar un rol según su Id. |

##### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.

![AuthBC_ComponentDiagram.png](Assets/AuthBC_ComponentDiagram.png)

##### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams.

![BCAuth_ClassDiagram.png](Assets/BCAuth_ClassDiagram.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram.

![AuthorizationBC_Database.png](Assets/AuthorizationBC_Database.png)

#### 4.2.2. Bounded Context: Learning 
##### 4.2.2.1. Domain Layer.

En la capa del dominio del bounded context Learning se ha identificado tres entidades/aggregates: Resource, Teacher y Course.

**Aggregate Resources**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del recurso. |
| title | String | Private | Título o nombre del recurso educativo. |
| description | String | Private | Breve descripción del contenido del recurso. |
| resourceType | String | Private | Tipo de recurso (video, documento, audio, etc.). |
| url | String | Private | Enlace al contenido del recurso. |

**Métodos de Resource:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| Resource | Void | Public | Constructor de la clase Resource. |
| updateResourceInfo | Void | Public | Permite actualizar los datos del recurso. |

**Aggregate Teacher**
|Nombre | Tipo | Propósito |
|-|-|-|
|Teacher | Aggregate/Entity | Representa a un docente o tutor encargado de impartir cursos de lengua de señas. |

**Atributos de Teacher:**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del docente. |
| name | String | Private | Nombre completo del docente. |
| email | String | Private | Correo electrónico del docente. |
| specialization | String | Private | Área de especialización o experiencia en lengua de señas. |

**Métodos de Teacher:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| Teacher | Void | Public | Constructor de la clase Teacher. |
| updateProfile | Void | Public | Permite actualizar el perfil del docente. |

**Aggregate Course**
| Nombre | Tipo | Propósito |
|-|-|-|
| Course | Aggregate/Entity | Representa un curso o programa de enseñanza de lengua de señas. |

**Atributos de Course:**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del curso. |
| courseName | String | Private | Nombre del curso. |
| description | String | Private | Breve resumen del contenido del curso. |
| teacherId | UUID | Private | ID del docente que dicta el curso. |

**Métodos de Course:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| Course | Void | Public | Constructor de la clase Course. |
| assignTeacher | Void | Public | Asigna un docente responsable al curso. |

##### 4.2.2.2. Interface Layer.

En la capa de interfaces se definen los controladores que se comunicarán con la interfaz de usuario para manejar cursos, docentes y recursos.

**Controller ResourceController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| ResourceController | Controller | Controlador para la gestión de recursos educativos. |

**Métodos de ResourceController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| createResource | ResponseEntity | Public | Crear un nuevo recurso educativo. |
| getResourceById | ResponseEntity | Public | Consultar un recurso por su ID. |
| updateResource | ResponseEntity | Public | Actualizar la información de un recurso. |
| deleteResource | ResponseEntity | Public | Eliminar un recurso existente. |

**Controller TeacherController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| TeacherController | Controller | Controlador para la gestión de docentes. |

**Métodos de TeacherController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| registerTeacher | ResponseEntity | Public | Registrar un nuevo docente. |
| getTeacherById | ResponseEntity | Public | Consultar un docente por su ID. |
| updateTeacherProfile | ResponseEntity | Public | Actualizar los datos de un docente. |
| deleteTeacher | ResponseEntity | Public | Eliminar un docente registrado. |

**Controller CourseController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| CourseController | Controller | Controlador para la gestión de cursos de lengua de señas. |

**Métodos de CourseController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| createCourse | ResponseEntity | Public | Crear un nuevo curso. |
| getCourseById | ResponseEntity | Public | Consultar un curso por su ID. |
| assignTeacherToCourse | ResponseEntity | Public | Asignar un docente a un curso. |
| deleteCourse | ResponseEntity | Public | Eliminar un curso existente. |

##### 4.2.2.3. Application Layer.

Se definen los servicios de aplicación que manejan la lógica de negocio.

**Service ResourceService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| ResourceService | Service | Servicio que gestiona los recursos educativos. |

**Service TeacherService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| TeacherService | Service | Servicio que gestiona el registro y administración de docentes. |

**Service CourseService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| CourseService | Service | Servicio que gestiona la creación y organización de cursos. |

##### 4.2.2.4. Infrastructure Layer.

Se definen los repositorios que permiten la persistencia de datos.

**Repository ResourceRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| ResourceRepository | Repository | Acceso a los datos de recursos educativos. |

**Repository TeacherRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| TeacherRepository | Repository | Acceso a los datos de docentes. |

**Repository CourseRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| CourseRepository | Repository | Acceso a los datos de cursos. |


##### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.
![learning 3 - 4 2 2 5](https://github.com/user-attachments/assets/b6237ab3-900c-4814-af99-41e7da0ec5d6)

##### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams.
##### 4.2.2.6.2. Bounded Context Database Design Diagram.

#### 4.2.3. Bounded Context: Translation
##### 4.2.3.1. Domain Layer.
##### Aggregate: TranslationRequest
| Nombre             | Tipo             | Propósito                                                                 |
|--------------------|------------------|---------------------------------------------------------------------------|
| TranslationRequest | Aggregate/Entity | Representa una solicitud de traducción de lenduaje de señas a texto/audio |

###### Atributos:

| Nombre              | Tipo de dato                   | Visibilidad  | Propósito                                                 |
|---------------------|--------------------------------|--------------|-----------------------------------------------------------|
| id                  | UUID                           | Private      | Identificador único de la solicitud de traducción         |
| userId              | UUID                           | Private      | Identificador único del usuario que realiza la solicitud  |
| inputType           | Enum(GESTURE,TEXT)             | Private      | Tipo de entrada de la solicitud (gesto o texto)           |
| inputData           | String                         | Private      | Datos de entrada(JSON de gestos o texto)                  |
| outputType          | Enum(TEXT,AUDIO)               | Private      | Tipo de salida de la solicitud (texto o audio)            |
| status              | Enum(PENDING,COMPLETED,FAILED) | Private      | Estado de la solicitud (pendiente, completada o fallida)  |
| createdAt           | LocalDateTime                  | Private      | Fecha de creación de la solicitud                         |
| completedAt         | LocalDateTime                  | Private      | Fecha de finalización de la solicitud                     |

###### Métodos:

| Nombre               | Tipo de retorno   | Visibilidad   | Propósito                                   |
|----------------------|-------------------|---------------|---------------------------------------------|
| TranslationRequest   | Void              | Public        | Constructor de la clase TranslationRequest  |
| startProcessing      | Void              | Public        | Marca el estado a PROCESSING                |
| completeTranslation  | Void              | Public        | Marca el estado a COMPLETED                 |
| failTranslation      | Void              | Public        | Marca el estado a FAILED                    |

##### Aggregate: TranslationResulT

| Nombre             | Tipo             | Propósito                                                                 |
|--------------------|------------------|---------------------------------------------------------------------------|
| TranslationResult | Aggregate/Entity | Representa el resultado de la traducción de lenduaje de señas a texto/audio |

###### Atributos:
| Nombre               | Tipo de dato                    | Visibilidad   | Propósito                                                  |
|----------------------|---------------------------------|---------------|------------------------------------------------------------|
| id                   | UUID                            | Private       | Identificador único del resultado de la traducción         |
| requestId            | UUID                            | Private       | Identificador único de la solicitud de traducción          |
| outputData           | String                          | Private       | Datos traducidos                                           |
| accuracyScore        | Float                           | Private       | Puntuación de precisión de la traducción (0-1)             |
| processingTimeMs     | Long                            | Private       | Tiempo de procesamiento de la traducción (en milisegundos) |

##### Value Object: GestureData

| Nombre             | Tipo             | Propósito                                 |
|--------------------|------------------|-------------------------------------------|
| GestureData       | Value Object      | Representa los datos de gestos capturados |

###### Atributos:

| Nombre         | Tipo de dato                  | Visibilidad  | Propósito            |
|----------------|-------------------------------|--------------|----------------------|
| handPosition   | String                        | Public       | Posición de la mano  |
| fingerAngles   | List<Float>                   | Public       | Ángulos de los dedos |
| movementVector | String                        | Public       | Vector de movimiento |

##### Domain Service: TranslationService
| Nombre             | Tipo           | Propósito                         |
|--------------------|----------------|-----------------------------------|
| TranslationService | Domain Service | Coordina el proceso de traducción |

###### Métodos:
| Nombre                  | Tipo de retorno    | Visibilidad    | Propósito                                   |
|-------------------------|--------------------|----------------|---------------------------------------------|
| translateGesture        | TranslationResult  | Public         | Traduce un gesto a texto/audio              |
| translateTextToGestures | TranslationResult  | Public         | Traduce un texto a representación de gestos |
| validateGesture         | Boolean            | Public         | Valida si los gestos son reconocibles       |

##### 4.2.3.2. Interface Layer.
###### Controller: TranslationController
| Nombre                | Tipo            | Propósito                                  |
|-----------------------|-----------------|--------------------------------------------|
| TranslationController | Controller      | Maneja las solicitudes HTTP de traducción  |

###### Atributos:
| Nombre                | Tipo de dato          | Visibilidad  | Propósito                                                 |
|-----------------------|-----------------------|--------------|-----------------------------------------------------------|
| translationAppService | TranslationAppService | Private      | Servicio encargado de la lógica de traducción             |

###### Métodos:
| Nombre                   | Tipo de retorno    | Visibilidad     | Propósito                              |
|--------------------------|--------------------|-----------------|----------------------------------------|
| translateGesture         | ResponseEntity     | Public          | Endpoint para traducir gestos          |
| translateText            | ResponseEntity     | Public          | Endpoint para traducir texto a gestos  |
| getTranslationStatus     | ResponseEntity     | Public          | Obteniene el estado de la traducción   |
| getTranslationResult     | ResponseEntity     | Public          | Obteniene el historial de traducciones |
##### 4.2.3.3. Application Layer.
###### App Service: TranslationAppService

| Nombre                | Tipo            | Propósito                                 |
|-----------------------|-----------------|-------------------------------------------|
| TranslationAppService | App Service     | Maneja la lógica de traducción            |

###### Atributos:
| Nombre                 | Tipo de dato           | Visibilidad   | Propósito                                                  |
|------------------------|------------------------|---------------|------------------------------------------------------------|
| translationRepository  | TranslationRepository  | Private       | Repositorio para acceder a los datos de traducción         |
| translationService     | TranslationService     | Private       | Servicio de dominio                                        |
| eventPublisher         | DomeinEventPublisher   | Private       | Publicador de eventos de dominio                           |

###### Métodos:
| Nombre                    | Tipo de retorno          | Visibilidad      | Propósito                                    |
|---------------------------|--------------------------|------------------|----------------------------------------------|
| processGestureTranslation | TranslationResult        | Public           | Procesa la traducción de un gesto            |
| processTextTranslation    | TranslationResult        | Public           | Procesa la traducción de un texto            |
| getTranslationStatus      | TranslationRequest       | Public           | Obtiene el estado de la traducción           |
| getTranslationHistory     | List<TranslationRequest> | Public           | Obtiene el historial de traducciones         |

###### Event Handlers:
| Nombre                           | Tipo         | Propósito                                     |
|----------------------------------|--------------|-----------------------------------------------|
| TranslationCompletedEventHandler | EventHandler | Maneja el evento de traducción completada     |
| TranslationFailedEventHandler    | EventHandler | Maneja el evento de traducción fallida        |

##### 4.2.3.4. Infrastructure Layer.

###### Repository: TranslationRepository
| Nombre                | Tipo            | Propósito                                |
|-----------------------|-----------------|------------------------------------------|
| TranslationRepository | Repository      | Persistencia de solicitudes y resultados |

###### Métodos:
| Nombre                    | Tipo de retorno              | Visibilidad     | Propósito                                    |
|---------------------------|------------------------------|-----------------|----------------------------------------------|
| saveRequest               | TranslationRequest           | Public          | Guarda una solicitud de traducción           |
| findRequestById           | Optional<TranslationRequest> | Public          | Encuentra una solicitud por su ID            |
| saveResult                | TranslationResult            | Public          | Guarda el resultado de la traducción         |
| findResulsByUserId        | List<TranslationResult>      | Public          | Encuentra resultados por ID de usuario       |
| findRecentRequests        | List<TranslationRequest>     | Public          | Encuentra solicitudes recientes              |

###### External Service: AIIntegrationService
| Nombre                | Tipo            | Propósito                                |
|-----------------------|-----------------|------------------------------------------|
| AIIntegrationService  | External Service| Interactúa con el servicio de IA         |

###### Métodos:
| Nombre                 | Tipo de retorno  | Visibilidad   | Propósito                                     |
|------------------------|------------------|---------------|-----------------------------------------------|
| sendForTranslation     | String           | Public        | Envía datos para traducción a IA              |
| getModelStatus         | String           | Public        | Obtiene el estado del modelo de IA             |

##### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.
![img.png](Assets/Translation_Bounded_Context.png)
##### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams.
![img.png](Assets/Translation_BC.png)
##### 4.2.3.6.2. Bounded Context Database Design Diagram.
![img.png](Assets/DB_translation.png)


#### 4.2.4. Bounded Context: Record

##### 4.2.4.1. Domain Layer

En la capa del dominio del bounded context Record se han identificado tres entidades/aggregates principales: **History**, **Search**, y **Visualization**.

**Aggregate History**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| id | UUID | Private | Identificador único del historial de traducciones. |
| userId | UUID | Private | Identificador del usuario dueño del historial. |
| translations | List<TranslationRecord> | Private | Lista de traducciones realizadas y almacenadas. |

**Métodos de History:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| History | Void | Public | Constructor de la clase History. |
| addTranslation | Void | Public | Agrega una nueva traducción al historial. |
| getTranslations | List | Public | Recupera todas las traducciones almacenadas. |

**Aggregate Search**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| searchId | UUID | Private | Identificador único de la búsqueda realizada. |
| userId | UUID | Private | Usuario que realiza la búsqueda. |
| keyword | String | Private | Palabra o gesto buscado. |
| searchDate | LocalDateTime | Private | Fecha y hora en que se realizó la búsqueda. |
| success | Boolean | Private | Resultado de la búsqueda (éxito/fallo). |

**Métodos de Search:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| Search | Void | Public | Constructor de la clase Search. |
| performSearch | List<TranslationRecord> | Public | Realiza una búsqueda en el historial del usuario. |

**Aggregate Visualization**

| Nombre | Tipo de dato | Visibilidad | Propósito |
|-|-|-|-|
| visualizationId | UUID | Private | Identificador único del gráfico generado. |
| userId | UUID | Private | Usuario que solicita la visualización. |
| topGestures | Map<String, Integer> | Private | Gráfico de los gestos más usados. |
| generationDate | LocalDateTime | Private | Fecha y hora de generación del reporte. |

**Métodos de Visualization:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| Visualization | Void | Public | Constructor de la clase Visualization. |
| generateReport | Map | Public | Genera un reporte con los gestos más frecuentes. |

##### 4.2.4.2. Interface Layer

**Controller HistoryController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| HistoryController | Controller | Gestiona el acceso al historial de traducciones del usuario. |

**Métodos de HistoryController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| viewTranslationHistory | ResponseEntity | Public | Mostrar el historial completo de traducciones. |
| registerTranslation | ResponseEntity | Public | Registrar una nueva traducción en el historial. |

**Controller SearchController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| SearchController | Controller | Gestiona la búsqueda de traducciones anteriores. |

**Métodos de SearchController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| searchInHistory | ResponseEntity | Public | Buscar palabras o gestos en el historial. |
| searchFailedAttempts | ResponseEntity | Public | Listar búsquedas sin resultados. |

**Controller VisualizationController:**

| Nombre | Tipo | Propósito |
|-|-|-|
| VisualizationController | Controller | Gestiona la generación de reportes de gestos más usados. |

**Métodos de VisualizationController:**

| Nombre | Tipo de retorno | Visibilidad | Propósito |
|-|-|-|-|
| generateUsageReport | ResponseEntity | Public | Mostrar gráficos de gestos más utilizados. |

##### 4.2.4.3. Application Layer

**Service HistoryService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| HistoryService | Service | Servicio para manejar registros de traducciones. |

**Service SearchService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| SearchService | Service | Servicio para búsquedas y consultas en historiales. |

**Service VisualizationService:**

| Nombre | Tipo | Propósito |
|-|-|-|
| VisualizationService | Service | Servicio para construir y mostrar reportes estadísticos del historial. |

##### 4.2.4.4. Infrastructure Layer

**Repository HistoryRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| HistoryRepository | Repository | Persistencia de los historiales de traducción de usuarios. |

**Repository SearchRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| SearchRepository | Repository | Persistencia de las búsquedas realizadas por los usuarios. |

**Repository VisualizationRepository:**

| Nombre | Tipo | Propósito |
|-|-|-|
| VisualizationRepository | Repository | Persistencia de los reportes de visualización generados. |

##### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección incluye diagramas de componentes del nivel de arquitectura de software, mostrando cómo cada contenedor está compuesto por diferentes componentes, sus responsabilidades y las interacciones entre ellos.
Estos diagramas ayudan a entender la estructura interna del sistema de gestión de historial de traducciones en SmartSign.
![image](https://github.com/user-attachments/assets/2a0853f4-85ae-40c7-a68d-9fd240cb86be)



##### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
En esta sección, se presentan los diagramas que detallan la implementación de los componentes dentro del Bounded Context Record.


##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
![image](https://github.com/user-attachments/assets/42577ea2-705f-49c6-8794-63b5883dc343)



##### 4.2.4.6.2. Bounded Context Database Design Diagram
El diagrama de base de datos define cómo se almacena la información del historial de traducciones y el uso de gestos.
![image](https://github.com/user-attachments/assets/a431fb95-2aa1-400f-b9af-9e0be91e7467)

# Conclusiones 

## Conclusiones TB1

* Durante el desarrollo del TB1 pudimos analizar e investigar acerca de cómo la solución que estamos proponiendo puede adecuarse a las demandas de nuestros usuarios objetivos. Además, hemos desarrollado las bases del diseño estructural de nuestra solución, las cuales nos van a servir cuando entremos a la fase de desarrollo.

# Bibliografía 

# Anexos
