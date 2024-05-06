# WITMOTION_IMU HWT901 B-TTL

La información necesaria se puede encontrar en el siguiente enlace:

https://github.com/ElettraSciComp/witmotion_IMU_ros?tab=readme-ov-file


## INSTALACIÓN


    sudo apt-get install libqt5serialport5-dev

    cd rr_ros_ws

    git clone --recursive https://github.com/ElettraSciComp/witmotion_IMU_ros.git src/witmotion_ros

    catkin_make



## USO DIARIO

    roslaunch witmotion_ros witmotion.launch

Los datos captados por el sensor se pueden ver en rviz. Una vez abierto rviz (escribir rviz en el terminal), en la paleta de la izquierda seleccionar en Fixed Frame la opción *imu*. Después, pulsamos en la opción *Add*, *By topic* y añadimos *imu*. 

Ya se debería poder ver una flecha que representa la orientación del sensor.

## Otros enlaces de referencia

https://www.wit-motion.com/proztmz/38.html

https://github.com/ElettraSciComp/witmotion_IMU_QT?tab=readme-ov-file



# PROBLEMAS USUALES

## CONEXIÓN DEL SENSOR

El conversor USB del sensor tiene 4 cables que se pueden conectar de diferentes maneras indicadas en la hoja de instrucciones que viene en la caja. Para nuestro sensor modelo HWT901B-TTL, la forma correcta de conectarlo es la configuración TTL:


<img src="https://github.com/RoboRescueUMA/Autonomia_WitMotion_IMU/blob/main/IMAGES/TTL.jpg" align="center">



