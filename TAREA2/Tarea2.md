
# Tarea de Configuracion de Rango de servidores en Debian

##  Instalacion del servidor DHCP. 
Empezaremos entrando en nuestro Debian Server e instalaremos nuestor Servidor ssh 
para esto aremos nuestro apt-update para conseguir la informacion de los paquetes 

![Imagen realizada masTarde.1](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/SIR%201%20UPDATE.PNG)

Tras esto instalaremos el paquete y la configuracion de este se hara mas tarde

![Imagen realizada masTarde.2](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/Sir%202.PNG)



## Configuracion de las Tarjetas red 
Aquí procedo a hacer la configuracion de las tarjetas red para que este de acuerdo con el esquema 

Red:

![1](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/1.png)

PFsense:

![2](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/2.png)

Servidor Debian:

![3](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/3.png)

Cliente Debian:

![4](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/4.png)

Cliente Windows:

![5](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/5.png)


## Configuración del Rango Del server Debian
Aquí tendremos que ir al documento del rango del server de Debian
y lo configuraremos como tal 
![6](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/6.png)

Arriba pondremos la configuración del rango
en la cual pondremos el rango pedido el cual esta entre el 10.0.13.3-10.0.13.100 
los dominios son los especificados (el del instituto y el de google)
la ip del router tambien insertaremos el lease-time el cual sera nuestro tiempo medio en el cual la duracion de la ip  
y la maxima.

Abajo tendremos la reserva del cliente de Linux
en este caso la he llamado U-Angel.

Esta tendrá la ip 60

***Comprobación de que el servidor halla dado las IP's correctas***

![7](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/7.png)

![8](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/8.png)

## IP que estan siendo utilizadas al momento
Aqui podemos ver las ips dadas a otros sistemas al momento 

![9](https://github.com/HerreraAngel/RSI/blob/main/TAREA2/IMGS/9.png)

