# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se resume toda la información recopilada, analizando el codigo que utilizamos y la arquitectura y principios de ingenieria que empleamos a lo largo de nuestro trabajo

### 5.1.1. Software Development Environment Configuration

En la siguiente sección se describe la ruta de referencia de cada uno de los productos de software para que cualquier miembro del equipo pueda desarrollar cada punto del trabajo.

- **UXPressia:** Plataforma que nos permitirá crear los user stories y tambien poderemos realizar múltiples mapas para evaluar sus prioridades y una serie de opciones que nos aportan al aspecto grafico de nuestro trabajo.
- **Figma:** Herramienta colaborativa que nos permitirá desarrollar lo respectivos wireframes y mockups de nuestra landing page.
- **Vertabelo:** Plataforma que nos permitirá crear nuestro diagrama de base de datos.
- **LucidChart:** Aplicación web destinada a la elaboración de Wireflows, Lean UX Canvas, User Flows y diagramas de clases.
- **GitHub:** Repositorio colaborativo en la nube.
- **Visual Studio Code:** Entorno de desarrollo.
- **GitHub Pages:** Plataforma que permite hacer deployments sencillos y rapidos para nuestra páginas web.
- **HTML5:** Lenguaje para elaboración de nuestra página web.
- **CSS3:** Tecnología para darle variados estilos a nuestra página web.
- **Javascript:** Lenguaje de programación orientado a objetos, que nos sirvió para implementar funcionalidades en nuestra Landing Page.

### 5.1.2. Source Code Management

Trabajamos con tres ramas principales:

- Main: nuestra rama principal donde presentaremos nuestras
publicaciones oficiales.
- Branch: Se descompone en ramas por cada feature trabajado, diviendose asi en cada chapter correspondiente del 1 al 5.

### 5.1.3. Source Code Style Guide & Conventions

Para desarrollar nuestro proyecto hemos requerido de algunas nomenclaturas, referencias y lenguajes para esta solución.
<br>

- **Tecnologías:** Utilizamos tecnologías básicas como HTML5, CSS y JavaScript para el desarrollo web.

- **Herramientas:** Nos apoyamos en herramientas populares como Visual Studio Code, GitHub, Figma y WebStorm para facilitar el desarrollo y la colaboración en el proyecto.

- **Convenciones de Idioma:** Optamos por utilizar el inglés en todo nuestro código, incluyendo la Landing Page, para mantener la coherencia y facilitar la comunicación y colaboración con otros desarrolladores y usuarios.

### 5.1.4. Software Deployment Configuration

En la siguiente sección se explicará cómo se realizó la
implementación de nuestra landing page en la plataforma de
GitHub

1) Establecemos un repositorio remoto en GitHub como el centro de nuestro proyecto.
2) Inicializamos el repositorio usando el comando “git init”
3) Añadimos el repositorio remoto y subimos los archivos a la nube de GitHub.
4) Configuramos GitHub Pages en la sección de configuración del repositorio en GitHub.
5) Accedemos a la URL proporcionada por GitHub Pages para verificar que nuestra página web se haya desplegado correctamente.

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

### 5.2.1.2. Sprint Backlog 1

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
  </tr>
  <tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1"> Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status(To-do /InProcess /To-Review /Done)</td>
</tr>
  <tr>
    <td colspan="1">2</td>
    <td colspan="2">Visualización de lista de tipos de suscripción</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir funcion para mostrar lista de tipos de suscrpción</td>
    <td colspan="3">Como visitador del landing page de MedicDefense,quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
    <td colspan="1">1</td>
    <td colspan="2">Fabricio</td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1"></td>
    <td colspan="2">Sección de Creadores</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir funcion para mostrar los creadores de la empresa</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
    <td colspan="1">1</td>
    <td colspan="2">Cesar</td>
    <td colspan="1">Done</td>
<tr>
    <td colspan="1">10</td>
    <td colspan="2">Visualización de servicios</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir sección de servicios</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
    <td colspan="1">1</td>
    <td colspan="2">Marcelo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">11</td>
    <td colspan="2">Sección de contacto</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir sección de contacto</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
    <td colspan="1">1</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">12</td>
    <td colspan="2">Sección nosotros</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir sección nosotros</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección nosotros para informarme sobre la empresa que está brindando los servicios.</td>
    <td colspan="1">1</td>
    <td colspan="2">Marcelo</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1"></td>
    <td colspan="2">Sección de inicio</td>
    <td colspan="1"></td>
    <td colspan="2">Añadir sección de inicio</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
    <td colspan="1">1</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
</tr>
</table>

### 5.2.1.3. Development Evidence for Sprint Review

### 5.2.1.4. Testing Suite Evidence for Sprint Review

### 5.2.1.5. Execution Evidence for Sprint Review
Para esta primera entrega, nuestro equipo a conseguido elaborar la Landing Page del proyecto "MedicDefense". De tal modo, se podrá visualizar la información necesaria de lo que ofrece nuestro proyecto.

![alt text](../assets/imgs/header.png)
![alt text](../assets/imgs/nosotros.png)
![alt text](../assets/imgs/servicios.png)
![alt text](../assets/imgs/planes.png)
![alt text](../assets/imgs/contactanos.png)
![alt text](../assets/imgs/footer.png)

### 5.2.1.6. Services Documentation Evidence for Sprint Review

### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el despliegue del Landing Page, hemos utilizado la herramienta de Github Pages para poder hacer un deployment. Para eso, hemos creado un repositorio donde hemos colocado el código de desarrollo de nuestra Landing Page.

![alt text](<../assets/imgs/github-repositorio.PNG>)

Una vez creado el repositorio, entraremos a configuración del repositorio y escogemos el apartado de Pages. Se coloca la información necesaria, como la fuente del branch a utilizar para realizar el deployment. Luego de eso, Github Pages nos brindará el link y desplegará nuestra landing page en la Web.

![alt text](<../assets/imgs/github-pages.PNG>)


### 5.2.1.8. Team Collaboration Insights during Sprint
- Tuesta, P(2023). *Existe un déficit de 2417 médicos anestesiólogos en 20 regiones del país*. Convoca.pe. Recuperado de: https://convoca.pe/agenda-propia/existe-un-deficit-de-2417-medicos-anestesiologos-en-20-regiones-del-pais

- Conne, M(2024). *The Markdown Guide*. MarkdownGuide. Recuperado de: https://www.markdownguide.org/
