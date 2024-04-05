# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories

| Epics                        | User Stories                                                                                                                             |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Autenticación y autorización | 1.Eliminar cuenta de Usuario                                                                                                             |
| Visualizacion de Apartados   | 2. Visualización de lista de tipos de suscripción<br>3.Visualizar actividades del Usuario<br>6.Visualización de Perfil de Abogado Médico |
|                              |                                                                                                                                          |
|                              |                                                                                                                                          |

<table>
<tr>
    <th colspan="5">Historia de Usuario 1</th>
  </tr>
      <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU01</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Eliminar cuenta Usuario</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,necesito poder eliminar mi cuenta en caso sea necesario para no tener vinculo con el sitio web.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Usuario no tiene una cuenta<br><br>DADO de que el Cliente quiere eliminar su cuenta del sitio web<br><br>CUANDO éste decidido a hacerlo,<br><br>Y complete las verificaciones para ver que sea el usuario de la cuenta,<br><br>ENTONCES al presionar el botón "eliminar cuenta" del apartado de configuración se eliminara su cuenta exitosamente.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 2</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU02</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualización de lista de tipos de suscripción</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Usuario quiere visualizar tipos de suscripciones<br><br>DADO de que el Cliente quiere visualizar los tipos de suscripciones enl sitio web<br><br>CUANDO tiene curiosidad sobre los precios de las suscripciones para usarl sitio web,<br><br>Y complete las acciones para dirigirse al apartado,<br><br>ENTONCES irá al apartado "suscripciones" dentro del sitio web y podrá ver las promociones que tiene el sitio web.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 3</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU03</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualizar actividades del Usuario</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Cliente quiere visualizar sus actividades en el sitio web<br><br>DADO de que el Cliente quiere visualizar sus actividades <br><br>CUANDO se le asignen en las asesorias y/o reuniones<br><br>Y complete las acciones para dirigirse al apartado,<br><br>ENTONCES irá al apartado de "actividades" dentro del sitio web y podrá visualizarlos.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 4</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU04</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Búsqueda por Filtros</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>DADO que soy un usuario que necesita realizar una búsqueda de abogado médico,<br>
    <br>CUANDO selecciono la búsqueda por filtros,<br>
    <br>ENTONCES escojo los parámetros de filtro y la búsqueda será exitosa de acuerdo a lo seleccionado.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 5</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU05</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Suscripción a un plan </td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Suscripción a un plan de usuario<br>
    <br>DADO que soy un usuario que quiere inscribirse en la plataforma MedicDefense,<br>
    <br>CUANDO escojo el tipo de suscripción (mensual o anual) de acuerdo a lo que me beneficie,<br>
    <br>ENTONCES realizaré el pago y podré recibir los beneficios de la suscripción escogida.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 6</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU06</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualización de Perfil de Abogado Médico</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Visualización de perfil<br>
    <br>DADO que soy un usuario que quiere ver los perfiles de los abogados médicos en MedicDefense,<br>
    <br>CUANDO tiene curiosidad sobre los perfiles de los abogados médicos,<br>
    <br>ENTONCES entro a la sección “Perfiles de Abogados” dentro del sitio web y podré visualizar.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 10</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU10</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Diego Flores</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualización de servicios</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Visualizar información sobre los servicios<br>
    <br>DADO que soy un visitante de la landing page,<br>
    <br>CUANDO me encuentre navegando por la landing page,<br>
    <br>ENTONCES encuentro una sección con información acerca de los servicios de MedicDefense.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 11</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU11</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Diego Flores</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Sección de contacto</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como visitante de la landing page de  MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Visualización de una sección de contacto<br>
    <br>DADO que soy un visitante de la landing page,<br>
    <br>CUANDO me encuentre navegando por la landing page,<br>
    <br>ENTONCES encuentro una sección de contacto con campos como nombre, correo, teléfono, mensaje para solicitar información.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 12</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU12</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Diego Flores</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Sección about us</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como visitante de la landing page de  MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Visualización de una sección about us<br>
    <br>DADO que soy un visitante de la landing page,<br>
    <br>CUANDO me encuentre navegando por la landing page,<br>
    <br>ENTONCES encuentro una sección about us que me brinda información acerca de la empresa la cual estoy interesado en sus servicios.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 13</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU13</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Marcelo Rentería</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Verificación de Certificado Médico</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Registro y verificación de certificado médico.<br><br>DADO que quiero registrarme en la plataforma MedicDefense.<br><br>Y rellene los datos necesarios.<br><br>CUANDO suba un archivo de mi certificado médico.<br><br>Y el sistema verifique su veracidad.<br><br>ENTONCES mi cuenta es registrada.<br><br>Y tengo acceso a la plataforma.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 14</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU14</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Marcelo Rentería</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Editar Perfil</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Editar Perfil.<br><br>DADO que ingresé a la plataforma MedicDefense.<br><br>Y esté en el apartado de Perfil.<br><br>CUANDO presione la opción de Editar Perfil.<br><br>Y cambie los datos correspondientes.<br><br>Y presione Guardar Cambios.<br><br>ENTONCES mis datos son cambiados en el sistema.<br><br>Y se refleja en mi perfil.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 15</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU15</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Marcelo Rentería</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Canales de contacto</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Contactar a un abogado.<br><br>DADO que ingresé a la plataforma MedicDefense.<br><br>Y esté en el apartado de Abogado.<br><br>CUANDO presione el botón de Correo.<br><br>Y tenga mi plataforma de correo ingresada en el navegador.<br><br>ENTONCES soy redireccionado a la plataforma.<br><br>Y le mando un correo.</td>
</table>

## 3.3. Impact Mapping

## 3.4. Product Backlog

<table>
    <tr>
        <th>#Orden</th>
        <th>User Story/Technical Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <td>1</td>
        <td>US01</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,necesito poder eliminar mi cuenta en caso sea necesario para no tener vinculo con el sitio web.</td>
    </tr>
    <tr>
        <td>2</td>
        <td>US02</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
    </tr>
    <tr>
        <td>3</td>
        <td>US03</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
    </tr>
       <tr>
        <td>4</td>
        <td>US04</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
    </tr>
    <tr>
        <td>5</td>
        <td>US05</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
    </tr>
    <tr>
        <td>6</td>
        <td>US06</td>
        <td>Visualización de Perfil de Abogado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
    </tr>
    <tr>
        <td>13</td>
        <td>US13</td>
        <td>Verificación de Certificado Médico</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se verifique mi licencia médica para asegurar que sean los médicos quienes se beneficien de los servicios.</td>
    </tr>
    <tr>
        <td>14</td>
        <td>US14</td>
        <td>Editar Perfil</td>
        <td>Como usuario de la plataforma MedicDefense, quiero la opción de editar los datos de mi perfil para reflejar cambios en mis datos registrados.</td>
    </tr>
    <tr>
        <td>15</td>
        <td>US15</td>
        <td>Canales de contacto</td>
        <td>Como usuario de la plataforma MedicDefense, quiero que se muestren los canales de contacto de los abogados para poder contactarlos antes de efectuar un pago.</td>
    </tr>
    
</table>
