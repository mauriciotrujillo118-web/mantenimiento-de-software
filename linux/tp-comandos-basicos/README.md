# TP: Comandos Basicos, Procesos y Utilidades en Linux

* **Materia:** Mantenimiento de Software
* **Estudiante:** Mauricio Cristian Trujillo
* **Fecha de Entrega:** 2026
*  **Profesor:** Gabriel Artaza

## 1. Gestion de Archivos y Directorios

El comando `ls` muestra los archivos y carpetas que no están ocultos. En cambio, `ls -al` también muestra los ocultos y da más detalles, como los permisos, el propietario, el tamaño y la fecha de modificación.

![01_navegacion_archivos](./assets/01_navegacion_archivos.png)


## 2. Monitoreo de Procesos

El comando `ps` muestra los procesos de la terminal actual en ese momento, mientras que `top` muestra los procesos del sistema y actualiza la información en tiempo real. El comando `kill pid` sirve para solicitar el cierre de un proceso cuando un programa queda colgado, reemplazando `pid` por el número que identifica a ese proceso.

![02_procesos_top](./assets/02_procesos_top.png)


## 3. Informacion del Sistema

El comando `uname -a` muestra información del núcleo del sistema, como su nombre, versión y fecha de compilación, además de la arquitectura del equipo. El comando `free` muestra la memoria RAM total, usada y libre, junto con el uso de la memoria de intercambio (swap).

![03_info_sistema](./assets/03_info_sistema.png)


## 4. Red y Espacio en Disco

El comando `ping` sirve para comprobar si hay comunicación con otro equipo en una red TCP/IP. Para hacerlo, envía paquetes de datos y espera una respuesta del destino.

![04_red_espacio](./assets/04_red_espacio.png)
