# PIR_Aaron
Code pour simulation sous Gazebo d'un liDAR et de la voiture TIM07 de l'INSA Toulouse

Ici je suppose que ROS melodic et Gazebo sont installés

A ajouter dans les sources du dossier catkin, puis compiler avec ```catkin_make```

lancer avec ```roslaunch velodyne_description example.launch``` (ajouter ```gpu:=true``` pour accélerer si présence d'une carte graphique)

la téléopération est lancée par défaut dans le terminal qui a lancé la commande: 
l'installation du node de teleop que j'ai utilisé se fait avec ```sudo apt-get install ros-melodic-teleop-twist-keyboard```
Les informations sur son utilisation sont disponibles sur : [http://wiki.ros.org/teleop_twist_keyboard]
