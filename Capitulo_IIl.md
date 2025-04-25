Capítulo III: Requirements Specification
3.1. To-Be Scenario Mapping.
3.2. User Stories.

Epic
| Epic id | Título | Descripción |
|---------|--------|-------------|
| 1 | Estacionamiento de bicicletas | Como ciclista, deseo saber que estacionamiento están cercanos a mi ubicación, cuantos espacios disponibles hay, además de poder escribir una reseña sobre el estacionamiento para reducir mi tiempo de búsqueda de estacionamientos. |
| 2 | Foro | Como ciclista, deseo tener acceso a un foro para realizar diversas publicaciones y tener interacciones con otros ciclistas. |
| 3 | Acceso a tiendas | Como ciclista, deseo saber que tiendas tienen relación con las bicicletas para poder realizar las compras para mi bicicleta más rápido. |
| 4 | Búsqueda de rutas | Como ciclista, deseo buscar las rutas más seguras, tener diversos avisos sobre una ruta, además de poder calificar la ruta para ahorrar tiempo en mi búsqueda de rutas. |
| 5 | Landing page | Como ciclista, deseo que el landing page tenga secciones con información importante para conocer y entender la aplicación. |
| 6 | Validación de usuario | Como desarrollador, deseo que la aplicación valide a todos los usuarios que envíen sus datos en el inicio de sesión para que la aplicación sea segura para los usuarios. |

| Epic/Story ID | Título | Descripción | Criterios de aceptación | Relacionado con (Epic ID) |
|---------|---------------|--------|-------------|--------------------------|
| 1 | Estacionamiento cercanos | Como ciclista, deseo saber que estacionamientos estan cercanos a mi ubicación para ahorrar tiempo en mi busqueda de estacionamientos. | **Escenario: Ingresar a estacionamientos** Dado que el ciclista se encuentra en el inicio Cuando el ciclista selecciona el botón “Estacionamientos” Entonces el sistema muestra los estacionamientos disponibles **Escenario: Buscar estacionamientos cercanos** Dado que el ciclista se encuentra en “Estacionamientos” Cuando el ciclista selecciona el botón “Estacionamientos cercanos” Entonces el sistema muestra los estacionamientos más cercanos a la ubicación del ciclista | 1 |
| 2 | Espacios libres en estacionamientos | Como ciclista, deseo saber cuantos espacios disponibles hay en un estacionamiento para saber si podré estacionar mi bicicleta. | **Escenario: Cantidad de espacios disponibles** Dado que el ciclista se encuentra en “Estacionamientos” Cuando el ciclista selecciona un estacionamiento Entonces el sistema muestra la cantidad de espacios disponibles | 1 |
| 3 | Reseña sobre estacionamiento | Como ciclista, deseo hacer una reseña sobre un estacionamiento para poder compartir mi experiencia sobre un estacionamiento. | **Escenario: Escribir una reseña** Dado que el usuario ha seleccionado un estacionamiento Cuando el ciclista selecciona el botón “Reseña” Entonces el sistema permite que el ciclista pueda escribir y publicar una reseña sobre el estacionamiento | 1 |
| 4 | Acceso a foro | Como ciclista, deseo acceder a un foro para poder comunicarme con otros ciclistas. | **Escenario: Opción de foro** Dado que el ciclista se encuentra en el inicio Cuando el ciclista seleccione el botón “Foro” Entonces el sistema muestra las publicaciones del foro sobre ciclistas | 2 |
| 5 | Subir imágenes y videos al foro | Como ciclista, deseo subir imágenes y videos al foro para que mis publicaciones sean mejores. | **Escenario: Subir videos y fotos** Dado que el ciclista se encuentra en el “Foro” Cuando el ciclista selecciona “Subir publicación” Entonces el sistema permite agregar imágenes y videos a la publicación | 2 |
| 6 | Reportar a un usuario | Como ciclista, deseo reportar un usuario para que la aplicación tenga un buen ambiente para los ciclistas. | **Escenario: Reporte sobre un usuario** Dado que el ciclista se encuentra en el inicio Cuando el ciclista seleccione el icono de alerta Entonces el sistema permite que el ciclista pueda hacer un reporte sobre un usuario | 2 |
| 7 | Seguir a otro usuario | Como ciclista, deseo seguir a otro usuario en la aplicación para que sus publicaciones sean prioritarias cuando ingrese al foro. | **Escenario: Seguir a usuario** Dado que el ciclista se encuentra en el foro Cuando el ciclista haga click al nombre de un usuario Entonces el sistema le muestra la opción de seguir | 2 |
| 8 | Buscar tiendas relacionadas a las bicicletas | Como ciclista, deseo buscar tiendas relacionadas al ciclismo en la aplicación para poder realizar alguna compra para mi bicicleta. | **Escenario: Buscar tienda** Dado que el ciclista se encuentra en el inicio Cuando el ciclista seleccione el icono de una tienda Entonces el sistema le muestra las tiendas disponibles | 3 |
| 9 | Buscar rutas seguras | Como ciclista, deseo buscar rutas seguras para mantenerme a salvo. | **Escenario: Búsqueda de rutas seguras** Dado que el ciclista se encuentra en el inicio Cuando el ciclista seleccione el botón “Rutas” Entonces el sistema muestra todas las rutas seguras según la ubicación del ciclista | 4 |
| 10 | Aviso de inseguridad | Como ciclista, deseo recibir alertas sobre inseguridad sobre una ruta para poder tener más cuidado. | **Escenario: Alerta de inseguridad** Dado que el ciclista se encuentra en “Rutas” Cuando el ciclista seleccione una ruta Entonces el sistema le muestra un aviso de inseguridad en el caso que exista | 4 |
| 11 | Aviso de tráfico | Como ciclista, deseo recibir alertas de tráfico para tomar mis precauciones. | **Escenario: Alerta de tráfico** Dado que el ciclista se encuentra en “Rutas Cuando el ciclista seleccione una ruta Entonces el sistema le muestra un aviso de tráfico en el caso que exista | 4 |
| 12 | Calificar una ruta | Como ciclista, deseo calificar una ruta para que los demás ciclistas puedan tener conocimiento si una ruta es buena o mala. | **Escenario: Calificación a ruta** Dado que el ciclista se encuentra en “Rutas” Cuando el ciclista seleccione una ruta Entonces el sistema muestra la opción de calificar una ruta, el cual es de 1 a 5 estrellas | 4 |
| 13 | Información importante sobre la aplicación | Como ciclista, deseo que el landing page tenga secciones con información importante para mantenerme informado sobre la aplicación. | **Escenario: Acceso a información importante** Dado que el ciclista se encuentra en el landing page Cuando el ciclista selecciona alguna opción de las secciones del encabezado Entonces el sistema muestra la información de la sección que ha sido seleccionada | 5 |
| 14 | Contacto de información | Como ciclista, deseo que el landing page tenga contactos de información para poder contactarme rápidamente con servicio al cliente. | **Escenario: Acceso a contacto** Dado que el ciclista se encuentra en el landing page Cuando el ciclista seleccione la opción “Contacto” Entonces el sistema muestra los contactos disponibles para el servicio al cliente | 5 |
| 15 | Validación de usuario | Como desarrollador, deseo validar a los usuarios cuando envien su información en el inicio de sesión para que la aplicación sea segura y óptima. | **Escenario: Validar usuario** Dado que el ciclista se encuentra en el inicio de sesión Cuando el ciclista envia sus datos en el inicio de sesión Entonces el sistema valida si los datos del usuario son correctos o no | 6 |

3.3. Impact Mapping.

3.4. Product Backlog.
| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
|---------|---------------|--------|-------------|--------------------------|
| 1 | 1 | Estacionamiento cercanos | Como ciclista, deseo saber que estacionamientos estan cercanos a mi ubicación para ahorrar tiempo en mi busqueda de estacionamientos. | 5 |
| 2 | 2 | Espacios libres en estacionamientos | Como ciclista, deseo saber cuantos espacios disponibles hay en un estacionamiento para saber si podré estacionar mi bicicleta. | 3 |
| 3 | 3 | Reseña sobre estacionamiento | Como ciclista, deseo hacer una reseña sobre un estacionamiento para poder compartir mi experiencia sobre un estacionamiento. | 3 |
| 4 | 4 | Acceso a foro | Como ciclista, deseo acceder a un foro para poder comunicarme con otros ciclistas. | 8 |
| 5 | 5 | Subir imágenes y videos al foro | Como ciclista, deseo subir imágenes y videos al foro para que mis publicaciones sean mejores. | 3 |
| 6 | 6 | Reportar a un usuario | Como ciclista, deseo reportar un usuario para que la aplicación tenga un buen ambiente para los ciclistas. | 3 |
| 7 | 7 | Seguir a otro usuario | Como ciclista, deseo seguir a otro usuario en la aplicación para que sus publicaciones sean prioritarias cuando ingrese al foro. | 5 |
| 8 | 8 | Buscar tiendas relacionadas a las bicicletas | Como ciclista, deseo buscar tiendas relacionadas al ciclismo en la aplicación para poder realizar alguna compra para mi bicicleta. | 5 |
| 9 | 9 | Buscar rutas seguras | Como ciclista, deseo buscar rutas seguras para mantenerme a salvo. | 5 |
| 10 | 10 | Aviso de inseguridad | Como ciclista, deseo recibir alertas sobre inseguridad sobre una ruta para poder tener más cuidado. | 3 |
| 11 | 11 | Aviso de tráfico | Como ciclista, deseo recibir alertas de tráfico para tomar mis precauciones. | 3 |
| 12 | 12 | Calificar una ruta | Como ciclista, deseo calificar una ruta para que los demás ciclistas puedan tener conocimiento si una ruta es buena o mala. | 3 |
| 13 | 13 | Información importante sobre la aplicación | Como ciclista, deseo que el landing page tenga secciones con información importante para mantenerme informado sobre la aplicación. | 2 |
| 14 | 14 | Contacto de información | Como ciclista, deseo que el landing page tenga contactos de información para poder contactarme rápidamente con servicio al cliente. | 2 |
| 15 | 15 | Validación de usuario | Como desarrollador, deseo validar a los usuarios cuando envien su información en el inicio de sesión para que la aplicación sea segura y óptima. | 8 |
