# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
Luego de realizar el ai-is con sus fases propuestas, para el to-be se realizaron nuevos procesos enfocados en mejorar las fases de los segmentos objetivos con nuestro proyecto.
**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories

Los User Stories sirven para describir de manera más detallada las diferentes funciones de la aplicación, adaptándolas a las necesidades y prioridades de los usuarios. Estas historias también capturan el propósito de uso de las personas, brindando una comprensión más completa de cómo se relacionan con la aplicación y qué esperan lograr con ella.

<table>
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Funciones de Usuario</td>
        <td>Como médico, deseo tener funciones y opciones relacionadas a mi usuario para manejar mis datos y acciones en la cuenta.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Visualizacion de Apartados</td>
        <td>Como médico, deseo tener opciones de detalles y búsqueda para visualizar los datos que me interesan en la plataforma.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Landing Page</td>
        <td>Como médico, deseo visitar una Landing Page para informarme sobre MedicDefense y lo que ofrece.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Interacción con Abogado</td>
        <td>Como médico, deseo tener funciones y opciones relacionadas al abogado para tratar con él u opinar de sus servicios.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>HU01</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero poder eliminar mi cuenta para no tener vinculo con el sitio web.</td>
        <td>Scenario: El Usuario elimina una cuenta<br><br>GIVEN el Cliente quiere eliminar su cuenta del sitio web<br><br>WHEN complete las verificaciones para ver que sea el usuario de la cuenta,<br><br>AND presione el botón "eliminar cuenta" del apartado de configuración,<br><br>THEN se eliminara su cuenta exitosamente.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU02</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como visitante de la landing page de MedicDefense, quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>Scenario: El Usuario quiere visualizar tipos de suscripciones<br><br>GIVEN el Cliente quiere visualizar los tipos de suscripciones enl sitio web<br><br>WHEN tiene curiosidad sobre los precios de las suscripciones para usar el sitio web,<br><br>AND complete las acciones para dirigirse al apartado,<br><br>THEN irá al apartado "suscripciones" dentro del sitio web y podrá ver las promociones que tiene el sitio web.</td>
        <td>EP03</td>
    </tr>
    <tr>
        <td>HU03</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>Scenario: El Cliente quiere visualizar sus actividades en el sitio web<br><br>GIVEN el Cliente quiere visualizar sus actividades <br><br>WHEN se le asignen en las asesorias y/o reuniones<br><br>AND complete las acciones para dirigirse al apartado,<br><br>THEN irá al apartado de "actividades" dentro del sitio web y podrá visualizarlos.</td>
        <td>EP02</td>
    </tr>
    <tr>
        <td>HU04</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
        <td>Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>GIVEN que el usuario necesite realizar una búsqueda de abogado médico,<br>
    <br>WHEN seleccione la búsqueda por filtros,<br>
    <br>AND escoge los parámetros de filtro,<br>
    <br>THEN la búsqueda será exitosa de acuerdo a lo seleccionado.</td>
        <td>EP02</td>
    </tr>
    <tr>
        <td>HU05</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>Scenario: Suscripción a un plan de usuario<br>
    <br>GIVEN un usuario quiere inscribirse en la plataforma MedicDefense,<br>
    <br>WHEN escoge el tipo de suscripción (mensual o anual) de acuerdo a lo que le beneficie,<br>
    <br>AND realice el pago,<br>
    <br>THEN podrá recibir los beneficios de la suscripción escogida.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU06</td>
        <td>Visualización de Perfil de Abogado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
        <td>Scenario: Visualización de perfil<br>
    <br>GIVEN un usuario quiere ver los perfiles de los abogados médicos en MedicDefense,<br>
    <br>AND tiene curiosidad sobre los perfiles de los abogados médicos,<br>
    <br>WHEN entra a la sección “Perfiles de Abogados” dentro del sitio web,<br>
    <br>THEN podrá visualizar los perfiles.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU07</td>
        <td>Notificaciones de las consultas programadas</td>
        <td>Como usuario de la plataforma, quiero recibir notificaciones sobre las consultas programadas con los abogados para recordarme la fecha y hora de la cita.</td>
        <td>Scenario: Notificación de las consultas programadas<br>
    <br>GIVEN un usuario ha programado una consulta con un abogado especializado en la medicina legal,<br>
    <br>WHEN se acerque la fecha y hora de la consulta,<br>
    <br>THEN debe recibir una notificación por correo electrónico que incluya detalles de la consulta como la fecha, hora y tema.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>HU08</td>
        <td>Seguimiento de casos legales</td>
        <td>Como usuario de la plataforma, quiero tener la capacidad de realizar un seguimiento de los casos legales en los que estoy involucrado para ver el progreso realizado por el abogado asignado.</td>
        <td>Scenario: Seguimiento de su caso legal<br>
    <br>GIVEN el usuario está dentro de su perfil en la plataforma MedicDefense,<br>
    <br>WHEN acceda a la sección de seguimiento de casos legales,<br>
    <br>THEN verá una lista de todos los casos activos en los que está involucrado, con detalles sobre el estado actual de su caso legal, las acciones tomadas y los próximos pasos planificados para el caso.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>HU09</td>
        <td>Calificación y reseñas para los Médicos Abogados</td>
        <td>Como usuario de la plataforma MedicDefense, quiero poder calificar y dejar reseñas sobre cómo fue mi experiencia que tuve con un médico abogado después de una consulta, para ayudar a otros usuarios a tomar decisiones informadas.</td>
        <td>Scenario: Calificación con reseñas a Médico Abogado<br>
    <br>GIVEN un usuario ha completado una consulta con un médico abogado,<br>
    <br>WHEN finalice la sesión sobre la consulta que pidió,<br>
    <br>THEN debe tener la opción de calificar la consulta y dejar comentarios sobre la experiencia, los cuales quedarán visibles para otros usuarios que estén interesados en pedir sus servicios.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>HU10</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>Scenario: Visualizar información sobre los servicios<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección con información acerca de los servicios de MedicDefense.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU11</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de  MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>Scenario: Visualización de una sección de contacto<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección de contacto con campos como nombre, correo, teléfono, mensaje para solicitar información.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU12</td>
        <td>Sección about us</td>
        <td>Como visitante de la landing page de  MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>Scenario: Visualización de una sección about us<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección about us que le brinda información acerca de la empresa cuyos servicios le interesan.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU13</td>
        <td>Verificación de Certificado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios.</td>
        <td>Scenario: Registro y verificación de certificado médico.<br><br>GIVEN un médico quiere registrarse en la plataforma MedicDefense.<br><br>AND rellena los datos necesarios.<br><br>WHEN sube un archivo de su certificado médico.<br><br>AND el sistema verifique su veracidad.<br><br>THEN su cuenta es registrada.<br><br>AND tiene acceso a la plataforma.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>HU14</td>
        <td>Editar Perfil</td>
        <td>Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados.</td>
        <td>Scenario: Editar Perfil.<br><br>GIVEN un usuario ingresa a la plataforma MedicDefense.<br><br>AND está en el apartado de Perfil.<br><br>WHEN presione la opción de Editar Perfil.<br><br>AND cambie los datos correspondientes.<br><br>AND presione Guardar Cambios.<br><br>THEN sus datos son cambiados en el sistema.<br><br>AND se refleja en su perfil.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>HU15</td>
        <td>Canales de contacto</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago.</td>
        <td>Scenario: Contactar a un abogado.<br><br>GIVEN un usuario ingrese a la plataforma MedicDefense.<br><br>AND esté en el apartado de Abogado.<br><br>WHEN presione el botón de Correo.<br><br>AND tenga su plataforma de correo ingresada en el navegador.<br><br>THEN será redireccionado a su plataforma de correo.<br><br>AND le mandará un correo al abogado.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU16</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentacion de mi caso.</td>
        <td>Scenario: Visualización de documentacion<br>
    <br>GIVEN un usuario quiere ver su caso con su respectiva documentacion en MedicDefense,<br>
    <br>WHEN entre a la sección “Resumen”,<br>
    <br>AND seleccione su caso,<br>
    <br>THEN podrá visualizar toda la documentacion de su caso.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU17</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rapida y eficientemente con mi seleccionado medico asesor.</td>
        <td>Scenario: Contacto con el medido asesor seleccionado<br>
    <br>GIVEN un usuario quiere contactarse con su medico asesor en MedicDefense,<br>
    <br>WHEN entre a la sección “Perfiles de Abogados” dentro del sitio web,<br>
    <br>THEN tendrá la informacion del medico asesor que seleccionó para poder tener contacto con él.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>HU18</td>
        <td>Sección de Creadores</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>Scenario: Visualización de una sección creadores<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección creadores que le brinda información acerca de los creadores de la empresa.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU19</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>Scenario: Visualización de una sección inicio<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección inicio que tenga una barra de navegación donde puede ver el logo para poder desplazarse mejor.</td>
        <td>EP03</td>
    </tr>
</table>

## 3.3. Impact Mapping

En esta sección, se plantearon metas de negocio utilizando los criterios SMART para elaborar el Impact Mapping en base a nuestras User Personas y User Stories.

**Segmento 1**
![alt text](<../assets/imgs/Clara-ImpactMap.png>)

**Segmento 2**
![alt text](<../assets/imgs/Carlos-ImpactMap.png>)

## 3.4. Product Backlog

<table>
    <tr>
        <th>#Orden</th>
        <th>User Story/Technical Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Story Points(1 / 2 / 3 / 5 / 8)</th>
    </tr>
    <tr>
        <td>1</td>
        <td>US19</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>2</td>
        <td>US10</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>3</td>
        <td>US12</td>
        <td>Sección about us</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>4</td>
        <td>US11</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>2</td>
    </tr>
       <tr>
        <td>5</td>
        <td>US02</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como visitante de la landing page de MedicDefense, quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>6</td>
        <td>US18</td>
        <td>Sección de Creadores</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>1</td>
    </tr>
    <tr>
        <td>7</td>
        <td>US05</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>8</td>
        <td>US06</td>
        <td>Visualización de Perfil de Abogado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>9</td>
        <td>US15</td>
        <td>Canales de contacto</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>10</td>
        <td>US17</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rapida y eficientemente con mi seleccionado medico asesor.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>11</td>
        <td>US13</td>
        <td>Verificación de Certificado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>12</td>
        <td>US09</td>
        <td>Calificación y reseñas para los Médicos Abogados</td>
        <td>Como usuario de la plataforma MedicDefense, quiero poder calificar y dejar reseñas sobre cómo fue mi experiencia que tuve con un médico abogado después de una consulta, para ayudar a otros usuarios a tomar decisiones informadas.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>13</td>
        <td>US04</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>14</td>
        <td>US03</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>15</td>
        <td>US08</td>
        <td>Seguimiento de casos legales</td>
        <td>Como usuario de la plataforma, quiero tener la capacidad de realizar un seguimiento de los casos legales en los que estoy involucrado para ver el progreso realizado por el abogado asignado.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>16</td>
        <td>US14</td>
        <td>Editar Perfil</td>
        <td>Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>17</td>
        <td>US16</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentacion de mi caso.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>18</td>
        <td>US01</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero poder eliminar mi cuenta en caso para no tener vinculo con el sitio web.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>19</td>
        <td>US07</td>
        <td>Notificaciones de las consultas programadas</td>
        <td>Como usuario de la plataforma, quiero recibir notificaciones sobre las consultas programadas con los abogados para recordarme la fecha y hora de la cita.</td>
        <td>5</td>
    </tr>
</table>
