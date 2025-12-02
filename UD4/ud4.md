
## [UD 4 Puertos](../README.md)
### [SS](#1-ss)
### [NMAP](#2-nmap)
### [ARP](#3-arp)
### [WHOIS](#4-whois)

-----

### 1. SS

- `ss -plunt` --> Muestra todos los puertos  tcp y udp que estan escuchando.

  <p align="center"><img src="img/captura1.png" width="800" height="450"></p>

- `ss -ntmp` --> Lista de conexiones tcp con sus puertos y los procesos correspondientes.

  <p align="center"><img src="img/captura2.png" width="800" height="450"></p>

  -----

  ### 2. NMAP

- `nmap -sn ip` --> Realiza un ping para verificar si el host de la ip esta activo.

<p align="center"><img src="img/captura3.png" width="950" height="450"></p>

- `nmap -sn direccion de red/mascara de red` --> Descubre todos los equipos activos de una red.

<p align="center"><img src="img/captura4.png" width="950" height="450"></p>

- `nmap --top-ports 100 -sV ip` --> Analiza los 100 puertos mas comunes del objetivo e intenta determinar la version exacta del servicio que corre en ellos.

<p align="center"><img src="img/captura5.png" width="950" height="450"></p>

  ### 3. ARP

- `arp -a` --> Muestra la tabla arp actual del sistema.

<p align="center"><img src="img/captura6.png" width="950" height="450"></p>

  
  
  ### 4. WHOIS

- `whois` --> Consulta las bases de datos de los registros regionales para revelar datos del objetivo.

<p align="center"><img src="img/captura7.png" width="950" height="450"></p>
