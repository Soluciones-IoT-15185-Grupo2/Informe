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

| Alumno                         | Código     |
|--------------------------------|------------|
| Alvaro Esteban Crispin Ccancce | u202020328 |
| Jesús Andres Godoy Santillan   | u20251c350 |
| Jorge David Orrego Noriega     | u201921734 |
| Miguel Angel Huaman Cataño     | u202120615 |
|                                |            |

Abril, 2025

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|----------------------------|
|||||

# Project Report Collaboration Insights

**TB1:**

**Colocar al final capturas de los commits**

# Contenido

## Tabla de Contenidos

## [Capítulo I: Introducción](#capitulo-i-introduccion)
- [1.1. Startup Profile](#1.1-startup-profile)
    - [1.1.1. Descripción de la Startup]()
    - [1.1.2. Perfiles de integrantes del equipo]()
- [1.2. Solution Profile]()
    - [1.2.1. Antecedentes y problemática]()
    - [1.2.2. Lean UX Process]()
        - [1.2.2.1. Lean UX Problem Statements]()
        - [1.2.2.2. Lean UX Assumptions]()
        - [1.2.2.3. Lean UX Hypothesis Statements]()
        - [1.2.2.4. Lean UX Canvas]()
- [1.3. Segmentos objetivo]()
## [Capítulo II: Requirements Elicitation & Analysis]()
- [2.1. Competidores]()
    - [2.1.1. Análisis competivio]()
    - [2.1.2. Estrategias y tácticas frente a competidores]()
- [2.2. Entrevistas]()
    - [2.2.1. Diseño de entrevistas]()
    - [2.2.2. Registro de entrevistas]()
    - [2.2.3. Análisis de entrevistas]()
- [2.3. Needfinding]()
    - [2.3.1. User Personas]()
    - [2.3.2. User Task Matrix]()
    - [2.3.3. User Journey Mapping]()
    - [2.3.4. Empathy Mapping]()
    - [2.3.5. As-is Scenario Mapping]()
- [2.4. Ubiquitous Language]()

## [Capítulo III: Requirements Specification]()
- [3.1. To-Be Scenario Mapping]()
- [3.2. User Stories]()
- [3.3. Impact Mapping]()
- [3.4. Product Backlog]()

## [Capítulo IV: Solution Software Design]()
- [4.1. Strategic-Level Domain-Diven Design]()
    - [4.1.1. Event Storming]() 
        - [4.1.1.1. Candidate Context Discovery]()
        - [4.1.1.2. Domain Message Flows Modeling]()
        - [4.1.1.3. Bounded Context Canvases]()
    - [4.1.2. Context Mapping]()
    - [4.1.3. Software Achitecture]()
        - [4.1.3.1. Software Architecture System Landscape Diagram]()
        - [4.1.3.2. Software Architecture Context Level Diagrams]()
        - [4.1.3.3. Software Architecture Container Level Diagrams]()
        - [4.1.3.4. Software Architecture Deployment Diagrams]()


# Student Outcome

**Colocar la tabla del student outcome**

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

#### 4.1.3. Software Achitecture

4.1.3.1. Software Architecture System Landscape Diagram

4.1.3.2. Software Architecture Context Level Diagrams

4.1.3.3. Software Architecture Container Level Diagrams
        
4.1.3.4. Software Architecture Deployment Diagrams

En esta sección se definen los diagramas del despliegue de la aplicación, en los que se ilustra cómo las instancias de los sistemas de software (bases de datos, aplicaciones web y móviles, etc.) se desplegarán en entornos físicos y/o en la nube. 

![soft_deployment_diag.png](Assets/soft_deployment_diag.png)


# Conclusiones 

# Bibliografía 

# Anexos