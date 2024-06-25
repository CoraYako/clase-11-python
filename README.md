## Clase 11 (Python) 24 de Junio del 2024
Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en ``Linux``, debe ser como administrador en ``Window``
2. Creamos una carpeta o directorio: ``mkdir python-final``
![Ejecución del paso 1 y 2](/images/pasos_1_y_2.png)
3. Entramos en ella: ``cd python-final``
4. Iniciamos el repositorio: ``git init``
![Ejecución del paso 3 y 4](/images/pasos_3_y_4.png)
5. Creamos un archivo: __(Linux)__ ``touch finales.py`` __(Windows)__ `ni finales.py`
![Ejecución del paso 5](/images/paso_5.png)
6. Abrimos VSC: code .
![Ejecución del paso 6](/images/paso_6.png)
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada: ``python -V`` o ``python3 -V``
8. Creamos el entorno virtual en Python: ``python3 -m venv venv``
9. Activamos el entorno virtual: __(Linux)__ ``source venv/bin/activate`` __(Windows)__ ``venv/scripts/activate``
10. Hacemos actualización del pip de Python: ``python3 -m pip install --upgrade pip``
![Ejecución de los pasos 7, 8, 9 y 10](/images/pasos_7_8_9_y_10.png)
11. Investigar ¿Qué es el pip y porque lo actualizamos?

    Pip es el gestor de paquetes oficial para Python. Permite instalar, actualizar y desinstalar paquetes y bibliotecas que se encuentran en el Python Package Index (PyPI), un repositorio en línea que contiene una amplia colección de software desarrollado por la comunidad para Python.

    __Funciones Principales de pip:__

    - Instalar Paquetes: Descarga e instala paquetes de PyPI u otros repositorios especificados.
    - Actualizar Paquetes: Actualiza los paquetes instalados a sus versiones más recientes.
    - Desinstalar Paquetes: Elimina paquetes instalados.
    - Listar Paquetes Instalados: Muestra una lista de todos los paquetes instalados en el entorno.
    - Mostrar Información de un Paquete: Muestra detalles sobre un paquete específico.
    
    __¿Por Qué Actualizamos pip?__
    
    Actualizar pip es importante por varias razones:
    - Mejoras y Nuevas Funcionalidades: Las actualizaciones de pip a menudo incluyen nuevas características que facilitan la gestión de paquetes.
    - Corrección de Errores: Las actualizaciones corrigen errores y problemas conocidos en versiones anteriores de pip, mejorando la estabilidad y confiabilidad del gestor de paquetes.
    - Compatibilidad: Las nuevas versiones de pip pueden incluir mejoras de compatibilidad con nuevas versiones de Python y otros paquetes.
    - Seguridad: Las actualizaciones pueden incluir parches de seguridad que protegen el entorno de desarrollo contra vulnerabilidades.
    
    __Conclusión__

    Pip es una herramienta esencial para cualquier desarrollador de Python, facilitando la instalación y gestión de paquetes. Mantener pip actualizado es crucial para aprovechar las últimas mejoras, corregir errores y garantizar la seguridad y compatibilidad del entorno de desarrollo.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que se fue mostrando en comandos, y las respuesta del punto 11.