
## [UD 4 Puertos](../README.md)
### [TCPDUMP](#1-tcpdump)
### [TCPTRACK](#2-tcptrack)
### [IPTRAF](#3-iptraf)
### [BMON](#4-bmon)

-----

### 1. SS

- `ss -plunt` --> Captura los paquetes y vuelca el trafico de red para analizarlo.

  <p align="center"><img src="img/captura1.png" width="800" height="450"></p>

- `ss -ntmp` --> Captura los paquetes y vuelca el trafico de red para analizarlo.

  <p align="center"><img src="img/captura2.png" width="800" height="450"></p>

  -----

  ### 2. NMAP

- `nmap -sn ip` --> Monitoriza a tiempo real las conexiones tcp, de manera detallada.

<p align="center"><img src="img/captura3.png" width="950" height="450"></p>

- `nmap -sn direccion de red/mascara de red` --> Monitoriza a tiempo real las conexiones tcp, de manera detallada.

<p align="center"><img src="img/captura4.png" width="950" height="450"></p>

- `nmap --top-ports 100 -sV ip` --> Monitoriza a tiempo real las conexiones tcp, de manera detallada.

<p align="center"><img src="img/captura5.png" width="950" height="450"></p>

  ### 3. ARP

- `arp -a` --> Genera un menú con estadisticas detalladas de trafico ip, udp y tcp por puertos.

<p align="center"><img src="img/captura6.png" width="950" height="450"></p>

  
  
  ### 4. WHOIS

- `whois` --> Monitoriza el ancho de banda y visualiza el trafico con graficos.

<p align="center"><img src="img/captura7.png" width="950" height="450"></p>
