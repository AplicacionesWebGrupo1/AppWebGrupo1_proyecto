# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

Para el desarrollo de nuestro proyecto, el documento es gestionado través de GitHub, una plataforma que sirve como repositorio remoto y de control de versiones.  Hemos utilizado un flujo de trabajo basado en ramas para organizar el desarrollo donde dichas ramas permiten visualizar el proceso de documentación, corrección y producción de los ítems. Lo que asegura una integración ordenada y eficiente a lo largo del desarrollo del proyecto. Se ha hecho uso de mensajes commit en Git, las cuales nos permiten mantener un historial claro dentro de nuestro repositorio siguiendo un formato estandarizado. Además, empleamos GitHub Actions para la integración continua que automatiza pruebas y validaciones, garantizando que los cambios sean revisados y aprobados antes de su fusión mediante pull requests revisadas previamente por el equipo.

### 5.1.1. Software Development Environment Configuration
En esta sección, se definen las herramientas utilizadas en cada fase del desarrollo del software:

| Herramienta        | Propósito                                                                                                                  | Ruta de Descarga/Referencia                                                                  |
| ------------------ |-------------------------------------------------------------------------------------------------------------------------- |-------------------------------------------------------------------------------------------- |
| GitHub             | Control de versiones y colaboración en el código fuente del proyecto.                                                      | [Github](https://github.com/)                                                                |
| Visual Studio Code | Editor de código fuente y entorno de desarrollo que permite la codificación de archivos                                    | [Visual Studio Code](https://code.visualstudio.com/)                                         |
| HTML               | Lenguaje de Marcas de Hiperterxto utilizado en la elaboración de páginas web                                                 | [HTML](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/HTML_basics) |
| CSS                | Tecnología para dar estilo a las páginas web, permitiendo el diseño visual.                                                | [CSS](https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/What_is_CSS)               |
| TypeScript         | Lenguaje de programación orientado a objetos utilizado para implementar funcionalidades en la Landing Page.                | [TypeScript](https://www.typescriptlang.org/)                        |
| Figma              | Plataforma para el diseño de interfaces y elaboración de prototipos interactivos.                                          | [Figma](https://www.figma.com/es-la/downloads/)                                              |
| GitHub Pages       | Plataforma que facilita el despliegue sencillo de páginas web directamente desde repositorios de GitHub.                   | [GitHub Pages](https://pages.github.com/)                                                    |
| Markdown           | Lenguaje de marcado que permite la documentación técnica, utiliza un formato de texto sencillo fácil de convertir en HTML. | [Markdown Guide](https://www.markdownguide.org/) 


### 5.1.2. Source Code Management
| Nombre completo | Nombre de la cuenta|
| ------------------ |------------------------- |
| Integrante 1 | 
| Integrante 2 | x | 
| Integrante 2 | x |
| Integrante 4 | x |
| Integrante 5 | x |

capturas/imagenes de evidencia
Evidencia de la creacion del repositorio de trabajo. Enlace del repossitorio: 

Creacion de las ramas de trabajo (branchs):

Commits de evidencia del trabajo:

### 5.1.3. Source Code Style Guide & Conventions
El código seguirá las convenciones de BEM (Block Element Modifier) para la estructura de CSS, HTML y JavaScript. Se aplicarán las siguientes guías de estilo: 
- HTML: Basado en Google HTML/CSS Style Guide.
- CSS: Convención BEM para organización y nomenclatura.
- JavaScript: Se respetarán buenas prácticas recomendadas en el Google JavaScript Style Guide.
- Gherkin: Se adoptará un formato claro y legible, siguiendo Gherkin Conventions for Readable Specifications.

### 5.1.4. Software Deployment Configuration
Nuestro proyecto está alojado en un repositorio de GitHub y para el despliegue de nuestro landing page se a usado el GithubPages, ya que es una excelente manera de mostrar tu sitio web de forma gratuita y accesible en línea


Se a subido todos los archivos que conforman en landign Page, tanto como los archivos HTML, CSS y JS.


Y por ultimo se carga todo y se genera un enlace de pagina web donde esta se encuentra nuestro landing Page


## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1

Durante el Sprint 1, nuestro enfoque principal fue el desarrollo de la landing page para el proyecto. Este sprint marcó el inicio de la construcción de la interfaz inicial que los usuarios verán al acceder a la plataforma. Este esfuerzo fue crucial para establecer la estética y la estructura de nuestra página de inicio, asegurando que cumpliera con los requisitos de diseño moderno y funcionalidad necesarios para captar la atención de los usuarios y proporcionar una primera impresión efectiva.

#### 5.2.1.1. Sprint Planning 1

| **Sprint #**                        | 1                                                                                              |
|-----------------------------------|------------------------------------------------------------------------------------------------|
| **Date**                           |                                                                                    |
| **Time**                           | 11:00 AM                                                                                       |
| **Location**                       | Zoom Meetings                                                                                  |
| **Prepared By**                    |                                                                                   |
| **Attendees (to planning meeting)**| |

**Introducción:**

El equipo se reunió para planificar el Sprint 1 del proyecto Eventify, cuyo enfoque principal es la creación de la landing page. La planificación incluyó la definición de las User Stories y la asignación de Story Points para determinar la velocidad del equipo y asegurarse de que las tareas clave se completen dentro del tiempo estimado.

**Sprint Goal:**

Nuestro enfoque está en **diseñar e implementar la página de destino**. Creemos que ofrece **una interfaz de usuario funcional y visualmente atractiva** para **usuarios potenciales**. Esto se confirmará cuando **la página pase revisiones internas y cumpla con los requisitos de coherencia del diseño y elementos interactivos**.

**Sprint 1 Velocity:**  
El equipo ha acordado un total de **20 puntos** de velocidad para este sprint, basándose en la capacidad y disponibilidad de los miembros del equipo.

**Sum of Story Points:**  
El equipo ha asignado un total de **20 puntos** distribuidos en **6 User Stories**.

| **Sprint 1 – 1 Review Summary**        | Landing Page.                                                                                     |
|----------------------------------------|---------------------------------------------------------------------------------------------------|
| **Sprint 1 – 1 Retrospective Summary** | Basado en la retroalimentación del Sprint anterior, se identificaron áreas clave para mejorar la eficiencia del equipo y la calidad del producto. La revisión de la landing page reveló que, aunque se cumplieron los objetivos iniciales, hubo desafíos en la integración de elementos interactivos y en la consistencia del diseño visual. El equipo acordó que era crucial abordar estos problemas en el próximo sprint para asegurar una experiencia de usuario fluida. Además, se decidió implementar revisiones más frecuentes y establecer una documentación más clara del proceso para evitar malentendidos y mejorar la colaboración. La planificación del Sprint 1 se centra en aplicar estas lecciones aprendidas, optimizando el diseño y la funcionalidad de la landing page para cumplir con los estándares de calidad y las expectativas del Product Owner. |


#### 5.2.2.2. Sprint Backlog 1

**Objetivo del Sprint**
El objetivo principal de este sprint es completar la estructura y los elementos interactivos de la landing page, aplicando estilos visuales consistentes y asegurando la funcionalidad de los formularios y el carrusel de imágenes. Se busca que la página sea completamente operativa y esté lista para las pruebas finales de usabilidad y ajuste, basándose en el feedback recibido.

| **Sprint #** | **Sprint 1** |
|--------------|--------------|

| **User Story** | **Work-Item / Task** |
|--------------|--------------|

| **Id**        | **Title**                                | **Id**  | **Title**                     | **Description**                                                    | **Estimation (Hours)** | **Assigned To**                    | **Status** |
|--------------|------------------------------------------|---------|-------------------------------|--------------------------------------------------------------------|------------------------|-----------------------------------|------------|
| US001        | Definir estructura de la landing page     | T001    | Crear estructura HTML          | Implementar la estructura básica de la landing page en HTML.       | 4                      |         |       |
| US001        | Definir estructura de la landing page     | T002    | Estilizar con CSS              | Aplicar el diseño visual utilizando CSS, siguiendo los lineamientos del proyecto. | 6                      |          |       |
| US002        | Implementar elementos interactivos        | T003    | Configurar carrusel de imágenes | Desarrollar el componente de carrusel para mostrar imágenes en la landing page. | 5                      |        |        |
| US002        | Implementar elementos interactivos        | T004    | Crear formularios de contacto  | Crear y validar los formularios de contacto en la landing page.    | 3                      |         |       |
| US003        | Pruebas y ajustes finales                 | T005    | Realizar pruebas de funcionalidad | Ejecutar pruebas para asegurar que todos los elementos interactivos funcionen correctamente. | 2                      |         |        |
| US003        | Pruebas y ajustes finales                 | T006    | Ajustar según feedback         | Modificar elementos de diseño y funcionalidad basado en el feedback recibido. | 4                      |        |      |

#### 5.2.X.3. Development Evidence for Sprint Review
En esta seccion se busca detallar el proceso por la cual se trabajo el Sprint 1 indicando el repositorio en la cual se trabajo las ramas que se usaron dentro de dicho repositorio, el id con su mensaje y la fecha en la que se realizo de esta manera tener un registro del avance de los task planteados.

| Repository          | Branch            | Commit Id | Commit Message           | Commit Message Body            | Committed on (Date) |
|---------------------|-------------------|-----------|--------------------------|--------------------------------|---------------------|
|   |             | 6dfd1ead416b49e9fab0b7362219965534945ad4       | Update README.md          |  |          |
|   |             | 025d465422e53cb1222091ea25e39f4303273779       | Delete css directory      |  |          |
|   |            | 5bb2aa9b6f8310e7363b0b912cc2d07558470961       | Add files via upload      |  |         |
|   |            | ada6c0c2ad75e98ea1aef9cfcce1fdf820dc6d34       | Add files via upload      |  |         |
|   |             | b85cd8f99c7f2a4c1dd72afa9d18bb3c34f554f4       | Initial commit            |  |          |
|   | feature/responsive-design  | 7e4d9bc2f9a730e1548b1a72da3f048fc94372f1       | Add responsive design               |        |         |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Durante el desarrollo de este primer sprint no fueron realizados acceptance test. Esto debido a que, en el alcance de este entregable, recién fue implementada una primera versión de nuestra Landing Page.

#### 5.2.1.5. Execution Evidence for Sprint Review

Para este sprint, siendo el primero de nuestro proyecto, se pudo realizar una primera versión de nuestra Landing Page desplegada por medio de GitHub Pages. En esta se puede apreciar que están siendo aplicados todos los Style Guidelines establecidos para nuestro proyecto. A su vez, para este entregable, pudimos ofrecer una Landing Page que activamente le muestra al usuario lo que podrá realizar con nuestra aplicación al igual que múltiples call to action.

Las siguientes imágenes son algunas capturas de nuestra landing.
A continuación, por medio de este enlace, podrá visualizar una demostración del funcionamiento de nuestra landing page: 


#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Para esta primera entrega no fue requerido el uso de ningún servicio. Esto es, por el propio alcance de los objetivos propuestos para este primer sprint. Es por lo anterior mencionado, que no se agregó ninguna documentación respecto a web services empleados. 

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante este sprint, se realizó el despliegue inicial de la **Landing Page** del proyecto. Este proceso incluyó la configuración de recursos y la implementación de estrategias para garantizar un despliegue exitoso. A continuación, se detallan las actividades realizadas, los pasos seguidos y las herramientas utilizadas para completar el proceso de deployment.

#### Proceso de Deployment Realizado

1. **Creación y Configuración de Repositorio en GitHub:**
   - Se creó un repositorio dedicado para la **Landing Page** en GitHub.
   - Se configuraron las ramas necesarias para gestionar el flujo de trabajo y garantizar la estabilidad del código desplegado.

2. **Desarrollo de la Landing Page:**
   - **HTML:** Se utilizó para definir la estructura base de la landing page, incluyendo el header, footer, secciones de contenido y enlaces.
   - **CSS:** Se aplicaron estilos personalizados para alinear la apariencia de la página con la identidad visual de King Reserve, incorporando fuentes, colores y layout responsive.
   - **JavaScript:** Se implementaron interacciones dinámicas como formularios, botones y efectos visuales para mejorar la experiencia del usuario.

3. **Configuración de GitHub Pages:**
   - Se habilitó la funcionalidad de GitHub Pages desde la configuración del repositorio.
   - Se seleccionó la rama `main` como fuente de publicación para la landing page.
   - Se personalizó la URL del sitio publicado para facilitar su acceso y visibilidad.

4. **Automatización del Despliegue:**
   - Se configuró un flujo de trabajo de GitHub Actions para automatizar el despliegue. Esto incluye la ejecución de scripts de validación y la publicación automática de la landing page en cada actualización de la rama `main`.

5. **Pruebas Post-Despliegue:**
   - Validación visual y funcional de la landing page en diferentes navegadores y dispositivos.
   - Verificación de enlaces, formularios y elementos interactivos para asegurar su correcto funcionamiento.

### Evidencias del Proceso de Despliegue



#### 5.2.X.8. Team Collaboration Insights during Sprint
Durante este Sprint, el equipo ha colaborado en la creación de los productos planificados, centrándose en la **Landing Page**. A continuación, se ofrece un resumen sobre el desarrollo de las actividades que fueron divididas entre los integrantes del equipo.

### Actividades de Implementación

#### Diseño de la Estructura de la Landing Page
Durante la primera fase del sprint, el equipo colaboró en el diseño inicial de la estructura de la landing page. Esto incluyó la creación del wireframe y la definición de las secciones principales, como el encabezado, las secciones de características y el pie de página. Se discutieron diversas opciones y se seleccionó la más adecuada para garantizar una navegación intuitiva y atractiva. 

#### Desarrollo de la Interfaz y Estilos Visuales
Se trabajó en la implementación del diseño visual utilizando HTML y CSS. El equipo definió la paleta de colores y los estilos tipográficos siguiendo las directrices de la identidad de King Reserve. Se realizaron sesiones de trabajo conjuntas para ajustar detalles de la interfaz y asegurar la consistencia visual en todos los dispositivos. 

#### Implementación de Funcionalidades Dinámicas
En esta etapa, se integraron las funcionalidades dinámicas de la landing page utilizando JavaScript. Se añadieron animaciones y se mejoraron las interacciones con el usuario, como los botones de navegación y el formulario de contacto. El equipo trabajó en estrecha colaboración para probar y optimizar estas funcionalidades, asegurando una experiencia de usuario fluida y sin errores. 

#### Configuración y Automatización del Despliegue
Se configuró el entorno de despliegue utilizando GitHub Pages. El equipo estableció un flujo de trabajo automatizado con GitHub Actions para realizar pruebas y despliegues continuos cada vez que se actualizaba el repositorio. Esto facilitó la integración de cambios y permitió realizar despliegues rápidos y confiables. 

#### Pruebas de Calidad y Validación Final
Finalmente, se llevaron a cabo pruebas exhaustivas para garantizar la calidad del producto. Se realizaron pruebas en distintos navegadores y dispositivos para verificar la compatibilidad y el rendimiento. El equipo también recopiló retroalimentación de stakeholders y usuarios para hacer ajustes finales antes de la entrega del sprint. 

### Analíticos de Colaboración

A continuación, se presentan capturas de los informes de colaboración en GitHub, donde se puede observar la participación de cada integrante en cuanto a commits y contribuciones.

