

# Calculadora_
Repositorio que contiene una calculadora básica basada en multiservicios  utilizando php como entorno web y apache como motor

# Instalación
Se deben descargar los archivos y guardarlos en una misma carpeta, además como prerequisito se debe tener instalado docker, para linux
la forma de instalarlo es siguiendo los siguientes comandos.

$ sudo apt-get update

$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
   
$ sudo apt-get update

$ sudo apt-get install docker-ce docker-ce-cli containerd.io

# Instrucciones de Uso

* Correr la aplicación
En la terminal de Linux se coloca los comandos para acceder a la ubicación
$cd documentos/aplicacion
* Cuando ya se está en la ubicación se coloca escribe
$ docker compose-up

* Docker
Para iniciar el docker se coloca el siguiente comando

$ sudo dockebuild -t gestion:latest .

$ sudo docker start calculadora


# Construido con
* PHP
* html
* docker
* Apache 7
