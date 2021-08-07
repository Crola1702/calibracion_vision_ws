# calibracion_vision_ws
Es el workspace donde está guardado el trabajo de visión para el ERC 2021 Maintenance Task

Contiene un solo paquete llamado __calibracion_vision_pkg__

## Dependencias
+ cv_bridge
+ roscpp
+ rospy
+ std_msgs

Para asegurarse de que cv_bridge esté instalado y no genere errores:
```
sudo apt install ros-melodic-cv-bridge
```
## Librerías necesarias de python

Adicionalmente, para que el código funcione de la manera esperada se necesita la librería opencv-contrib, la cual puede instalarse utilizando los siguientes comandos en la terminal:
```
python3 -m pip uninstall opencv-python
python3 -m pip install opencv-contrib-python
```
(Cabe aclarar que el primero de los comandos es obligatorio para evitar conflictos en la librería que impidan su correcta ejecución)
