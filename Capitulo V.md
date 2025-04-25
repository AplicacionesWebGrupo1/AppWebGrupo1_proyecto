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
| Integrante 1 | JuanqQuijano
| Integrante 2 | JhonHuam | 
| Integrante 2 | melinaasantillan |
| Integrante 4 | SantiIHC |

Evidencia de la creacion del repositorio de trabajo: 
![Captura de pantalla 2025-04-24 055040](https://github.com/user-attachments/assets/23776c45-e88a-4fe8-8391-72db89dd5f8b)

Creacion de las ramas de trabajo (branchs):
![brach](https://github.com/user-attachments/assets/05ed2b89-c25a-427c-9c40-46d9ce7399b3)

Commits de evidencia del trabajo: (PENDIENTE PARA EL FINAL)

Enlace del repositorio: https://github.com/AplicacionesWebGrupo1/AppWebGrupo1_proyecto

### 5.1.3. Source Code Style Guide & Conventions
El código seguirá las convenciones de BEM (Block Element Modifier) para la estructura de CSS, HTML y JavaScript. Se aplicarán las siguientes guías de estilo: 
- HTML: Basado en Google HTML/CSS Style Guide.
- CSS: Convención BEM para organización y nomenclatura.
- JavaScript: Se respetarán buenas prácticas recomendadas en el Google JavaScript Style Guide.
- Gherkin: Se adoptará un formato claro y legible, siguiendo Gherkin Conventions for Readable Specifications.

### 5.1.4. Software Deployment Configuration
Nuestro proyecto está alojado en un repositorio de GitHub y para el despliegue de nuestro landing page se a usado el GithubPages, ya que es una excelente manera de mostrar tu sitio web de forma gratuita y accesible en línea


Se a subido todos los archivos que conforman en landign Page, tanto como los archivos HTML, CSS y JS.
![fawef](https://github.com/user-attachments/assets/5ea86c54-6273-41eb-b910-3625c4b9c422)

Y por ultimo se carga todo y se genera un enlace de pagina web donde esta se encuentra nuestro landing Page: https://aplicacioneswebgrupo1.github.io/Landing-page-CicloVia/

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1

Durante el Sprint 1, nuestro enfoque principal fue el desarrollo de la landing page para el proyecto. Este sprint marcó el inicio de la construcción de la interfaz inicial que los usuarios verán al acceder a la plataforma. Este esfuerzo fue crucial para establecer la estética y la estructura de nuestra página de inicio, asegurando que cumpliera con los requisitos de diseño moderno y funcionalidad necesarios para captar la atención de los usuarios y proporcionar una primera impresión efectiva.

#### 5.2.1.1. Sprint Planning 1

| **Sprint #**                        | 1                                                                                              |
|-----------------------------------|------------------------------------------------------------------------------------------------|
| **Date**                           | 22/04/2025                                                                                   |
| **Time**                           | 11:30 AM                                                                                       |
| **Location**                       | Zoom Meetings                                                                                  |
| **Prepared By**                    | Juan Quijano                                                                                  |
| **Attendees (to planning meeting)**| Santiago Alonso, Jhon Huamani, Melina Santillan|

**Introducción:**

El equipo se reunió para planificar el Sprint 1 del proyecto, cuyo enfoque principal es la creación de la landing page. La planificación incluyó la definición de las User Stories y la asignación de Story Points para determinar la velocidad del equipo y asegurarse de que las tareas clave se completen dentro del tiempo estimado.

**Sprint Goal:**
Nuestro enfoque está en **diseñar e implementar la página de destino**. Creemos que ofrece **una interfaz de usuario funcional y visualmente atractiva** para **usuarios potenciales**. 

**Sprint 1 Velocity:**  
El equipo ha acordado un total de **27 puntos** de velocidad para este sprint, basándose en la capacidad y disponibilidad de los miembros del equipo.

**Sum of Story Points:**  
El equipo ha asignado un total de **27 puntos** distribuidos en **3 User Stories**.

| **Sprint 1 – 1 Review Summary**        | Landing Page.                                                                                     |
|----------------------------------------|---------------------------------------------------------------------------------------------------|
| **Sprint 1 – 1 Retrospective Summary** | Tras la culminacion de este sprint, se identificaron áreas clave para mejorar la eficiencia del equipo y la calidad del producto. La revisión de la landing page reveló que, aunque se cumplieron los objetivos iniciales, hubo desafíos en la integración de elementos interactivos y en la consistencia del diseño visual. El equipo acordó que era crucial abordar estos problemas en el próximo sprint para asegurar una experiencia de usuario fluida. Además, se decidió implementar revisiones más frecuentes y establecer una documentación más clara del proceso para evitar malentendidos y mejorar la colaboración. |


#### 5.2.2.2. Sprint Backlog 1

**Objetivo del Sprint**
El objetivo principal de este sprint es completar la estructura y los elementos interactivos de la landing page, aplicando estilos visuales consistentes y asegurando la funcionalidad de los formularios y el carrusel de imágenes. Se busca que la página sea completamente operativa y esté lista para las pruebas finales de usabilidad y ajuste, basándose en el feedback recibido.
Los elementos para este este sprint se organizaron en un tablero de trello: 

![Captura de pantalla 2025-04-25 024131](https://github.com/user-attachments/assets/835f2568-b1a9-4a41-b9e3-d4337c1128f7)
Enlace al tablero de trello: https://trello.com/b/iRvxX7bk/grupo-1-ciclovia

| **Sprint #** | **Sprint 1** |
|--------------|--------------|

| **User Story** | **Work-Item / Task** |
|--------------|--------------|

| **Id**        | **Title**                                | **Id**  | **Title**                     | **Description**                                                    | **Estimation (Hours)** | **Assigned To**                    | **Status** |
|--------------|------------------------------------------|---------|-------------------------------|--------------------------------------------------------------------|------------------------|-----------------------------------|------------|
| US001        | Como ciclista quiero una landing page clara y organizada para entender rápidamente la app     | T001    | Crear estructura HTML          | Implementar la estructura básica de la landing page en HTML      | 4                      | Santiago Gordillo        | Done      |
| US001        | Como ciclista quiero una landing page clara y organizada para entender rápidamente la app     | T002    | Estilizar con CSS              | Aplicar el diseño visual utilizando CSS, siguiendo los lineamientos del proyecto. | 6                      | Jhon Huamani          | Done     |
| US001        | Como ciclista quiero una landing page clara y organizada para entender rápidamente la app       | T003    | Configurar carrusel de imágenes | Incluir secciones informativas sobre la aplicación (uso, beneficios, etc.) | 5                      | Juan Quijano       | Done       |
| US001        | Como ciclista quiero una landing page clara y organizada para entender rápidamente la app        | T004    | Crear formularios de contacto  | Implementar sección de contacto con datos y formulario para soporte.    | 3                      | Melina Santillan        | Done      |
| US002        | Como ciclista quiero interactuar con elementos dinámicos para explorar de forma sencilla las funcionalidades de la aplicación                 | T005    | Configurar carrusel de imágenes | Ejecutar pruebas para asegurar que todos los elementos interactivos funcionen correctamente. | 2                      | Juan Quijano         | Done       |
| US002        | Como ciclista quiero interactuar con elementos dinámicos para explorar de forma sencilla las funcionalidades de la aplicación                 | T006    | Agregar animaciones al desplazarse         | Modificar elementos de diseño y funcionalidad basado en el feedback recibido. | 4                      | Santiago Gordillo       | Done     |
| US002        | Como ciclista quiero interactuar con elementos dinámicos para explorar de forma sencilla las funcionalidades de la aplicación                                          | T007            | implementación de botones dentro de la landing page                               | Se agregan los botones con las funcionalidades escenciales de la app                                                                        | 3                       | Jhon Huamani       |Done

#### 5.2.X.3. Development Evidence for Sprint Review
En esta seccion se busca detallar el proceso por la cual se trabajo el Sprint 1 indicando el repositorio en la cual se trabajo las ramas que se usaron dentro de dicho repositorio, el id con su mensaje y la fecha en la que se realizo de esta manera tener un registro del avance de los task planteados.

| Repository          | Branch            | Commit Id | Commit Message           | Commit Message Body            | Committed on (Date) |
|---------------------|-------------------|-----------|--------------------------|--------------------------------|---------------------|
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 095c8984d560b6c89642c83e6fa0aa174cd479c3      | Update styles.css       | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 5d9df57242224132e812e6d1d08ac9ff04444a1f      | Update styles.css       | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 50ea5bbbc28ddc5da6e4d9733d9de741da2284c8      | Update styles.css       | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 515954cabfa0b51af2711f0abbccf02df94ac5d6      | Update styles.css       | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/main.js    | 97254fa5eeddcd3edf48b9d46c1da7b777a51a96      | Update main.js          | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 10079f0bb29125287d2f032d1ea0b855486947af      | Add responsive design   | -- | 25/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 6b4e5c3c8c9f7200656f8833f63a0349d96b923e      | Add responsive design   | -- | 24/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/styles.css | 5fed89d466e536fe1a3269b6576d2d47c1d423b6      | Add responsive design   | -- | 24/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop/index.html | b3159128247b46f26ec225fc5bc39d128d491866      | Update index.html       | -- | 23/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | develop            | 88b6d6d75da22b1771d8b680253758cb5578f4ef      | Add files via upload    | -- | 23/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | main               | 298312a3c7a372ee2a7dc252817d8f7035d34533      | added develop           | -- | 23/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | readme             | e6be8918dfc08256936e9563665d49f44c940bd5      | Update readme           | -- | 23/04/2024  |
| https://github.com/AplicacionesWebGrupo1/Landing-page-CicloVia  | main               | cbbecf0db5b33c18c395ec0afbc752ae79526204      | Initial commit          | -- | 23/04/2024  |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Durante el desarrollo de este primer sprint no fueron realizados acceptance test. Esto debido a que, en el alcance de este entregable, recién fue implementada una primera versión de nuestra Landing Page.

#### 5.2.1.5. Execution Evidence for Sprint Review

Para este sprint, siendo el primero de nuestro proyecto, se pudo realizar una primera versión de nuestra Landing Page desplegada por medio de GitHub Pages. En esta se puede apreciar que están siendo aplicados todos los Style Guidelines establecidos para nuestro proyecto. A su vez, para este entregable, pudimos ofrecer una Landing Page que activamente le muestra al usuario lo que podrá realizar con nuestra aplicación al igual que múltiples call to action.

Las siguientes imágenes son algunas capturas de nuestra landing.
![ld1](https://github.com/user-attachments/assets/f5565ab7-c288-4bf3-a482-6b3dfa38977a)
![ld2](https://github.com/user-attachments/assets/e03ac446-72ea-480d-bf96-18e8a56de5c3)

A continuación, por medio de este enlace, podrá visualizar una demostración del funcionamiento de nuestra landing page: https://aplicacioneswebgrupo1.github.io/Landing-page-CicloVia/


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
Nos dirigimos a settings, pages
![1-deploy](https://github.com/user-attachments/assets/46d6df40-1907-40e3-b2c0-7cf621e86ff2)

En el apartado de branch seleccionamos la rama que contenga el codigo de nuestra landing page; en este caso "develop"
![2-deploy](https://github.com/user-attachments/assets/c585cf3c-8355-438f-bcee-d0edd4bd28f6)

Precionamos en "save". Hecho esto, tendremos que esperar unos minutos y tendremos el enlace de nuestra landing page desplegada.
![3-deploy](https://github.com/user-attachments/assets/b15e440e-78d2-4f04-84f1-effd7682b7bb)


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
![Captura de pantalla 2025-04-25 033224](https://github.com/user-attachments/assets/cc0fe148-1001-410e-b0bf-1c13e1b7d40e)


