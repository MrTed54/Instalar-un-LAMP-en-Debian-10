# Instalar-un-LAMP-en-Debian-10
	Nesesitamos instalar lo siguiente
		Apache2
		Mysql o MariaDB
		PHP, Dependencias de PHP
#
# Proceso de instalacion

# Instalar Apache2

sudo apt install apache2

![instalarapache](https://user-images.githubusercontent.com/35048921/79944166-75ed3d00-8430-11ea-9127-37d470ba13fb.png)
#
una vez terminada la instalacion tenemos que verificar si esta bien instalado apache tenemos que entrar a nuestro navegador como google o firefox el de nuestro gusto y entrar a localhost y nos aparecera una pantalla como la siguiente

![verificarApache](https://user-images.githubusercontent.com/35048921/79946007-b8b11400-8434-11ea-98d9-1d2a9164405e.png)
#
# Instalar PHP7

sudo apt-get install python-software-properties

sudo add-apt-repository ppa:ondrej/php

sudo apt-get update

sudo apt-get install php7.0

php -v
#
