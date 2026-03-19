# Sistema de Gestión de Usuarios

## Descripción
El proyecto consiste en el desarrollo de un sistema de registro de usuarios que permite almacenar, organizar y consultar información de manera estructurada. Su función principal es facilitar el manejo de datos personales, evitando desorden y errores en los registros.

## Motivación
La motivación principal de este proyecto es mejorar la gestión y control de la información de los usuarios mediante un sistema digital organizado. Contar con un registro estructurado permite ahorrar tiempo, evitar duplicidad de datos y mantener la información actualizada.

## Normalizacion
La base de datos se normalizó con el objetivo de organizar mejor la información, evitar datos repetidos y facilitar su mantenimiento. Este proceso permitió mejorar la integridad de los datos y asegurar que cada elemento estuviera correctamente estructurado.

-Se normalizó para eliminar redundancia, evitar inconsistencias y mantener la información organizada.

-Se separó la información en entidades como Usuario, Rol y Sesión, y se definieron claves primarias para identificar cada registro.

-Se eliminaron datos repetidos y se dejó de almacenar información innecesaria en una sola tabla.

-Se añadieron claves foráneas para relacionar las tablas sin duplicar información.

Formas normales aplicadas
Se aplicó la Primera Forma Normal (1FN) al usar atributos simples sin repeticiones.
La Segunda Forma Normal (2FN) al asegurar que todos los atributos dependieran de su clave primaria.
La Tercera Forma Normal (3FN) al eliminar redundancia y organizar los datos en tablas relacionadas.

Gracias a esto, la base de datos quedó organizada, consistente y fácil de mantener.
