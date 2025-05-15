# parte 1: instalacion

1. creamos la maquina virtual para pone el owncloud

![Mi Foto](1.png)

2. Actualizar el sistema: Se actualizan las listas de paquetes disponibles y se actualizan todos los paquetes del sistema a las versiones más recientes.

![Mi Foto](2.png)

3. Instalar requisitos previos de PPA: Se instalan las herramientas necesarias para trabajar con repositorios PPA (Personal Package Archives).

<img src="/fotos/primera parte/3.png"alt="3"> ![Mi Foto](3.png)

4. Agregar repositorio PPA de PHP: Se agrega un repositorio que contiene las versiones más recientes de PHP, incluida la versión 7.4.

<img src="/fotos/primera parte/4.png"alt="4"> ![Mi Foto](4.png)

5. Instalar PHP 7.4: Se instala el paquete básico de PHP 7.4

<img src="/fotos/primera parte/5.png"alt="5"> ![Mi Foto](5.png)

6. Instalar librerías adicionales de PHP:Se instalan varias librerías adicionales de PHP 7.4 que pueden ser necesarias para diferentes aplicaciones, como:

    Módulo de Apache2 para PHP 7.4
    Servidor de FastCGI de PHP 7.4
    Librerías comunes de PHP 7.4

<img src="/fotos/primera parte/6.png"alt="6"> ![Mi Foto](6.png)

7. Seleccionar versión de PHP: Se selecciona la versión de PHP que se quiere utilizar como predeterminada.

<img src="/fotos/primera parte/7.png"alt="7"> ![Mi Foto](1.png)

8. Activar módulos de Apache2: Se activan los módulos de Apache2 necesarios para PHP 7.4, como el módulo de FastCGI y la configuración de PHP-FPM.

<img src="/fotos/primera parte/8.png"alt="8">![Mi Foto](1.png)

9. Reiniciar Apache2: Se reinicia el servidor Apache2 para aplicar los cambios y asegurarse de que todo esté funcionando correctamente.

<img src="/fotos/primera parte/9.png"alt="9">![Mi Foto](1.png)


<img src="/fotos/primera parte/10.png"alt="10">![Mi Foto](1.png)


# parte 2: instalacion de apache 2.0

11. Actualizar lista de paquetes: Se actualiza la lista de paquetes disponibles en el sistema para asegurarse de que se tienen las versiones más recientes.

<img src="/fotos/segunda parte/11.png"alt="11">![Mi Foto](1.png)



12. Actualizar paquetes: Se actualizan todos los paquetes del sistema a las versiones más recientes para asegurarse de que se tienen las últimas mejoras y correcciones de seguridad.

<img src="/fotos/segunda parte/12.png"alt="12">![Mi Foto](1.png)



13. Instalar servidor web Apache2: Se instala un servidor web que permite servir contenido web a los usuarios.

<img src="/fotos/segunda parte/13.png"alt="13">![Mi Foto](1.png)



14. Instalar servidor de bases de datos MySQL: Se instala un servidor de bases de datos que permite almacenar y gestionar datos de manera eficiente.

<img src="/fotos/segunda parte/14.png"alt="14">![Mi Foto](1.png)



15. Instalar PHP y módulo Apache2: Se instala el lenguaje de programación PHP y se configura para trabajar con el servidor web Apache2.

<img src="/fotos/segunda parte/15.png"alt="15">![Mi Foto](1.png)



16. Instalar librerías adicionales de PHP: Se instalan varias librerías adicionales de PHP que pueden ser necesarias para diferentes aplicaciones, como procesamiento de imágenes, conexiones a bases de datos, etc.

![Mi Foto](15.png)



17. Reiniciar servidor Apache2: Se reinicia el servidor web para aplicar los cambios y asegurarse de que todo esté funcionando correctamente.

![Mi Foto](16.png)



18. Acceder a la consola de MySQL: Se accede a la consola de MySQL para gestionar la base de datos.

![Mi Foto](17.png)



19. Crear base de datos: Se crea una nueva base de datos para almacenar datos.

![18](18.png)

20. Crear usuario: Se crea un nuevo usuario de MySQL con acceso a la base de datos.

![19](19.png)


21. Dar privilegios al usuario: Se da al usuario acceso total a la base de datos para que pueda realizar operaciones de lectura y escritura.

![20](20.png)


![24](24.png)


22. Salir de la base de datos: Se sale de la consola de MySQL después de configurar la base de datos y el usuario.

![20](20.png)


23. Se copia un archivo comprimido (app-web.zip) al directorio raíz del servidor web.

![21](21.png)


24. Se cambia el directorio actual al directorio raíz del servidor web.

![21](21.png)


25. Se descomprime el archivo comprimido en el directorio actual, extrayendo los archivos y directorios contenidos en él.

![23](22.png)


26. Se elimina un directorio específico (app-web/) y todo su contenido. Se elimina el archivo index.html predeterminado del directorio raíz del servidor web.

![24](23.png)


27. Se cambian los permisos del directorio y sus contenidos para permitir que el propietario tenga control total y otros usuarios puedan leer y ejecutar archivos. Se cambia el propietario del directorio y sus contenidos a un usuario específico y al grupo del servidor web, para que el servidor pueda acceder a los archivos y directorios.

![25](25.png)

