# PIR_Aaron
Code pour simulation sous Gazebo d'un liDAR et de la voiture TIM07 de l'INSA Toulouse

A ajouter dans les sources du dossier catkin, puis compiler avec ```catkin_make```

lancer avec ```roslaunch velodyne_description example.launch``` (ajouter ```gpu:=true``` pour accélerer si présence d'une carte graphique)

la téléopération est lancée par défaut dans le terminal qui a lancé la commande: 
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

q/z : increase/decrease max speeds by 10%
w/x : increase/decrease only linear speed by 10%
e/c : increase/decrease only angular speed by 10%
anything else : stop

CTRL-C to quit
