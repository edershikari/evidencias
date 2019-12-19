**SERVIDOR FTP**

1. Desde el launch-wizard vamos a añadir el puerto 21.


![](img/FTP/puerto21.png)

Ahora instalamos FTP en el servidor:

![](img/FTP/comando_ftp.png)

Creamos los usuarios cliente,servidor y admin con sus respectivas carpetas:
![](img/FTP/ftp_admin.png)
![](img/FTP/ftp_cliente.png)
![](img/FTP/ftp_servidor.png)

Con el comando nano vamos a modificar el archivo vsftpd.conf:
![](img/FTP/ftp_conf.png)
Reiniciamos el FTP y el apache2:
![](img/FTP/restart_ftp.png)

Ahora abrimos el WinSCP y desactivamos el modo pasivo:
![](img/FTP/ftp_pasivo.png)
Una vez desactivado el modo pasivo , nos podremos conectar con cualquiera de los usuarios: Admin,cliente o servidor mediante la IP elástica.
![](img/FTP/ftp_conectado.png)


