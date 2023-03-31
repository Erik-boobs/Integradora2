# Integradora II
[![Contribuidores][contribuidores-shield]][contributors-url]

## contenido
<details>
  <summary>Tabla contenidos</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#objetivos">Objetivos</a>
        </li>
        <li><a href="#organigrama">Organigrama</a></li>
        <li><a href="#diagrama-gantt">Diagrama Gantt</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#requerimientos">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#modelo-relacional">Modelo Relacional</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de Clases</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
      </ul>
    </li>    
    <li>
      <a href="#implementación">Implementación</a>
      <ul>
        <li><a href="#estándares-codificación">Estándares Codificación</a></li>
        <li><a href="#arquitectura">Arquitectura</a></li>
        <li><a href="#código-fuente">Código Fuente</a></li>
      </ul>
    </li>      
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
        <li><a href="#ejecución">Ejecución</a></li>
      </ul>
    </li>       
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
## Acerca del proyecto
Requisitos.

<!-- Descripción -->
### Descripción.
Este proyecto consta del desarrollo de un sistema informático del gimnasio Fitness Center que se ubica en la calle Nayarit #52-B, 37800 Dolores Hidalgo Cuna de la Independencia Nacional, Guanajuato. Que administre y gestione sus servicios. El proyecto tiene como fin desarrollar un sistema que cumpla con ciertas funcionalidades en las cual podemos hablar de que son las de login par a la administración de usuarios como una de productos para la gestión de compra y venta de estos, un registro de ventas, un registro de clientes para su suscripción y un sistema que gestiona las horas de llegada para administrar un gimnasio.
Se planea que el proyecto se realice en un plazo de cuatro meses (enero – abril) o alrededor de 16 a 18 semanas. Como fecha final de entrega el 21 de abril.
Se estima que el costo del desarrollo de este proyecto sea de $30, 720.00 Incluyendo el sueldo de los desarrolladores así como otros costos.


<!-- Objetivos -->
### Objetivos.
#### Objetivos Generales del proyecto.
Nuestro proyecto tiene como propósito principal desarrollar un sistema informático para un gimnasio desde cero, basándonos en las necesidades y requerimientos de la empresa iTTiVA. Cumpliendo con los requerimientos propuestos en la documentación y entregando un sistema completo y funcional en el tiempo estimado.

#### Objetivos Especificos.
Por otro lado, la idea de implementar este tipo de proyecto con estas especificaciones tiene como objetivo aprender y llevarse experiencia y conocimiento que nos aportará herramientas para ser empleadas en un futuro en nuestra carrera profesional.

<!-- Organigrama -->
### Organigrama.
![organigrama](https://user-images.githubusercontent.com/84553507/228033515-0545b171-66be-41d9-a574-5ec755c3f04f.jpg)


<!-- Diagrama Gantt -->
### Diagrama Gantt.
![Gantt](https://user-images.githubusercontent.com/84553507/228038870-0977b2e9-473a-448b-82a1-5bac616af003.png)


<!-- Análisis del proyecto -->
## Análisis de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Requerimientos -->
### Requerimientos.

| Clave de requerimiento |                                                                           Descripción                                                                           |
|:----------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|          RF01          | El sistema permitirá agregar nuevos proveedores                                                                                                                 |
|          RF02          | El sistema permitirá actualizar la información de los proveedores                                                                                               |
|          RF03          | El sistema permitirá eliminar cualquier proveedor por su nombre                                                                                                 |
|          RF04          | El sistema permitirá consultar datos de los proveedores por medio de filtros                                                                                    |
|          RF05          | El sistema aloja la información de los proveedores: Id Proveedor Nombre del Proveedor Teléfono Correo electrónico  Ubicación Productos                          |
|          RF06          | El sistema no permitirá tener registros duplicados (dos proveedores con el mismo nombre)                                                                        |
|          RF07          | Los proveedores se registran con al menos un producto                                                                                                           |
|          RF08          | Los proveedores no podrán tener campos vacíos                                                                                                                   |
|          RF09          | El sistema enviará una notificación cuando se realice una inserción                                                                                             |
|          RF10          | El sistema solo permitirá ingresar a un usuario registrado                                                                                                      |
|          RF11          | El administrador es el único que puede registrar usuarios                                                                                                       |
|          RF12          | El sistema contará con un formulario para registrar usuarios solo si somos el administrador  y podremos ingresar a tal formulario desde una barra de navegación |
|          RF13          | El sistema mostrará los proveedores en una interfaz gráfica donde podremos acceder a su  información o eliminarlo con un botón                                  |
|          RF14          | La información de los proveedores se visualizará en una interfaz gráfica distinta a donde  se encuentran los proveedores                                        |
|          RF15          | El sistema contará con un botón para direccionarnos al formulario para agregar proveedores                                                                      |


<!-- Diagrama de Casos de Uso -->
### Diagrama Casos de Uso.
![Diagrama casos de uso](https://user-images.githubusercontent.com/84553507/228041533-b1d7d486-96fd-4240-8e6a-c99c6b5e7e36.jpg)


<!-- Diseño del proyecto -->
## Diseño de la Solución.
En ésta sección se indicará los artefactos generados en base a la solución.

<!-- Modelo Relacional -->
### Propuesta del modelo de la base de datos.
![coleccion](https://user-images.githubusercontent.com/84553507/228043655-994cc712-7dc4-49ba-9dc5-d4501e72f40f.jpg)

<!-- Diagrama de Clases -->
### Diagrama de Clases.
![Diagrama de clase UML](https://user-images.githubusercontent.com/84553507/228042253-cc5a849f-4fe0-4dbd-81a7-8140bf2214c1.jpg)

<!-- Diagrama de Componentes -->
### Diagrama de Componentes.
![Diagrama de componentes](https://user-images.githubusercontent.com/84553507/228354888-7a418b03-1c74-4af1-9b8e-8032d78ed47e.jpeg)


<!-- Implementación del proyecto -->
## Implementación.
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Estándares de Codificación -->
### Estándares Codificación.
#### Front-End.
* Utilizar HTML5, CSS3 y JavaScript como versiones principales de lenguaje.
* Utilizar los frameworks Angular y Bootstrap.
* Identar el código HTML con dos espacios para mejorar la legibilidad.
* Utilizar atributos alt en las imágenes para mejorar la accesibilidad del sitio.
* Hacer uso de los colores de la plantilla proporcionada por iTTiVA.
* Indentar el código CSS con dos espacios para mejorar la legibilidad.
* Utilizar técnicas de responsive design para asegurar que el sitio se vea bien en diferentes tamaños de pantalla.
* Las pantallas contendras una pantalla de carga al redireccionar a otra.
* Se hara el uso de clases de estilo bootstrap en los componentes.
* Se hara uso de ids para identificar componentes.

#### Back-End.
* Utilizar MongoDB como sistema gestor de base de datos.
* Utilizar Spring Boot.

<!-- Arquitectura MVC y Middleware -->
### Arquitectura.
#### Patrones empleados.
* MVC (Modelo-Vista-Controlador): Este patrón divide la aplicación en tres componentes: el modelo (que maneja la lógica de negocios y la interacción con la base de datos), la vista (que maneja la presentación de la información al usuario) y el controlador (que maneja la interacción entre el modelo y la vista). Se utilizará este patrón para separar de manera clara la presentación, la lógica y la base de datos.

#### Seguridad.
* Autenticación y autorización: Se utilizará autenticación y autorización para garantizar que solo los usuarios autorizados puedan acceder a ciertas partes de la aplicación. Se utilizará una combinación de nombre de usuario y contraseña y tokens de autenticación para manejar la autenticación.

<!-- Código Fuente -->
### Código Fuente.
* [Front-End](https://github.com/ArmandoxxXD/front-end-integradora.git)
* [Back-End](https://github.com/ArmandoxxXD/back-end-integradora.git)


<!-- Pruebas proyecto -->
## Pruebas.
En ésta sección se describe  los artefactos generados en base a la solución.

<!-- Casos de prueba -->
### Casos de prueba.
#### Inicar sesión.
![iniciar](https://user-images.githubusercontent.com/84553507/229186469-a73288d7-4df3-45fd-a7f0-d11ac3941f89.png)

#### Agregar Proveedor.
![agregarProv](https://user-images.githubusercontent.com/84553507/229186605-6dc9e24b-4423-4781-a146-643404afd188.png)

#### Editar Proveedor.
![EditarProv](https://user-images.githubusercontent.com/84553507/229186649-51678c38-c28e-4d0c-8e3d-74e14cf6e659.png)

#### Eliminar Proveedor.
![Eliminarprov](https://user-images.githubusercontent.com/84553507/229186684-2e95f9d2-0602-43cd-9bb5-e058edf5b209.png)

#### Agregar Producto.
![AgregarProd](https://user-images.githubusercontent.com/84553507/229186718-6ef8f07c-55d6-4281-9fde-dc5a1969017e.png)

#### Editar Producto.
![EditarProduc](https://user-images.githubusercontent.com/84553507/229186769-b5e49eec-b380-4d31-9bc0-1d0e7148a486.png)

#### Eliminar Producto.
![Eliminarproduct](https://user-images.githubusercontent.com/84553507/229186844-90c7994e-39d4-409b-bb31-f0e1c468d75a.png)


<!-- Iniciando -->
## Iniciando
Iniciando.

<!-- Requisitos -->
### Requisitos
* Poseer un equipo informático con un sistema operativo windows 10 o windows 11.
* Tener al menos 100GB de almacenamiento libre.
* Tener una memoria RAM de al menos 8GB.
* Estar conectado a una red de internet.
* Tener instalado Node.Js.
* Tener instalado Spring Boot.
* Tener instalado Angular.
* Tener importada la libreria de bootstrap.

<!-- Instalación -->
### Instalacion
Instalación del Software


## Guias
Guias de Uso.

## contribucion
Contribucion.

## Licencia
Licencia.

## Contacto
Contacto.

## Participantes
* [Erik Daniel Méndez Enríquez]()
* [José Armando Gutíerrez Rodríguez]()
* [Julio Samuel Torres Reyes]()
* [Miguel Ánguel Anastacio Nava]()

[contribuidores-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
