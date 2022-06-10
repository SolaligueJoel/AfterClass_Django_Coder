#### AfterClass_Django_Coder
_Repaso general de Django_

# Primeros pasos con Django
_Django es un framwerk de propósito general, que ya tiene muchas funcionalidades añadidas, entre ellas las siguientes_:
* Implementacion de modelo MODELO-VISTA-CONTROLADOR: En Django se pueden diferenciar tres elementos principales:
    * Modelos de datos: están alojados en la base de datos y mapeados con el ORM para ser manipulados como objetos Python.
    * Vistas: guardan toda la lógica de la aplicación. Saben cómo manejar las peticiones de los usuarios, manipular los datos y representarlos de forma           óptima.
    * Controlador: es el encargado de enrutar las peticiones hacia la vista concreta.
    * Nota: este patrón tambien es conocido en Django como MTV (Model-View-Template) haciendo énfasis en la parte que controla eldesarollador,                   dado que el controlador en Django es manejado por el framework en sí. Por tanto, se reemplaza el concepto de controlador y se añade el                     de plantilla (template) que sirve para especificar la logica del renderizado de la información.
  
- Panel de administración: uno de los puntos mas fuertes de Django es que se puede obtener facilmente una interfaz simle y bonita, capaz de modificar cualquier objeto de la base de datos sin necesidad de dedicar tiempo y esfuerzo. desarrollarla para operacion CRUD (Create Read Update Delete).

- Enrutado de URL: el sistema de enrutado de URL de Django permite agregación de nuesas URL según las aplicaciones o modulos instalados. Cada nueva aplicación que se pretenda instalar en una aplicacion Django puede exteneer las rutas que ya haya en el sistema sin afectar a las mismas, lo que tambien permite poder eliminarlas con facilidad.

- Vistas basadas en clases: a difrencia de otros frameworks, Django permite crear vistas basadas en clases, lo que es una gran ayuda; prmite ahorrar tiempo de desarrollo y reutilizar código.

- Soporte de middlewares: es framework consta de una capa de lógica intermedia entre la peticion del usuario y la ejecucion interna del codigo en el framework. Esta capa permite analizar o modificar cualqueir peticion que se haga a la aplicacion web haciendo uso de las denominados middlewares. Son una herramienta ptentisima que permite habilitar o no funcionalidades desde el fichero de configuracion de la aplicacion.

- Gestión y autenticacion de usuarios: este framework soporta el manejo de usuarios por defecto. Esto incluye lo siguiente: creacion, modificacion, autenticacion, manejo de contraseñas, permisos de usuarios, control de sesiones, etc..

- Modularidad de aplicaciones: gracias a la configuraciones que se hace en este framework, las apliaciones son carpetas que pueden ser añadidas o no en la aplicacion principal. Esto hace que activar o desactivar componentes sea muy simple.

- Sistema integrado de renderizado: Django usa el popular sistema de platnillas jinja2 de forma nativa y puede rendereizar objetos simples. colecciones de objetos utlizando bucles o añadir filtros propios que incluso hagan llamadas a la base de datos desde el propio motor de renderizado de paginas web.

- Documentación, robustez y comunidad: uno de los puntos mas fuertes de ser un framework utlizado por muchisimas empresas a lo largo del muno y en muchisimos proyectos profesionales es que la documentacion del codigo es excepecional, la robustez y establidad del codigo es magnifica y, sobre todo, la comunidad que hay alrededor de este framework es de las mejores entre los proyectos de código abierto.


