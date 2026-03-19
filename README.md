# Sistema de Gestión de Usuarios

## Descripción
El proyecto consiste en el desarrollo de un sistema de registro de usuarios que permite almacenar, organizar y consultar información de manera estructurada. Su función principal es facilitar el manejo de datos personales, evitando desorden y errores en los registros.

## Motivación
La motivación principal de este proyecto es mejorar la gestión y control de la información de los usuarios mediante un sistema digital organizado. Contar con un registro estructurado permite ahorrar tiempo, evitar duplicidad de datos y mantener la información actualizada.

## Normalizacion
La base de datos se normalizó con el objetivo de organizar mejor la información, evitar datos repetidos y facilitar su mantenimiento. Este proceso permitió mejorar la integridad de los datos y asegurar que cada elemento de información estuviera correctamente estructurado.

Se normalizó para eliminar redundancia, evitar inconsistencias y lograr una mejor organización de la información dentro de la base de datos.

Se separó la información en distintas entidades como Usuario, Rol y Sesión, en lugar de manejar todos los datos en una sola tabla. También se definieron claves primarias para identificar de manera única cada registro.

Se eliminaron datos repetidos y se evitó almacenar información innecesaria en una misma tabla, como el rol dentro de usuario o las sesiones dentro del mismo registro.

Se incorporaron claves foráneas, como id_rol en Usuario e id_usuario en Sesión, para relacionar las tablas entre sí sin duplicar información.

Gracias a la normalización, la base de datos quedó más organizada, sin redundancia y con relaciones claras entre sus entidades.
