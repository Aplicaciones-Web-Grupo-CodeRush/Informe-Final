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
        <td>EP05</td>
        <td>Tratado de datos</td>
        <td>Como administrador, deseo que haya opciones pertinentes para tratar y almacenar los distintos datos importantes de la aplicación.</td>
        <td></td>
        <td></td>
    </tr>
    <td>EP06</td>
        <td>Implementación del Frontend</td>
        <td>Como usuario, deseo que se implementen distintos apartados del frontend para facilitar su uso.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>US01</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero poder eliminar mi cuenta para no tener vínculo con el sitio web.</td>
        <td>Scenario: El Usuario elimina una cuenta<br><br>GIVEN el Cliente está en la plataforma<br><br>WHEN complete las verificaciones para ver que sea el usuario de la cuenta,<br><br>AND presione el botón "eliminar cuenta" del apartado de configuración,<br><br>THEN su cuenta se elimina exitosamente.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como visitante de la landing page de MedicDefense, quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>Scenario: El Usuario quiere visualizar tipos de suscripciones<br><br>GIVEN el Cliente se encuentra en el Landing Page<br><br>WHEN baje hasta la sección de Suscripciones<br><br>OR presione el botón en la barra de navegación<br><br>THEN se le muestran las promociones que tiene el sitio web.</td>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>Scenario: El Cliente quiere visualizar sus actividades en el sitio web<br><br>GIVEN el Cliente contacta a un abogado<br><br>WHEN se le asignen en las asesorias y/o reuniones<br><br>AND complete las acciones para dirigirse a la sección<br><br>THEN se le muestran las actividades que tiene dentro de la plataforma.</td>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
        <td>Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>GIVEN el usuario este en la sección de "Abogados",<br>
    <br>WHEN seleccione la búsqueda por filtros,<br>
    <br>AND escoge los parámetros de filtro,<br>
    <br>THEN la búsqueda muestra una lista de abogados según a lo seleccionado.</td>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>Scenario: Suscripción a un plan de usuario<br>
    <br>GIVEN un usuario este en la plataforma<br>
    <br>WHEN escoge el tipo de suscripción (mensual o anual)<br>
    <br>AND realice el pago,<br>
    <br>THEN recibe los beneficios de la suscripción escogida.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Visualización de Perfil de Abogado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
        <td>Scenario: Visualización de perfil<br>
    <br>GIVEN un usuario este en la plataforma<br>
    <br>AND este en la sección de "Abogados"<br>
    <br>WHEN seleccione a un abogado en particular<br>
    <br>THEN se visualiza su perfil.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>US07</td>
        <td>Notificaciones de las consultas programadas</td>
        <td>Como usuario de la plataforma, quiero recibir notificaciones sobre las consultas programadas con los abogados para recordarme la fecha y hora de la cita.</td>
        <td>Scenario: Notificación de las consultas programadas<br>
    <br>GIVEN un usuario programa una consulta con un abogado especializado en la medicina legal,<br>
    <br>WHEN se acerque la fecha y hora de la consulta,<br>
    <br>THEN recibe una notificación por correo electrónico que incluya detalles de la consulta como la fecha, hora y tema.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>US08</td>
        <td>Seguimiento de casos legales</td>
        <td>Como usuario de la plataforma, quiero tener la capacidad de realizar un seguimiento de los casos legales en los que estoy involucrado para ver el progreso realizado por el abogado asignado.</td>
        <td>Scenario: Seguimiento de su caso legal<br>
    <br>GIVEN el usuario esté dentro de su perfil en la plataforma MedicDefense,<br>
    <br>WHEN acceda a la sección de seguimiento de casos legales,<br>
    <br>THEN se le muestra una lista de todos los casos activos en los que está involucrado, con detalles sobre el estado actual de su caso legal, las acciones tomadas y los próximos pasos planificados para el caso.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>US09</td>
        <td>Calificación y reseñas para los Médicos Abogados</td>
        <td>Como usuario de la plataforma MedicDefense, quiero poder calificar y dejar reseñas sobre cómo fue mi experiencia que tuve con un médico abogado después de una consulta, para ayudar a otros usuarios a tomar decisiones informadas.</td>
        <td>Scenario: Calificación con reseñas a Médico Abogado<br>
    <br>GIVEN un usuario completa una consulta con un médico abogado,<br>
    <br>WHEN finalice la sesión sobre la consulta que pidió,<br>
    <br>THEN tiene la opción de calificar la consulta y dejar comentarios sobre la experiencia<br><br>AND quedan visibles para otros usuarios que estén interesados en pedir sus servicios.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>US10</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>Scenario: Visualizar información sobre los servicios<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN llegue a la sección de "Servicios",<br>
    <br>THEN se le muestra información acerca de los servicios de MedicDefense.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>US11</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de  MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>Scenario: Visualización de una sección de contacto<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN llegue a la sección de "Contactar",<br>
    <br>THEN llena los campos como nombre, correo, teléfono, mensaje para solicitar información.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>US12</td>
        <td>Sección about us</td>
        <td>Como visitante de la landing page de  MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>Scenario: Visualización de una sección about us<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>llegue a la sección de "About Us",<br>
    <br>THEN se le brinda información acerca de la empresa cuyos servicios le interesan.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>US13</td>
        <td>Verificación de Certificado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios.</td>
        <td>Scenario: Registro y verificación de certificado médico.<br><br>GIVEN un médico este en la página de registro.<br><br>AND rellena los datos necesarios.<br><br>WHEN sube un archivo de su certificado médico.<br><br>AND el sistema verifique su veracidad.<br><br>THEN su cuenta es registrada.<br><br>AND tiene acceso a la plataforma.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>US14</td>
        <td>Editar Perfil</td>
        <td>Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados.</td>
        <td>Scenario: Editar Perfil.<br><br>GIVEN un usuario ingresa a la plataforma MedicDefense.<br><br>AND está en la sección de Perfil.<br><br>WHEN presione la opción de Editar Perfil.<br><br>AND cambie los datos correspondientes.<br><br>AND presione Guardar Cambios.<br><br>THEN sus datos son cambiados en el sistema.<br><br>AND se refleja en su perfil.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>US15</td>
        <td>Canales de contacto</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago.</td>
        <td>Scenario: Contactar a un abogado.<br><br>GIVEN un usuario ingrese a la plataforma MedicDefense.<br><br>AND esté en el perfil de un Abogado.<br><br>WHEN presione el botón de Correo.<br><br>AND tenga su plataforma de correo ingresada en el navegador.<br><br>THEN accede a su plataforma de correo.<br><br>AND le manda un correo al abogado.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>US16</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentacion de mi caso.</td>
        <td>Scenario: Visualización de documentacion<br>
    <br>GIVEN un usuario este en la plataforma de MedicDefense,<br>
    <br>WHEN entre a la sección “Resumen”,<br>
    <br>AND seleccione su caso,<br>
    <br>THEN visualiza toda la documentacion de su caso.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>US17</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rapida y eficientemente con mi seleccionado medico asesor.</td>
        <td>Scenario: Contacto con el medido asesor seleccionado<br>
    <br>GIVEN un usuario este en la plataforma de MedicDefense,<br>
    <br>WHEN entre a la sección “Perfiles de Abogados” dentro del sitio web,<br>
    <br>THEN se le muestra la informacion del médico asesor que seleccionó para poder tener contacto con él.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>US18</td>
        <td>Sección de Creadores</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>Scenario: Visualización de una sección creadores<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN llegue a la sección "Creadores"<br>
    <br>THEN se le brinda información acerca de los creadores de la empresa.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>US19</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>Scenario: Visualización de una sección inicio<br>
    <br>GIVEN un usuario visita la landing page,<br>
    <br>WHEN presione una de las secciones de la barra de navegación<br>
    <br>THEN se desplaza a la sección seleccionada.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>US20</td>
        <td>Integración de pagos</td>
        <td>Como desarrollador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
        <td>Scenario: Implementar un proceso de pago seguro para las suscripciones<br>
    <br>GIVEN se envía información de pago a través del frontend<br>
    <br>WHEN se transfiere la información a un sistema de pago seguro,<br>
    <br>AND el sistema verifica la validez de la información de pago,<br><br>THEN el sistema procesa el pago de forma segura y actualiza el estatus de la suscripción en la base de datos.</td>
        <td>EP05</td>
    </tr>
    <tr>
    <td>US21</td>
        <td>Base de datos de usuarios</td>
        <td>Como desarrollador de la plataforma MedicDefense, quiero que haya una base de datos segura y escalable, para proteger y gestionar eficazmente la información</td>
<td>Scenario: Acceso a datos para auditorías internas.<br>
<br>GIVEN hay información de los usuarios en la base de datos,<br>
<br>WHEN un desarrollador solicite acceder a los datos de la misma,<br>
<br>AND la plataforma valida sus credenciales,<br>
<br>THEN se le proporciona los datos relevantes, garantizando la confidencialidad y la integridad de la información.</td>
<td>EP05</td>
    </tr>
    <td>US22</td>
        <td>API para gestión de perfiles</td>
        <td>Como desarrollador de la plataforma MedicDefense, quiero que existan APIs robustas para crear, editar y eliminar perfiles de usuario, y gestionar la información de manera segura y eficiente.</td>
        <td>Scenario: Actualizar información de un perfil por motivos de seguridad.<br>
<br>GIVEN un administrador accede al API,<br>
<br>WHEN modifica y guarda los cambios,<br>
<br>AND confirma la operación,<br>
<br>THEN la API actualiza los datos en la base de datos,<br>
<br>AND recibe una notificación indicando que la actualización fue exitosa.</td>
<td>EP05</td>
    </tr>
    <td>US23</td>
        <td>Logging de Actividades</td>
        <td>Como desarrollador de la plataforma MedicDefense, quiero que exista un sistema de logging robusto para registrar la actividad en la plataforma, facilitando la auditoría y la detección temprana de problemas.</td>
        <td>Scenario: Registrar una actividad crítica para la auditoría de seguridad.<br>
<br>GIVEN se lleva a cabo una acción crítica en la plataforma,<br>
<br>WHEN la acción es ejecutada,<br>
<br>THEN el sistema registra detalladamente la acción en los logs de seguridad,<br>
<br>AND se notifica a los usuarios pertinentes sobre la actividad registrada.</td>
<td>EP05</td>
    </tr>
    <td>US24</td>
        <td>API para búsqueda por filtros</td>
        <td>Como desarrollador de la plataforma MedicDefense, quiero que exista una API para búsquedas por filtros, para mejorar la accesibilidad de la información y facilitar la búsqueda de perfiles específicos.</td>
        <td>Scenario: Buscar perfiles específicos basados en criterios complejos.<br>
<br>GIVEN un desarrollador necesita encontrar información de perfiles específicos basados en criterios complejos,<br>
<br>WHEN utiliza la API de búsqueda por filtros en la interfaz de la plataforma,<br>
<br>THEN la API proporciona resultados precisos y rápidos, ayudándole a gestionar eficientemente la información.</td>
<td>EP05</td>
    </tr>
    <td>US25</td>
        <td>Servicio de notificaciones</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que exista un servicio de notificaciones, para mantenerme informado sobre actualizaciones importantes y eventos relevantes en la plataforma.</td>
        <td>Scenario: Recibir notificaciones sobre una actualización de seguridad importante.<br>
<br>GIVEN se ha emitido una actualización de seguridad,<br>
<br>WHEN el sistema procesa la actualización,<br>
<br>AND identifica a un usuario afectado,<br>
<br>THEN el servicio de notificaciones le envía automáticamente una alerta,<br>
<br>AND recibe la notificación en tiempo real.</td>
<td>EP06</td>
    </tr>
    <td>US26</td>
        <td>Soporte para múltiples navegadores</td>
        <td>Como desarrollador, quiero garantizar la compatibilidad en múltiples navegadores, para una experiencia de usuario uniforme.</td>
        <td>Scenario: Verificar y asegurar la compatibilidad de la plataforma en diferentes navegadores.<br>
    <br>GIVEN los administradores y usuarios acceden a la plataforma desde diversos navegadores,<br>
    <br>WHEN navegan y realizan operaciones críticas,<br>
    <br>THEN el sistema mantiene una funcionalidad consistente y segura, sin importar el navegador utilizado.</td>
        <td>EP06</td>
    </tr>
    <tr>
    <td>US27</td>
    <td>Configuración de la base de datos</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero diseñar y configurar correctamente la estructura de la base de datos para almacenar la información de los abogados de forma óptima.</td>
<td>Scenario: Configuración de la base de datos<br><br>GIVEN los desarrolladores configuren la base de datos para almacenar la información de los abogados,<br><br>WHEN definen la estructura de la tabla 'abogados' con los campos requeridos como nombre, especialidad y ubicación,<br><br>THEN la base de datos se configura correctamente para almacenar la información de los abogados.</td>
<td>EP05</td>
  </tr>
  <tr>
    <td>US28</td>
    <td>Desarrollo del frontend para la lista de abogados</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero crear componentes en el frontend para mostrar la lista de abogados de manera clara y que la interfaz de usuario sea fácil de usar.</td>
<td>Scenario: Desarrollo del frontend para la lista de abogados<br><br>GIVEN se necesita ver la lista de abogados en el frontend,<br><br>WHEN se creen componentes en el frontend para mostrar la lista de abogados,<br><br>THEN la lista de abogados se muestra correctamente en la interfaz de usuario.</td>
<td>EP06</td>
  </tr>
  <tr>
    <td>US29</td>
    <td>Integración del toolbar</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero implementar un toolbar en el frontend para navegar fácilmente entre las diferentes secciones de la aplicación.</td>
<td>Scenario: Integración del toolbar<br><br>GIVEN se necesita acceder a diferentes opciones de la aplicación,<br><br>WHEN se creen componentes en el frontend para implementar el toolbar,<br><br>THEN la navegación entre las secciones es fluida y sin problemas.</td>
<td>EP06</td>
  </tr>
  <tr>
    <td>US30</td>
    <td>Estilizado y diseño responsivo</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero aplicar estilos CSS que garanticen un diseño atractivo y responsivo en todas las páginas de la aplicación, para una experiencia de usuario óptima.</td>
<td>Scenario: Estilizado y diseño responsivo<br><br>GIVEN se necesita una experiencia visual atractiva y compatible con diferentes dispositivos,<br><br>WHEN se aplican estilos CSS utilizando frameworks como Bootstrap o Material-UI,<br><br>THEN el diseño de la aplicación es atractivo y compatible con diferentes tamaños de pantalla y dispositivos.</td>
<td>EP06</td>
  </tr>
  <tr>
    <td>US31</td>
    <td>Implementación de la funcionalidad de búsqueda de abogados</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero agregar una función de búsqueda en la página de lista de abogados para que pueda encontrar abogados por nombre o especialidad de manera fácil y rápida.</td>
<td>Scenario: Búsqueda de abogados<br><br>GIVEN se necesita buscar un abogado específico,<br><br>WHEN se creen componentes en el frontend para implementar los filtros de busqueda<br><br>THEN se muestran los resultados relevantes que coinciden con el término de búsqueda.</td>
<td>EP06</td>
  </tr>
  <tr>
    <td>US32</td>
    <td>Implementación de la paginación de resultados</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero agregaar funcionalidad de paginación en la página de lista de abogados para que pueda navegar fácilmente por una larga lista de abogados.</td>
<td>Scenario: Paginación de resultados<br><br>GIVEN se necesita navegar por una larga lista de abogados,<br><br>WHEN se creen componentes en el frontend para implementar la paginación de la lista de abogados<br><br>THEN se puede navegar fácilmente entre las páginas utilizando los controles de paginación.</td>
<td>EP06</td>
  </tr>
    <tr>
    <td>US33</td>
    <td>Implementar card que se superpone para mostrar perfiles de abogados</td>
<td>Como desarrollador de la plataforma MedicDefense, quiero implementar un card que se superpone para mostrar los perfiles completos de los abogados seleccionados de manera clara y organizada.</td>
<td>Scenario: Visualización del perfil completo de un abogado en un card que se superpone<br><br>GIVEN se necesita ver la información detallada de un abogado,<br><br>WHEN se creen componentes en el frontend para implementar los cards de perfiles<br><br>THEN se muestra claramente la información detallada del abogado seleccionado.</td>
<td>EP06</td>
    </tr>
    <tr>
    <td>US34</td>
    <td>Implementar método para cargar información de abogado en el card que se superpone</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero implementar un método para cargar dinámicamente la información completa de un abogado seleccionado en el card que se superpone, para una experiencia de usuario fluida y sin problemas al explorar perfiles de abogados.</td>
<td>Scenario: Carga dinámica de información del abogado en el card que se superpone<br><br>GIVEN se necesita ver la información detallada de un abogado seleccionado,<br><br>WHEN se creen componentes en el frontend para implementar el card del perfil del abogado<br><br>THEN se carga dinámicamente la información detallada del abogado seleccionado en el card que se superpone.</td>
<td>EP06</td>
    </tr>
    <tr>
    <td>US35</td>
    <td>Implementación de la Entidad de Usuario</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero crear la entidad de usuario con todos los atributos necesarios para asegurar una gestión adecuada de la información.</td>
<td>Scenario: Creación de la entidad de usuario<br><br>GIVEN se necesita representar a los usuarios en el sistema,<br><br>WHEN se define y crea la entidad de usuario con atributos como ID, nombre, especialidad, correo electrónico, contraseña, etc.,<br><br>THEN la entidad está disponible en el sistema para ser utilizada en otras funcionalidades de la plataforma.</td>
<td>EP01</td>
    </tr>
    <tr>
    <td>US36</td>
    <td>Diseño de la Sección de Perfil de Usuario</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero diseñar la sección de perfil para que muestre claramente la información de médico o estudiante de medicina de manera organizada y fácil de entender.</td>
<td>Scenario: Diseño del perfil de usuario<br><br>GIVEN un usuario necesita ver su información de usuario de manera organizada,<br><br>WHEN el desarrollador diseña la sección de perfil de usuario incluyendo campos como nombre, especialidad, y datos de contacto,<br><br>THEN la sección de perfil se muestra de forma atractiva y es fácil de navegar.</td>
<td>EP01</td>
    </tr>
    <tr>
    <td>US37</td>
    <td>Diseño de la Interfaz de Edición de Perfil de Usuario</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero diseñar la interfaz de edición de perfil para que se pueda ver claramente los campos que modificar en el perfil y realizar cambios fácilmente.</td>
<td>Scenario: Diseño de la interfaz de edición de perfil<br><br>GIVEN un usuario desea actualizar su perfil,<br><br>WHEN se creen componentes en el frontend para implementar los campos de edición de datos<br><br>THEN se muestra una interfaz con los campos de su perfil actual listos para ser editados.</td>
<td>EP01</td>
    </tr>
    <tr>
    <td>US38</td>
    <td>Diseño de la Interfaz de Edición de Filtros</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero diseñar la interfaz de filtros para que se pueda ver claramente las opciones de filtro disponibles y seleccionarlas fácilmente según las necesidades del usuario.</td>
<td>Scenario: Diseño de la interfaz de filtros<br><br>GIVEN un usuario necesita buscar algo aplicando cierto filtro,<br><br>WHEN se creen componentes en el frontend para implementar los filtros de busqueda<br><br>THEN se muestra una interfaz con todas las opciones de filtros disponibles.</td>
<td>EP01</td>
    </tr>
    <tr>
    <td>US39</td>
    <td>Diseño de la sección Suscripciones</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero implementar la sección de suscripción para que pueda obtener ayuda legal en caso de necesitarlo, lo que brindará seguridad y tranquilidad al usuario.</td>
<td>Scenario: Suscripción para ayuda legal<br><br>GIVEN un usuario está autenticado en la plataforma,<br><br>WHEN se creen componentes en el frontend para implementar la lista de suscripciones<br><br>THEN se le presenta una lista de planes de suscripción disponibles.</td>
<td>EP06</td>
    </tr>
    <tr>
    <td>US40</td>
    <td>Diseño de la interfaz Suscripciones</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero implementar una interfaz donde se pueda ver claramente los detalles de la suscripción actual y el plan seleccionado.</td>
<td>Scenario: Ver detalles de la suscripción<br><br>GIVEN un usuario,<br><br>WHEN se creen componentes en el frontend para adquirir una suscripción,<br><br>THEN se le presenta un apartado donde puedo ver los detalles de mi suscripción.</td>
<td>EP06</td>
    </tr>
    <tr>
    <td>US41</td>
    <td>Diseño de la interfaz de pago Suscripciones</td>
    <td>Como desarrollador de la plataforma MedicDefense, quiero implementar una interfaz donde se pueda ingresar fácilmente los detalles de tarjeta de crédito y el monto a pagar para completar el proceso de pago de la suscripción de manera segura y sin complicaciones.</td>
<td>Scenario: Ingreso de detalles de pago<br><br>GIVEN un usuario quiere pagarle a un abogado,<br><br>WHEN se creen componentes en el frontend para implementar la adquisición de servicios,<br><br>THEN se le presenta una interfaz para ingresar los detalles de pago como tarjeta y monto a pagar.</td>
<td>EP06</td>
    </tr>
    <tr>
    <td>HU42</td>
    <td>Gestión de Consultas Médicas</td>
    <td>Como administrador del sistema MedicDefense, quiero tener un servicio centralizado para la gestión de consultas médicas, de modo que pueda manejar eficientemente la creación, actualización, y almacenamiento de datos de consultas médicas en los diferentes repositorios, asegurando la integración con el sistema de localización y la base de datos relacional.</td>
<td>Scenario: Creación exitosa de una consulta médica<br><br>GIVEN que un administrador autenticado accede al sistema de gestión de consultas.<br><br>WHEN solicita la creación de una nueva consulta con detalles válidos.<br><br>AND los datos proporcionados cumplen con los requisitos de validación.<br><br>THEN el sistema debe almacenar la nueva consulta en el repositorio correspondiente.<br><br>AND confirmar la creación de la consulta al usuario.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU43</td>
    <td>Backend de Pagos</td>
    <td>Como desarrollador del sistema MedicDefense, quiero tener un servicio centralizado para la gestión de pagos, de modo que pueda manejar almacenar los datos relevantes en los diferentes repositorios, asegurando la integración con el sistema de localización y la base de datos relacional.</td>
<td>Scenario: Almacenar datos de pago<br><br>GIVEN que un administrador autenticado accede al sistema de información de pago.<br><br>WHEN proporciona detalles válidos al sistema.<br><br>AND selecciona "Publicar".<br><br>THEN el sistema debe almacenar la nueva información de pago en el repositorio correspondiente.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU44</td>
    <td>Integración MySQL</td>
    <td>Como administrador del sistema MedicDefense, quiero que mis sistemas de backend se puedan conectar con una base de datos MySQL para tener la información importante en una base de datos relacional.</td>
<td>Scenario: Integración con los servicios específicos<br><br>GIVEN que un administrador autenticado accede a los sistemas del backend.<br><br>WHEN hace una operación de inserción, eliminación, actualización o de recolección.<br><br>AND la operación es válida.<br><br>THEN el sistema debe conectar con la base de datos en MySQL.<br><br>AND efectuar la operación apropiadamente.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU45</td>
    <td>Creación y Gestión de Recursos Educativos</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de recursos educativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos.</td>
<td>Scenario: Crear Recurso Educativo<br><br>GIVEN que un administrador autenticado accede al sistema de gestión de recursos educativos.<br><br>WHEN proporciona detalles válidos al sistema.<br><br>AND los datos proporcionados cumplen con los requisitos de validación.<br><br>THEN el sistema debe almacenar el nuevo recurso educativo en el repositorio correspondiente.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU46</td>
    <td>Implementación de Categorías de Recursos</td>
    <td>Como desarrollador backend, quiero implementar la funcionalidad para gestionar categorías y etiquetas de recursos educativos para organizar los recursos de manera eficiente.</td>
<td>Scenario: Conexión exitosa<br><br>GIVEN que un administrador autenticado accede al sistema de información de pago.<br><br>WHEN seleccione una Categoría al sistema.<br><br>AND esta sea válida.<br><br>THEN el sistema debe organizar los recursos educacionales según la categoría.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU47</td>
    <td>Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
    <td>Como desarrollador backend, quiero implementar una funcionalidad de búsqueda avanzada para que los usuarios puedan buscar recursos educativos por diferentes criterios.</td>
<td>Scenario: Buscar recursos educativos<br><br>GIVEN que un administrador autenticado accede al sistema de información de pago.<br><br>WHEN proporciona detalles válidos al sistema.<br><br>AND selecciona "Buscar".<br><br>THEN el sistema debe presentar los recursos educativos.<br><br>AND filtrarlos según criterios avanzados.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU48</td>
    <td>Obtener todas las notificaciones</td>
    <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema.</td>
<td>Scenario: Obtener notificaciones<br><br>GIVEN que un administrador autenticado accede al sistema de información de pago.<br><br>WHEN entre al endpoint GET.<br><br>THEN el sistema debe presentar todas las notificaciones en el sistema.</td>
<td>EP05</td>
    </tr>
     <tr>
    <td>HU49</td>
    <td>Crear una nueva notificación</td>
    <td>Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema.</td>
<td>Scenario: Almacenar notificación<br><br>GIVEN que un administrador autenticado accede al sistema de gestión de notificaciones.<br><br>WHEN proporciona detalles válidos al sistema.<br><br>AND selecciona "Publicar".<br><br>THEN el sistema debe almacenar la nueva información de notificación en el repositorio correspondiente.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
    </tr>
    <tr>
    <td>HU50</td>
    <td>Obtener una notificación por ID</td>
    <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular basada en su identificador único.</td>
<td>Scenario: Obtener notificación<br><br>GIVEN que un administrador autenticado accede al sistema de información de pago.<br><br>WHEN haga una operación GET.<br><br>AND especifique un Id.<br><br>THEN el sistema debe mostrar la notificación con el Id correspondiente.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
    </tr>
    <tr>
    <td>HU51</td>
    <td>Creación y gestión de recursos de casos legales</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan gestionar los casos legales.</td>
<td>Scenario: Crear Caso Legal<br><br>GIVEN que un administrador autenticado accede al sistema de gestión de casos legales.<br><br>WHEN proporciona detalles válidos al sistema.<br><br>AND los datos proporcionados cumplen con los requisitos de validación.<br><br>THEN el sistema debe almacenar el nuevo caso legal en el repositorio correspondiente.<br><br>AND confirmar dicha operación.</td>
<td>EP05</td>
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
        <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
    </tr>
    <tr>
    <td>1</td>
        <td>US19</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>2</td>
        <td>US12</td>
        <td>Sección de about us</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>2</td>
        </tr>
         <tr>
        <td>3</td>
        <td>US10</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>4</td>
        <td>US02</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>5</td>
        <td>US11</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>2</td>
    </tr>
     <tr>
        <td>6</td>
        <td>US18</td>
        <td>Sección de creadores</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>2</td>
    </tr>
<tr>
    <td>7</td>
        <td>US26</td>
        <td>Soporte para múltiples navegadores</td>
        <td>Como desarrollador, quiero garantizar la compatibilidad en múltiples navegadores, para una experiencia de usuario uniforme.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>8</td>
        <td>US27</td>
        <td>Configuración de la base de datos</td>
        <td>Como usuario de la plataforma, confío en que se configure la base de datos de manera adecuada para garantizar la integridad y seguridad de la información de los abogados.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>9</td>
        <td>US28</td>
        <td>Desarrollo del frontend para la lista de abogados</td>
        <td>Como usuario de la plataforma, espero que se desarrolle el frontend para mostrar la lista de abogados de forma clara y que la interfaz sea amigable para facilitar la búsqueda.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>10</td>
        <td>US29</td>
        <td>Integración del toolbar</td>
        <td>Como usuario de la plataforma, deseo tener un toolbar integrado que facilite la navegación entre las diferentes secciones de la aplicación.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>11</td>
        <td>US30</td>
        <td>Estilizado y diseño responsivo</td>
        <td>Como usuario de la plataforma, espero que se apliquen estilos CSS para asegurar un diseño atractivo y que se adapte correctamente a diferentes dispositivos y tamaños de pantalla.</td>
        <td>5</td>
    </tr>
    <tr>
    <td>12</td>
        <td>US31</td>
        <td>Implementación de la funcionalidad de búsqueda de abogados</td>
        <td>Como usuario de la plataforma, deseo tener una función de búsqueda en la página de lista de abogados para encontrar fácilmente profesionales por nombre o especialidad.</td>
        <td>3</td>
    </tr>
    <tr>
    <td>13</td>
        <td>US32</td>
        <td>Implementación de la paginación de resultados</td>
        <td>Como usuario de la plataforma, quiero que se agregue funcionalidad de paginación en la página de lista de abogados para facilitar la navegación cuando hay muchos resultados.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>14</td>
        <td>US06</td>
    <td>Perfil de abogado médico</td>
    <td>Como usuario, quiero poder acceder al perfil completo de un abogado específico al hacer clic en el botón "Perfil".</td>
    <td>2</td>
    </tr>
    <tr>
        <td>15</td>
        <td>US33</td>
        <td>Implementar card que se superpone para mostrar perfiles de abogados</td>
        <td>Como desarrollador quiero implementar un card que se superpone para mostrar los perfiles completos de los abogados seleccionados.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>16</td>
        <td>US34</td>
        <td>Implementar método para cargar información de abogado en el card que se superpone</td>
        <td>Como usuario de la plataforma, quiero que se implemente un método para cargar de manera fluida la información completa de un abogado seleccionado cuando visualizo su perfil.</td>
        <td>3</td>
    </tr>
    </tr>
        <tr>
        <td>17</td>
        <td>US35</td>
        <td>Implementación de la Entidad de Usuario</td>
        <td>Como usuario de la plataforma, espero que se implemente una entidad de usuario para garantizar la gestión adecuada de mi información personal en el sistema.</td>
        <td>2</td>
    </tr>
        <tr>
        <td>18</td>
        <td>US36</td>
        <td>Diseño de la Sección de Perfil de Usuario</td>
        <td>Como usuario de la plataforma, quiero una sección de perfil que me permita gestionar mi información personal de manera eficiente.</td>
        <td>3</td>
    </tr>
        <tr>
        <td>19</td>
        <td>US37</td>
        <td>Diseño de la Interfaz de Edición de Perfil de Usuario</td>
        <td>Como usuario de la plataforma, quiero una interfaz de edición de perfil intuitiva que me permita modificar fácilmente los campos de mi perfil.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>20</td>
        <td>US39</td>
        <td>Diseño de la sección Suscripciones</td>
        <td>Como desarrollador, quiero implementar la sección de suscripción para obtener ayuda legal en caso de cometer alguna negligencia médica, para estar protegido legalmente.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>21</td>
        <td>US40</td>
        <td>Diseño de la interfaz Suscripciones</td>
        <td>Como usuario de la plataforma, quiero una sección de suscripción que me brinde la posibilidad de obtener ayuda legal en caso de cometer alguna negligencia médica, para sentirme protegido legalmente.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>22</td>
        <td>US41</td>
        <td>Diseño de la interfaz de pago Suscripciones</td>
        <td>Como usuario de la plataforma, quiero una interfaz donde pueda ver claramente los detalles de mi suscripción actual, para tener acceso rápido a la información sobre mi plan seleccionado.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>23</td>
        <td>US38</td>
        <td>Diseño de la Interfaz de Edición de Filtros</td>
        <td>Como usuario de la plataforma, quiero que la interfaz de filtros sea clara para poder seleccionar fácilmente los campos que deseo filtrar.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>24</td>
        <td>US01</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,necesito poder eliminar mi cuenta en caso sea necesario para no tener vinculo con el sitio web.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>25</td>
        <td>US03</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>26</td>
        <td>US04</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>27</td>
        <td>US05</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>28</td>
        <td>US16</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentacion de mi caso.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>29</td>
        <td>US17</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rapida y eficientemente con mi seleccionado medico asesor.</td>
        <td>3</td>
    </tr>
        <tr>
        <td>30</td>
        <td>US43</td>
        <td>Backend de Pagos</td>
        <td>Como desarrollador del sistema MedicDefense, quiero tener un servicio centralizado para la gestión de pagos, de modo que pueda manejar almacenar los datos relevantes en los diferentes repositorios, asegurando la integración con el sistema de localización y la base de datos relacional. </td>
        <td>3</td>
    </tr>
        <tr>
        <td>31</td>
        <td>US20</td>
        <td>Integración de pagos</td>
        <td>Como administrador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>32</td>
        <td>US44</td>
        <td>Integración de MySQL/td>
        <td>Como administrador del sistema MedicDefense, quiero que mis sistemas de backend se puedan conectar con una base de datos MySQL para tener la información importante en una base de datos relacional. </td>
        <td>2</td>
            </tr>
        <tr>
        <td>33</td>
        <td>US21</td>
        <td>Base de datos de usuarios</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que implementen una base de datos segura y escalable, para proteger y gestionar eficazmente la información de los usuarios.</td>
        <td>3</td>
    </tr>
        <tr>
        <td>34</td>
        <td>US22</td>
        <td>API para gestión de perfiles</td>
        <td>Como usuario de la plataforma MedicDefense, quiero APIs robustas para crear, editar y eliminar perfiles de usuario.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>35</td>
        <td>US45</td>
        <td>Creación y Gestión de Recursos Educativos</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de recursos educativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos. </td>
        <td>3</td>
    </tr>
    <tr>
        <td>36</td>
        <td>US46</td>
        <td>Implementación de Categorías de Recursos</td>
        <td>Como desarrollador backend, quiero implementar la funcionalidad para gestionar categorías y etiquetas de recursos educativos para organizar los recursos de manera eficiente. </td>
        <td>3</td>
    </tr>
    <tr>
        <td>37</td>
        <td>US47</td>
        <td>Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
        <td>Como desarrollador backend, quiero implementar una funcionalidad de búsqueda avanzada para que los usuarios puedan buscar recursos educativos por diferentes criterios. </td>
        <td>3</td>
    </tr>
    <tr>
        <td>38</td>
        <td>US48</td>
        <td>Obtener todas las notificaciones</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema. </td>
        <td>2</td>
    </tr>
    <tr>
        <td>39</td>
        <td>US49</td>
        <td>Crear una nueva notificación</td>
        <td>Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema. </td>
        <td>2</td>
    </tr>
    <tr>
        <td>40</td>
        <td>US50</td>
        <td>Obtener una notificación por ID</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular basada en su identificador único. </td>
        <td>2</td>
    </tr>
    <tr>
        <td>41</td>
        <td>US51</td>
        <td>Creación y gestión de recursos de casos legales</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan gestionar los casos legales. </td>
        <td>4</td>
    </tr>
        <tr>
        <td>42</td>
        <td>US23</td>
        <td>Logging de Actividades</td>
        <td>Como usuario de la plataforma MedicDefense, quiero un sistema de logging robusto para registrar la actividad en la plataforma, facilitando la auditoría y la detección temprana de problemas.</td>
        <td>3</td>
    </tr>
        <tr>
        <td>43</td>
        <td>US24</td>
        <td>API para búsqueda por filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que creen una API para búsquedas por filtros, para mejorar la accesibilidad de la información.</td>
        <td>3</td>
    </tr>
        <tr>
        <td>44</td>
        <td>US42</td>
        <td>Gestión de Consultas Médicas</td>
        <td>Como administrador del sistema MedicDefense, quiero tener un servicio centralizado para la gestión de consultas médicas, de modo que pueda manejar eficientemente la creación, actualización, y almacenamiento de datos de consultas médicas en los diferentes repositorios, asegurando la integración con el sistema de localización y la base de datos relacional. </td>
        <td>3</td>
    </tr>
    <tr>
        <td>45</td>
        <td>US25</td>
        <td>Servicio de notificaciones</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que implementen un servicio de notificaciones, para mantenerme informado.</td>
        <td>5</td>
    </tr>
     <tr>
        <td>46</td>
        <td>US07</td>
        <td>Notificaciones de las consultas programadas</td>
        <td>Como usuario de la plataforma, quiero recibir notificaciones sobre las consultas programadas con los abogados para recordarme la fecha y hora de la cita.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>47</td>
        <td>US08</td>
        <td>Seguimiento de casos legales</td>
        <td>Como usuario de la plataforma, quiero tener la capacidad de realizar un seguimiento de los casos legales en los que estoy involucrado para ver el progreso realizado por el abogado asignado.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>48</td>
        <td>US09</td>
        <td>Calificación y reseñas para los Médicos Abogados</td>
        <td>Como usuario de la plataforma MedicDefense, quiero poder calificar y dejar reseñas sobre cómo fue mi experiencia que tuve con un médico abogado después de una consulta, para ayudar a otros usuarios a tomar decisiones informadas.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>49</td>
        <td>US13</td>
        <td>Verificación de Certificado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios. </td>
        <td>1</td>
    </tr>
    <tr>
        <td>50</td>
        <td>US14</td>
        <td>Editar Perfil</td>
        <td>Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados. </td>
        <td>2</td>
    </tr>
    <tr>
        <td>51</td>
        <td>US15</td>
        <td>Canales de contacto</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago. </td>
        <td>3</td>
    </tr>
</table>
