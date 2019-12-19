**VIRTUAL HOSTS**

1. En primer lugar, vamos a hacer una copia del archivo 000-default.conf, donde posteriormente cambiaremos las URL y los directorios de los archivos "index.html" tanto en cliente como en servidor.

![](img/VirtualHosts/comandos_cliente.png)

Una vez dentro , cambiamos el Servername y el directorio donde se encuentra nuestro html.

![](img/VirtualHosts/cliente.conf.png)

Ahora deberemos habilitar la URL:
![](img/VirtualHosts/habilitar_url.png)

Este paso lo debemos hacer con el servidor también, cambiando el servername servidor-eder... y el directorio /var/www/servidor. Por ultimo , solo nos queda reiniciar el servidor .
![](img/VirtualHosts/reiniciar_apache.png)

Una vez hayamos completado correctamente los pasos anteriores , deberíamos poder acceder a los index.html mediante las URL que hemos asignado anteriormente.
![](img/VirtualHosts/cliente_url.png)
![](img/VirtualHosts/servidor_url.png)