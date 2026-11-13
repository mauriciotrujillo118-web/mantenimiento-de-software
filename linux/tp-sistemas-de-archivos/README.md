# Trabajo Práctico Laboratorio: Exploración del Sistema de Archivos en Linux

- **Materia:** Mantenimiento de Software
- **Estudiante:** Thiago Benjamin Fonseca Perez
- **Fecha de Entrega:** 2026
- **Profesor:** Gabriel Artaza

## 1. Estructura del Árbol de Directorios

- `/etc`: Contiene los archivos de configuración de la mayoría de los programas.
- `/home`: Contiene los archivos personales de los usuarios.
- `/dev`: Contiene archivos que representan partes del hardware, como discos duros y memoria.
- `/var`: Contiene datos como registros de actividad de programas, bases de datos, contenidos del servidor web y copias de seguridad.

![Estructura del árbol de directorios](./assets/01_estructura_directorios.png)

## 2. Sensibilidad a Mayúsculas y Minúsculas

En Linux los nombres de archivos distinguen entre mayúsculas y minúsculas. Por eso `Ejercicio.txt` y `ejercicio.txt` son nombres distintos y pueden estar en la misma carpeta. En Windows, por defecto, ambos se consideran el mismo nombre.

![Sensibilidad a mayúsculas y minúsculas](./assets/02_sensibilidad_mayusculas.png)

## 3. Visualización y Gestión de Archivos Ocultos

Los archivos ocultos sirven para guardar configuraciones y otros datos que utilizan los programas sin llenar de archivos el listado habitual de las carpetas. En Linux, sus nombres comienzan con un punto. Por eso, el archivo creado no aparece con `ls`, pero sí con `ls -la`.

![Visualización y gestión de archivos ocultos](./assets/03_archivos_ocultos.png)

## 4. Buenas Prácticas en Nombres de Archivos

El nombre `tp_sistema_ficheros_2026` cumple con las recomendaciones de la guía porque utiliza letras, números y guiones bajos, sin espacios ni caracteres especiales. En cambio, `TP Sistema de Ficheros (Año 2026)!.doc` contiene espacios, la letra ñ, paréntesis y un signo de exclamación, que la guía recomienda evitar.

![Buenas prácticas en nombres de archivos](./assets/04_buenas_practicas.png)

## 5. Exploración de Dispositivos y Procesos

El directorio `/proc` contiene información temporal sobre los procesos del sistema, es decir, los programas y tareas que se están ejecutando.

![Exploración de dispositivos y procesos](./assets/05_exploracion_proc.png)
