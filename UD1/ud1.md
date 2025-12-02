## [UD 1 PROCESOS](../README.md)
### [PS](#1-ps)
### [TOP](#2-top)

-----

### 1. PS

- `ps` --> Muestra información básica de los procesos que se estan ejecutando.

<p align="center"><img src="img/captura8.png" width="800" height="350"></p>

- `ps au` --> Muestra los procesos de los usuarios de forma detallada.

<p align="center"><img src="img/captura1.png" width="800" height="350"></p>

- `ps aux` --> Muestra una vision global de todos los procesos del sistema.

<p align="center"><img src="img/captura2.png" width="800" height="350"></p>

- `ps -eo user,pid,%cpu,comm|head -n 6` --> Muestra los procesos con las columnas que se indican, de manera personalizada.

  <p align="center"><img src="img/captura7.png" width="800" height="350"></p>

  -----

  ### 2. TOP

- `top` --> Muestra en tiempo real y de forma dinamica los procesos ordenados por consumo de recursos.

**<p align="center"><img src="img/captura4.png" width="800" height="350"></p>

- `top -b -n 3 >top.info` --> Ejecuta top en modo batch(El modo batch hace que la salida del comando sea en texto plano) por 3 iteraciones y las guarda en un fichero llamado info.top.

<p align="center"><img src="img/captura5.png" width="800" height="350"></p>

- `htop` --> Version interactiva y mas visual de top.

<p align="center"><img src="img/captura6.png" width="800" height="350"></p>

- `atop` --> Muestra la carga de cpu, memoria, disco y red del equipo.

<p align="center"><img src="img/captura1_1.png" width="800" height="350"></p>
