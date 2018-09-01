# Face Recognition

En este primer encuentro, trabajamos en comenzar a entender el funcionamiento de keras y tensorflow, utilizando Python.

El proyecto consiste en capturar y reconocer caras en imágenes obtenidas de una webcam. 

## Requerimientos

### IMPORTANTE!

Necesitamos correr la version de Python 3.6.x (no la 3.7 porque tensorflow-gpu no estaría disponible).

Si necesitan hacer un downgrade, desde el Anaconda navigator pueden hacerlo:

![Alt text](python-version-change.png?raw=true "Change Python Version")

Si están utilizando Visual Studio Code pueden hacerlo en la barra inferior, cambiando el compilador:

![Alt text](python-version.png?raw=true "Change Python Version")

Luego debemos verificar que estamos utilizando una versión actualizada de pip, ejecutando el siguiente comando:

```python
python -m pip install --upgrade pip
```

Hemos dejado un archivo "requirements.txt", donde figuran todos los requerimientos necesarios para ejecutar el programa en "main.py".

Para instalar automáticamente los requerimientos, ejecuten en la consola el siguiente código:

```python
pip install -r requirements.txt
```
