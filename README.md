# Labiratorio ciberfisico: homework 2

## Composizione gruppo
_ Dimo Eldison: creazione mappa ed esecuzione della simulazione<br>
_ Vicario Rudy: creazione mondo Gazebo<br>

## Descrizione progetto
L'obiettivo di questo homework è la creazione di un mondo virtuale in Gazebo in cui poter far muovere il modello simulato di un TurtleBot3.<br>
Come scenario abbiamo scelto di ricostruire il laboratorio Altair presente nel dipartimento di Informatica (Ca' Vignal 2).<br>
[foto del lab]

## Istruzioni per la compilazione
1. Scaricare il ROS package TurtleBot3 Simulation per poter simulare TurtleBot3 sul proprio PC<br>
```console
$ cd ~/catkin_ws/src
$ git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
$ cd ~/catkin_ws
$ catkin_make
```
2. Clonare questa repository ed avviare lo script "setup.sh"<br> 
```console
$ cd ~/catkin_ws/src
$ git clone https://github.com/rudyvic/lab_ciber_homework2.git
$ cd lab_ciber_homework2
$ ./setup.sh
$ cd ~/catkin_ws
$ catkin_make
```

## Istruzioni per l'esecuzione
1. Aprire un nuovo terminale e digitare
```console
$ export TURTLEBOT3_MODEL=waffle
$ roslaunch turtlebot3_gazebo turtlebot3_altair.launch
```
2. Aprire un nuovo terminale e digitare
```console
$ export TURTLEBOT3_MODEL=waffle
$ roslaunch turtlebot3_gazebo turtlebot3_simulation.launch
```

