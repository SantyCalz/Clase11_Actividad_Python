# Clase 11 Actividad en Python

```sh
# 1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

# 2. Creamos una carpeta o directorio: 
mkdir python-final

#3. Entramos en ella: 
cd python-final

#4. Iniciamos el repositorio:
git init

#5. Creamos un archivo:
touch finales.py

#6. Abrimos VSC:
code .

#7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
python -V
python3 -V

#8. Creamos el entorno virtual en Python:
python3 -m venv venv #Creamos el entorno virtual

#9. Activamos el entorno virtual:
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows

#10. Hacemos actualización del pip de Python
python3 -m pip install --upgrade pip #Actualizamos el pip

#11. Investigar ¿Qué es el pip y porque lo actualizamos?

#12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

#13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
```

## Punto 11 ¿Qué es el pip y porque lo actualizamos?

<sub>pip es el acrónimo de "Pip Installs Packages". Es el sistema de gestión de paquetes estándar para Python, que se utiliza para instalar y gestionar bibliotecas y dependencias de software que no forman parte de la biblioteca estándar de Python.

Actualizar pip es importante porque:

Compatibilidad: Asegura que puedas instalar y utilizar los paquetes más recientes, que pueden no ser compatibles con versiones antiguas de pip.

Nuevas características: Nuevas versiones de pip pueden incluir nuevas funcionalidades que facilitan la gestión de paquetes.

Corrección de errores: Actualizaciones pueden incluir correcciones de errores de versiones anteriores.

Seguridad: Mantener pip actualizado puede proteger tu entorno de vulnerabilidades conocidas.</sub>