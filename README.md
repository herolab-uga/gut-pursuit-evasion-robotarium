# gut-pursuit-evasion-robotarium
Software codes for running the Game-theoretic Utility Tree (GUT) algorithm for the multi-robot Pursuit-Evasion problem in the [Robotarium](https://www.robotarium.gatech.edu/) simulator-hardware multi-robot testbed.

## Experiments Setup
This implementation requires Robotarium Python Simulator.

### Install Robotarium Python Simulator 
Use the original source below and make sure you install it as per their instructions
```
Check the instruction: https://github.com/robotarium/robotarium_python_simulator
```

### Download this GUT-Pursuit repository's Code
```
$ git clone https://github.com/herolab-uga/gut-pursuit-evasion-robotarium.git
```

### To Run the simulations and algorithms
1. Contant Bearing (CB) pursuit strategy with 1/3/5 Pursuers (to capture 1 evader):
```
pyhton pursuit_game_1/3/5vs1_cb.py 
```
2. Pure Pursuit (PP) strategy with 1/3/5 Pursuers (to capture 1 evader):
```
pyhton pursuit_game_1/3/5vs1_pp.py 
```
3. Cooperative Game-theoretic Utility Tree (GUT) based pursuit strategy with 1/3/5 Pursuers (to capture 1 evader):
```
cd ~/pursuit_game
pyhton gut_pursuit_game_1/3/5vs1.py 
```


## Core contributors

* **Qin Yang** - Ph.D. student

* **Dr.Ramviyas Parasuraman** - Lab Director


## Heterogeneous Robotics (HeRoLab)

This project is a part of a Learning Technology Grant (LTG) project at the Heterogeneous Robotics Research Lab (HeRoLab) of the University of Georgia.

Please contact hero at uga . edu for any queries

http://hero.uga.edu/

<p align="center">
<img src="http://hero.uga.edu/wp-content/uploads/2021/04/herolab_newlogo_whitebg.png" width="300">
</p>



