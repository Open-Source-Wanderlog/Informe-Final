# INFORME DEL TRABAJO FINAL

![alt text](assets/imgs/upc.png)

### UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

### INGENIERÍA DE SISTEMAS DE INFORMACIÓN Y SOFTWARE

### CICLO 2024-01

Nombre del curso: Desarrollo de Aplicaciones Open Source <br>
 Sección: WX56 <br>
 Nombre del Profesor: Mori Paiva, Hugo Allan  <br>
 Nombre del StartUp: WanderLog <br>
 Nombre del Producto: WanderLog <br>
Relación de Integrantes:

- Cortés Casas, Joaquin Marcelo - U202114545
- Diaz Silva, Fernando Josué - U202112722
- Castilla Pachas Cesar Antonio - U202218735
- Medina Chocce Karito Dianeth - U20221C769

## Historial de Versiones

<table>
<tr>
    <th colspan="3">Version</th>
    <th colspan="3">Fecha</th>
    <th colspan="10">Autores</td>
    <th colspan="5">Descripción de Modificaciones</td>
  <tr>
    <td colspan="3">TB1</td>
    <td colspan="3">04/04/2024</td>
    <td colspan="10">Cortés Casas Joaquin Marcelo, Diaz Silva Fernando Josué, Cesar Castilla Pachas, Medina Chocce Karito Dianeth.</td>
    <td colspan="5">Documentación de los capítulos I-V.
Implementación y despliegue de la primera versión del Landing Page.
</td>
  </tr>
  </table>


# Índice

- [Capítulo I: Introducción]()
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de Integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hyphotesis Statements](#1223-lean-ux-hyphotesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis]()
  - [2.1. Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Persona](#231-user-persona)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
- [Capítulo III: Requirements Specification]()
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design]()
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment]()
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome

| Criterio Específico   | Acciones Realizadas  | Conclusiones   |
| ----------------------| ---------------------|----------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | **Cortés Casas, Joaquín Marcelo**<br>TB1:Ha participado en la investigación de los principales competidores, además del desarrollo de los diagramas C4 y  de base de datos.<br>**Díaz Silva, Fernando Josué**<br>TB1: He desarrollado el capítulo 3, Requirements Specification y la documentación del landing page del capítulo 4.<br>**Castilla Pachas Cesar Antonio**<br>TB1: He participado en la implementación del capitulo I, Implementación delLanding Page y Web applications <br>**Medina Chocce Karito Dianeth**<br>TB1: He participado haciendo el capítulo 2 y la parte del 4.7. | Nos aseguramos de trabajar de forma coordinada y eficaz, avanzando lo más posible en una cantidad de tiempo límite. Para lograrlo, tuvimos que trabajar como equipo y discutir las decisiones importantes de manera organizada y objetiva.
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.                                                             | **Cortés Casas, Joaquín Marcelo**<br>TB1:Ha participado en la investigación de los principales competidores, además del desarrollo de los diagramas C4 y  de base de datos.<br>**Díaz Silva, Fernando Josué**<br>TB1: He desarrollado el capítulo 3, Requirements Specification y la documentación del landing page del capítulo 4.<br>**Castilla Pachas Cesar Antonio**<br>TB1: He participado en la implementación del capitulo I, Implementación delLanding Page y Web applications <br>**Medina Chocce Karito Dianeth**<br>TB1: He participado haciendo el capítulo 2 y la parte del 4.7.  |                                                                                                                                                                                                                                            |





# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
Aquí tienes una versión ampliada y detallada de la sección 5.1.1. Software Development Environment Configuration de tu proyecto:

### 5.1.1. Software Development Environment Configuration
En la siguiente sección se describe la ruta de referencia de cada uno de los productos de software que utilizaremos en el proyecto, de modo que cualquier miembro del equipo pueda desarrollar cada punto del trabajo de manera eficiente y coherente.

**UXPressia**
UXPressia es una plataforma en línea que nos permitirá crear user stories y realizar múltiples mapas para evaluar sus prioridades. Ofrece herramientas gráficas avanzadas que mejoran el aspecto visual de nuestro trabajo, facilitando la comprensión y comunicación de las historias de usuario y otros elementos clave del diseño de UX.

Se puede acceder a la plataforma en el siguiente enlace: https://uxpressia.com 

**Figma**
Es una herramienta colaborativa de diseño que permite a nuestro equipo desarrollar wireframes y mockups de nuestra Landing Page en tiempo real. Figma facilita la colaboración entre diseñadores y desarrolladores al permitir comentarios y ediciones simultáneas, asegurando que todos los miembros del equipo estén en la misma página durante el proceso de diseño.

Se puede acceder a la plataforma en el siguiente enlace: https://figma.com 

**Vertabelo**
Es una plataforma de modelado de bases de datos que nos permitirá diseñar y visualizar nuestro Diagrama de Base de Datos. La herramienta proporciona una interfaz intuitiva para crear y modificar esquemas de bases de datos, lo cual es esencial para el desarrollo estructurado y eficiente de nuestro sistema de gestión de datos.

Se puede acceder a la plataforma en el siguiente enlace: https://vertabelo.com

**LucidChart**
Es una aplicación web destinada a la creación de diagramas y gráficos de flujo, incluyendo wireflows, Lean UX Canvas, User Flows y diagramas de clases. Esta herramienta facilita la visualización de procesos y estructuras complejas, mejorando la planificación y comunicación dentro del equipo.

Se puede acceder a la plataforma en el siguiente enlace: https://lucidchart.com

**GitHub**
Es un repositorio colaborativo en la nube utilizado para almacenar y gestionar el código fuente de nuestro proyecto. Permite el control de versiones, facilitando la colaboración entre los desarrolladores y asegurando que todos los cambios se registren y puedan ser revertidos si es necesario.

Se puede acceder a la plataforma en el siguiente enlace: https://github.com

**Visual Studio Code**
Es un entorno de desarrollo integrado (IDE) utilizado por nuestro equipo para la programación y desarrollo del proyecto. VS Code soporta una amplia gama de extensiones y configuraciones que mejoran la productividad, incluyendo depuración, control de versiones integrado y múltiples lenguajes de programación.

Se puede acceder a la plataforma en el siguiente enlace: https://code.visualstudio.com 

**GitHub Pages**
Es una plataforma que permite realizar despliegues (deployments) sencillos y rápidos para nuestras páginas web directamente desde un repositorio de GitHub. Es ideal para alojar proyectos de sitios web estáticos y proporciona una forma eficiente de compartir nuestro progreso y versiones finales con los interesados.

Se puede acceder a la plataforma en el siguiente enlace: https://pages.github.com 

**HTML5**
Es un lenguaje de marcado utilizado para la estructura y contenido de nuestra página web. Ofrece nuevas funcionalidades y mejoras respecto a versiones anteriores de HTML, facilitando la creación de sitios web modernos y responsivos.

**CSS3**
Es la tecnología que utilizamos para aplicar estilos y diseño a nuestra página web. Proporciona una amplia gama de propiedades de estilo, animaciones y efectos, permitiendo un diseño visual atractivo y coherente con la identidad de nuestro proyecto.

<br><br>

Con esta información, cualquier miembro de nuestro equipo podrá familiarizarse rápidamente con las herramientas y plataformas utilizadas en el proyecto facilitando la colaboración y el desarrollo eficiente.

### 5.1.2. Source Code Management
El manejo del código fuente es crucial para el éxito del proyecto. Utilizamos Git como sistema de control de versiones y GitHub como plataforma para alojar nuestros repositorios. A continuación, se detalla el flujo de trabajo y las prácticas que seguimos:

- Organización del equipo: https://github.com/Open-Source-Wanderlog 
- Repositorio landing page:https://github.com/Open-Source-Wanderlog/landing-page 
- Despliegue de landing page en Netlify: https://graceful-mousse-7d861d.netlify.app 

### 5.1.3. Source Code Style Guide & Conventions

**HTML Style Guide and Coding Conventions**
Es necesario seguir convenciones estandarizadas de HTML como estructura de la web. Entre las principales de W3 Schools (https://www.w3schools.com/html/html5_syntax.asp) podemos mencionar:

- Siempre declarar el tipo de documento con <!DOCTYPE html>
- Usar siempre letras en minúsculas para los nombres de los elementos (como <p>, <h1>, <section>, entre otros).
- Cerrar siempre con los elementos de HTML (por ejemplo <p></p>)
- Siempre poner entre comillas los atributos dentro de un elemento html ( <p class=”name”></p>)
- Especificar alt, width, and height para imágenes.
- Espaciado y signo igual estandarizados.
- Evitar líneas de código extensas.
- No olvidar el “<title></title>” al principio.
- Es posible evitar el “<head></head>”.
- Utilizar meta tags al inicio.

**Google HTML/CSS Style Guide**
Algunas de las convenciones de Google en cuanto a HTML y CSS (https://google.github.io/styleguide/htmlcssguide.html) podemos mencionar:

- Usar la sintaxis y semántica de HTML5.
- Usar minúsculas para los nombres de elementos y atributos.
- Usar comillas dobles para los valores de atributos.
- Usar una nueva línea para cada elemento.
- Usar un espacio después de los dos puntos del nombre de cada propiedad.
- Usar códigos de color hexadecimal (#000000) en vez de nombres propios.
- Usar códigos de color hexadecimales abreviados siempre que sea posible.
- Evitar especificar unidades para valores 0. Por ejemplo, margin: 0px se incluye la unidad de pixeles.

**JavaScript:**

- Usamos ESLint para asegurar un código limpio y sin errores comunes.
- Adherimos a la guía de estilo de Airbnb para JavaScript.
- Usamos Prettier para formatear el código automáticamente.

### 5.1.4. Software Deployment Configuration
Se utilizará GitHub

<img src="assets/img/img-softwareDeplymentConfig.png"  alt=" "></img>

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
<img src="assets/img/sprint1.png" alt=""></img>

#### 5.2.1.2. Sprint Backlog 1

<img src="assets/img/sprintBacklog1.1.png" alt=""></img>
<img src="assets/img/sprintBacklog1.2.png" alt=""></img>
<img src="assets/img/sprintBacklog1.3.png" alt=""></img>
<img src="assets/img/sprintBacklog1.4.png" alt=""></img>
<img src="assets/img/sprintBacklog1.5.png" alt=""></img>

#### 5.2.1.3. Development Evidence for Sprint Review

<img src="assets/img/evidenceSprint1.1.png" alt=""></img>
<img src="assets/img/evidenceSprint1.2.png" alt=""></img>

#### 5.2.1.4. Testing Suite Evidence for Sprint Review
En el alcance del sprint 1, no se realizaron testing de la aplicación al haber solo trabajado en el landing page.

#### 5.2.1.5. Execution Evidence for Sprint Review

<img src="assets/img/executionSprint1.1.png" alt=""></img>
<img src="assets/img/executionSprint1.2.png" alt=""></img>
<img src="assets/img/executionSprint1.3.png" alt=""></img>
<img src="assets/img/executionSprint1.4.png" alt=""></img>


#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
<img src="assets/img/evidenceDeploymentSprint1.1.png" alt=""></img>

#### 5.2.1.8. Team Collaboration Insights during Sprint 
A continuación se presentan capturas de los insights del repositorio del landing page en Github:

<img src="assets/img/networkGraphSprint1.png" alt=""></img>

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2
<img src="assets/img/sprint2.png" alt=""></img>

#### 5.2.2.2. Sprint Backlog 2

<img src="assets/img/sprintBacklog2.1.png" alt=""></img>
<img src="assets/img/sprintBacklog2.2.png" alt=""></img>

#### 5.2.2.3. Development Evidence for Sprint Review

<img src="assets/img/evidenceSprint2.1.png" alt=""></img>

#### 5.2.2.4. Testing Suite Evidence for Sprint Review
En el alcance del sprint 2, no se realizaron testing de la aplicación al haber solo trabajado en el landing page.

#### 5.2.2.5. Execution Evidence for Sprint Review

<img src="assets/img/executionSprint2.1.png" alt=""></img>
<img src="assets/img/executionSprint2.2.png" alt=""></img>
<img src="assets/img/executionSprint2.3.png" alt=""></img>
<img src="assets/img/executionSprint2.4.png" alt=""></img>


#### 5.2.2.6. Services Documentation Evidence for Sprint Review

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
<img src="assets/img/evidenceDeploymentSprint2.1.png" alt=""></img>

#### 5.2.2.8. Team Collaboration Insights during Sprint 
A continuación se presentan capturas de los insights del repositorio del landing page en Github:

<img src="assets/img/networkGraphSprint2.png" alt=""></img>


### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3
<img src="assets/img/sprint3.png" alt=""></img>

#### 5.2.3.2. Sprint Backlog 3

<img src="assets/img/sprintBacklog3.1.png" alt=""></img>
<img src="assets/img/sprintBacklog3.2.png" alt=""></img>

#### 5.2.3.3. Development Evidence for Sprint Review

<img src="assets/img/evidenceSprint3.1.png" alt=""></img>
<img src="assets/img/evidenceSprint3.2.png" alt=""></img>

#### 5.2.3.4. Testing Suite Evidence for Sprint Review
En el alcance del sprint 3, se realizaron testing del backend.

<img src="assets/img/executionSprint3.1.png" alt=""></img>
<img src="assets/img/executionSprint3.2.png" alt=""></img>
<img src="assets/img/executionSprint3.3.png" alt=""></img>
<img src="assets/img/executionSprint3.4.png" alt=""></img>


#### 5.2.3.5. Execution Evidence for Sprint Review

<img src="assets/img/executionSprint2.1.png" alt=""></img>
<img src="assets/img/executionSprint2.2.png" alt=""></img>
<img src="assets/img/executionSprint2.3.png" alt=""></img>
<img src="assets/img/executionSprint2.4.png" alt=""></img>
<img src="assets/img/executionSprint3.1.png" alt=""></img>
<img src="assets/img/executionSprint3.2.png" alt=""></img>
<img src="assets/img/executionSprint3.3.png" alt=""></img>
<img src="assets/img/executionSprint3.4.png" alt=""></img>


#### 5.2.3.6. Services Documentation Evidence for Sprint Review

#### 5.2.3.7. Software Deployment Evidence for Sprint Review
<img src="assets/img/evidenceDeploymentSprint3.1.png" alt=""></img>

#### 5.2.3.8. Team Collaboration Insights during Sprint 
A continuación se presentan capturas de los insights del repositorio del landing page en Github:

<img src="assets/img/networkGraphSprint3.1.png" alt=""></img>
<img src="assets/img/networkGraphSprint3.2.png" alt=""></img>
<img src="assets/img/networkGraphSprint3.3.png" alt=""></img>
