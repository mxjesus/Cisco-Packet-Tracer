# Información

Objetivo: Terminar la segunda parte del curso con conocimientos más sólidos de los temas vistos en el curso configurando la siguiente topología. 

![alt text](https://github.com/mxjesus/Cisco-Packet-Tracer/blob/main/Temas%20Selectos%20de%20Ingenier%C3%ADa%20en%20Computaci%C3%B3n%20III%20(CCNP)/Topolog%C3%ADa.png?raw=true)

Dentro del archivo 2doFeedback_JJJ.pkt se puede visualizar, con ayuda de Cisco Packet Tracer, los comandos que se utilizaron en cada uno de los equipos Cisco para la implementación de la topología

# Configuración que se realizó

* Protocolo de enrutamiento por RIPv2 y de manera estática.
* Acceso a R4 por Radius y de manera local
* Acceso a R2 por Tacacs y Radius
* Conexión de host a router inalámbrico por medio de Radius
* Configuración de zonas inside, outside y DMZ en ASA
* Configuración de webVPN para que los hosts de outside entren a la página web
* Acceso mediante VPN en Router2 para host de outside
* Acceso a página web mediante el DNS www.eselfingen21.com aplicando NATeo estático con una IP virtual y colocando es IP como DNS en los hosts.
* Servidor syslog funcionando (mandar mensajes desde cualquier dispositivo al servidor).
* Configuración de un IPS en Router 4 denegando el ping
* Configuración de usuarios y vistas en Router 4:
    
    usuario5 -> Nivel 5 de privilegios
    * ping
    * configure terminal
    * hostname
    
    usuario9 -> Nivel 9 de privilegios
    * show running-config
    * interface fastethernet
    * ip address
    
    usuario59 ->Nivel 15 de privilegios
    * Todos los comandos del sistema
    
    usuario3 -> Nivel 3 de privilegios
    * show running-config
    * show ip route
    * show privilege
    
    usuario7 -> Nivel 7 de privilegios
    * configure terminal
    * router rip
    * network (redes para el enrutamiento de rip)
    
    usuario37 -> Nivel 15 de privilegios
    * Todos los comandos del sistema
    
    Vistas
    
    vista1
    * configure terminal
    * ip dhcp pool
    * show ip route
    
    vista2
    * clock set
    * show ip interface brief
    * show clock
    
    vista3
    * show cdp neighbors
    * show version
    * ping
    
    vista4
    * configure terminal
    * logging host
    * logging trap
