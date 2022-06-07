## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)



- Garantizar el adecuado funcionamiento de las bases de datos.
Cuando se manejan grandes cantidades de datos, el administrador debe asegurarse que la información se actualice constantemente y sea eficiente al realizar una búsqueda.


- Respaldo de la información.
Los datos deben estar simepre disponibles para consultarlos, para conseguir esto, deberán realizarse copias de seguridad de la información con cierta periodicidad.


- Protección ante riesgos.
También deben considerarse posibles amenazas externas como virus y hackeo que pongan en riesgo la información; el administrador de bases de datos deberá detectar y proteger alguna potencial pérdida de información.


- Resolver pérdida de datos.
Si ocurre algún incidente que elimine los datos, se deberá restablecer inmediatamente la información y detectar la causa del fallo.


- Acceso restringido a los datos.
No toda la información debe estar disponible a todo usuario, se requiere un permiso especial dependiendo de la función del usuario.

 



2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)


3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)

4. ¿Qué es un Sistema de Información? (valor 1.5)

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.




# Diagrama entidad - relación 


Sucursales: domicilio, teléfono y un código de sucursal.

Empleado: nombre, apellidos, NIF y teléfono.

revistas: título, número de registro, periodicidad y tipo.

periodistas: nombre periodista, apellidos periodista , NIF periodista y teléfono periodista.

Secciones: título y una extensión.

revista: fecha, número de páginas y el número de ejemplares vendidos.




![Modelo relacional - bd editorial](https://user-images.githubusercontent.com/104279978/170846080-64e5b61a-edc4-48a5-8050-cc21b1184d9b.jpg)


# Código de la  Base de datos


https://www.db-fiddle.com/f/bSm7FhX5VnCJ6Gu2H4d55t/2
