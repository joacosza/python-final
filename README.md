Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

**El PIP (siglas en inglés de "Pip Installs Packages") es una herramienta de línea de comandos utilizada para instalar, actualizar y gestionar paquetes de software escritos en Python. Los paquetes son bibliotecas de código reutilizable que pueden ser utilizadas en proyectos de Python para añadir funcionalidades adicionales sin necesidad de escribir código desde cero.**

**¿Por qué actualizamos PIP?**
**Seguridad: Las versiones más recientes de PIP incluyen parches de seguridad que corrigen vulnerabilidades descubiertas en versiones anteriores. Utilizar una versión desactualizada podría exponer tu entorno a riesgos de seguridad.**

**Compatibilidad: Las nuevas versiones de PIP mejoran la compatibilidad con versiones recientes de Python y otros paquetes. Esto asegura que los paquetes se instalen y funcionen correctamente en tu entorno de desarrollo.**

**Corrección de Errores: Cada actualización de PIP suele incluir correcciones de errores que mejoran su funcionamiento y estabilidad. Actualizar PIP ayuda a evitar problemas conocidos y mejora la experiencia general de uso.**

**Nuevas Funcionalidades: Las actualizaciones de PIP pueden incluir nuevas funcionalidades y mejoras de rendimiento que hacen que la instalación y gestión de paquetes sea más eficiente y fácil.**

**Mejoras en la Documentación: Las versiones más recientes suelen venir con documentación mejorada que facilita la resolución de problemas y el uso de PIP de manera más efectiva.**

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
