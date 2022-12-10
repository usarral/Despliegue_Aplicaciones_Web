# Tarea Despliegue 02_Respaldando_La_Web

## 01. Accedo a mi carpeta en donde tengo los archivos estáticos de la web

![Imagen_cd](01.png)

## 02. Para simplificar el acceso, creo una configuración en el archivo config de ssh

![Imagen_sshConfig](02.png)

## 03. Me conecto al servidor por sftp y como tengo para identificación configurada mi clave SSH me pide mi contraseña del archivo de identificación

![Imagen_ftpConn](03.png)

## 4. Usando mput, del protocolo ftp, subo la carpeta a mi carpeta personal del servidor

![Imagen_ftpUpload](04.png)

## 5. Ahora me conecto por SSH para instalar apache y poner la carpeta en su lugar indicado para que apache pueda cargarla (me conecto usando el alias de mi archivo config)

![Imagen_sshConn](05.png)

## 6. Instalo el paquete apache2

![Imagen_apt](06.png)

## 7. Muevo mi archivo a la ruta de los archivos de apache2

![Imagen_mv](07.png)
![Imagen_mv2](08.png)

## 8. Ahora defino los permisos de forma que el propietario quede www-data para evitar problemas de permisos

![Imagen_chmod](09.png)

## Con esto ya si entro en el navegador a la URL de la pagina ya carga desde el servidor apache

![Imagen_chrome](10.png)
