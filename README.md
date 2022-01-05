# Botells - Sentimientos embotellados.
versión Alpha 0.0.1 MVP
## Proceso de diseño.
---
### Página web.
Para la página web de **Botells** se montará una única instancia de servidor en [Heroku](https://www.heroku.com) todo esto para optimizar recursos economicos y mantener el tiempo activo del servidor constantemente corriendo.
Se contará con una página web dedicada y desarrollada en [React.js](https://reactjs.org). Esta página contará con las opciones requerridas para que los usuarios entiendan el concepto que conlleva la aplicación, tanto como opciónes avanzadas para el control de su cuenta.

**Opciones de la página web:**
- [ ] **Registro de usuario:** Esta sección existe para que los usuarios puedan registrar sus cuentas desde la comodidad del sitio desarrollado para esta App. Cómo de momento la apliación se encuentra en estado de Alpha (MVP) los registros tendrán que ser aprobados previamente por un administrador (En este caso los principales desarrolladores del sistema) para que el usuario tenga acceso a una cuenta y por lo tanto a la aplicación.
- [ ] **Inicio de sesión:** El inicio de sesión dentro de la página web nos ayudará a que el usuario pueda tener un control sobre su cuenta, poder modificar su información personal, ya sea nombre de usuario, correo electronico principal y contraseña.
- [ ] **Nosotros:** Sección para explicar el contexto de la aplicación que estamos desarrollando, explicamos la misión y la visión, tanto del proyecto como de [INKODE](https://www.inkode.io/#) (Encargados del desarrollo de este y otros proyectos de software).
- [ ] **Ayuda:** En la sección de ayuda se le preguntará al usuario sobre el problema que esté experimentando, tomando las secciones sobre si es un problema con su aplicación o un bug dentro de ella, tambien se tomará en cuenta si es que tuvo un incidente con alguna respuesta dada dentro de la comunidad, tambien contará con un apartado de FAQ.
- [ ] **Donaciones:** En esta sección se le informa sobre el estado actual del desarrollo de la aplicación, que esta misma es creada por 3 personas unicamente. Por lo cual el mantenimiento de esta aplicación sin el apoyo de las donaciones es imposible.
---
## Desarrollo de la aplicación.
### Requerimentos.
- [ ] Los usuarios podrán registrarse siempre y cuando cuenten con un correo electrónico, nombre de usuario, contraseña de minimo 8 caracteres, con 1 mayuscula y 1 numero.
- [ ] Los usuarios podrán iniciar sesión mientras cuenten con el correo electronico y contraseña de una cuenta valida.
- [ ] Los usuarios deberán cumplir con un tutorial obligatorío. el cual cuenta con los siguientes pasos:
  - Una breve explicación del contexto de la aplicación.
  - Aceptar terminos, condiciones y reglamento de la aplicación.
  - Escribir una carta para los desarrolladores, donde les dé palabras de aliento en este nuevo proyecto
- [ ] Una vez terminado el tutorial recibirán 5 botellas, con estas botellas podrán escribir sus problemas y lanzarlos al mar para que otro usuario la reciba. Al redactar las cartas hay que tener en cuenta que se podrán tener multiples botellas en el "mar" a la vez, por lo cual el usuario tendrá que ponerles titulo (este titulo lo conocerá unicamente el usuario dueño de la carta).
- [ ] Los usuarios podrán contestar las cartas de otras personas y así recibir una botella, para esta sección los usuarios tendrán a la mano articulos de ayuda especializada en salud mental y consejos por parte de profesionales.
- [ ] Al tener una interacción con un usuario los mismos podrán reportar dicha interacción si estos creen que ha roto una regla o las normas de la comunidad, dicho reporte le llegará a los desarrolladores los cuales podrán tomar cartas sobre el asunto, y como recompenza se le otorgará una botella al usuario que haya realizado el reporte.
---
### Stack de desarrollo.
 - **Node.js + Express** como lenguaje principal de backend.
 - **Vue.js + Ionic** como frontend de la App movil.
 - **Firebase** como sistema de almacenamiento y base de datos.
 - **React.js** como frontend de la página web de información.
 - **Heroku** servirá de hosting para el backend y toda la lógica correspondiente.

### Plan para la Alpha
**Objetivos:**
- [ ] Página web.
- [ ] Escribir y recibir botellas, el manejo de la interaccion con el objeto botella, contando con un sistema de moderación por tiempo y prioridad en base al numero de respuestas.
- [ ] Redacción de la carta embotellada.
- [ ] Sistema de bonificaciones, botellas por ayudar a los demas.
- [ ] Tutorial, darle un consejo a los desarrolladores y unas palabras de animo. Para despues mandar su primer botella al mar.
- [ ] Sistema de moderación de lenguaje y reporte de usuarios (los reportes se revisaran manualmente).
- [ ] Reportes de bugs y errores.
- [ ] Validación de correos.
- [ ] Campaña publicitaria inicial.
- [ ] Apartado de comunidad.
- [ ] Notas del parche.
- [ ] Tips.
- [ ] Enlace a ayuda psicologica profesional.
- [ ] Notificaciones.

**Tiempos:**
- Diseño del mockup de la web: *14 hrs*. | *1 Semana*
- Diseño del mockup de la App: *14 hrs*. | *1 Semana*
- Página web desarrollo: *14 hrs*. | *1 Semana*
- Administración de usuarios: *14 hrs*. | *1 Semana*
- Apartado de administración (bugs, reportes): *10 hrs*. | *5 Días*
- Campaña publicitaria inicial: *60 hrs*. | *1 Mes*
- Api de los mensajes: *14 hrs*. | *1 Semana*
- Distribucion probabilistica de los mensajes: *36 hrs*. | *3 Semanas*
- Api de botellas: *14 hrs*. | *1 Semana*
- MVP de la App: *36 hrs*. | *3 Semanas*
- Api de notificaciones: *8 hrs*. | *4 días*
---
- **Semana 1:** Desarrollo del mockup para web y administración de usuarios.
- **Semana 2:** Desarrollo del mockup de la app y Desarrollo de la web.
- **Semana 3:** Administracion de la web.
- **Semana 4:** Api de los mensajes y distribución.
- **Semana 5:** Api de distribucion.
- **Semana 6:** Distribucion y botellas.
- **Semana 7:** MVP de la App.
- **Semana 8:** MVP de la app y notificaciones.
- **Semana 9:** MVP de la app y testing.
- **Semana 10:** Planeación de la Alpha (Usuarios y release).

### Plan para la Beta cerrada
### Plan para la Beta Abierta
### Plan para Producción