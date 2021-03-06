# Instalación de Python y OpenCV


## Python

Necesitaremos descargar python 2.7 
* [Python 2.7](http://python.org/ftp/python/2.7.5/python-2.7.5.msi) - Web Oficial de python

Sigue las instrucciones para instalar.

Agrega a la variable de entorno PATH la dirección en donde instalaste python


### Gestor de paquetes (PIP)

Es necesario para descargar e instalar las librerías que necesitaremos

Descargar el archivo PY.
* [Pip](https://bootstrap.pypa.io/get-pip.py) - Gestor de Paquetes PIP

Una vez descargado, abrimos una ventana de comandos en la carpeta donde se guardó el archivo y lo instalamos con el comando.


```
python get-pip.py
```

### Instalacion de Numpy con pip

```
python -m pip install numpy
```

### Instalacion de Matplotlib con pip

```
python -m pip install matplotlib
```


## Descargar e instalar OpenCV

1. Descargar la última versión de OpenCV y descomprimir
* [OpenCV](http://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.6/OpenCV-2.4.6.0.exe/download) - sourceforge site

2. Ir a la carpeta ***opencv/build/python/2.7***

3. Copiar **cv2.pyd** a ***C:/Python27/lib/site-packages***.

### Comprobar la instalación

Abrir el IDLE de python y escribe las siguientes líneas

```
1. >>> import cv2
2. >>> print cv2.__version__
```

Si se imprime el resultado sin errores. ¡Felicidades!! Ya tienes instalado el ambiente OpenCV-Python correctamente
