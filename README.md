# PIR_Aaron
Code pour simulation sous Gazebo d'un liDAR et de la voiture TIM07 de l'INSA Toulouse

Ici je suppose que ROS melodic et Gazebo sont installés

* L'installation du node de teleop que j'ai utilisé se fait avec ```sudo apt-get install ros-melodic-teleop-twist-keyboard```
  * Les informations sur son utilisation sont disponibles sur : http://wiki.ros.org/teleop_twist_keyboard

* Cloner ce repo dans les sources du dossier catkin, puis compiler avec ```catkin_make```

* Modifier le path des modèles de gazebo pour pouvoir charger le circuit: ```export GAZEBO_MODEL_PATH=~/<path>/PIR_Aaron/velodyne_plugin_v3/velodyne_description/world:${GAZEBO_MODEL_PATH}```

* Lancer avec ```roslaunch velodyne_description example.launch``` (ajouter ```gpu:=true``` pour accélerer si présence d'une carte graphique)

La téléopération est lancée par défaut dans le terminal qui a lancé la commande


