1. *Una vez estemos conectados al servidor mediante la máquina virtual , lo primero que tendremos que hacer , es un **sudo apt-get update**, para tener actualizada la lista de paquetes para su posterior instalación.*
![](img/apache2/comando_update.png)

2. *Instalamos **Apache2***:
![](img/apache2/comando_apache2.png)

3. *Instalamos **MySQL***:
*Para instalar MySQL , ejecutamos el siguiente comando(Recordad siempre hacer un update antes de instalar algo)*
![](img/MySQL/comando_mysql.png)
*Ahora procederemos con el siguiente comando para configurar nuestro MySQL*
![](img/MySQL/comando_config_mysql.png)

*En primer lugar,nos preguntará si queremos habilitar un plugin para medir la "dureza" de la contraseña,le diremos que si.Ahora tendremos la opción de asignar el grado de dureza de la contraseña, en nuestro caso la pondremos en 'media'*.
![](img/MySQL/dureza_contraseña.png)
*El siguiente paso , será asignarle una contraseña al ROOT:*
![](img/MySQL/contraseña_root.png)
*Deshabilitamos los usuarios anonimos:*
![](img/MySQL/usuarios_anonimos.png)
*Desactivamos el login remoto del ROOT:*
![](img/MySQL/login_remoto_root.png)
*Desactivamos los tests databases:*
![](img/MySQL/test_database.png)
*Y por ultimo, recargamos los privilegios de las tablas:*
![](img/MySQL/reload_tables.png)

4. *Instalamos **PHPmyadmin***:
*Ejecutamos el siguiente comando , y nos preguntará si queremos continuar, pulsamos si:*
![](img/PHPmyadmin/comando_phpmyadmin.png)
*Se abrirá una ventana emergente donde nos preguntará en que tipo de servidor queremos que se instale el PHPmyAdmin , seleccionamos Apache2:*
![](img/PHPmyadmin/seleccionar_apache2.png)
*Al pulsar siguiente , nos preguntará si queremos configurar el phpmyadmin con dbconfig-common , le decimos que si:*
![](img/PHPmyadmin/dbconfig.png)
*Por ultimo , cambiamos el nombre de usuario a root@localhost y asignamos una contaseña:*
![](img/PHPmyadmin/password.png)