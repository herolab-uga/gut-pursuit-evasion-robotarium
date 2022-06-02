# gut-pursuit-evasion-robotarium
Software codes for running the Game-theoretic Utility Tree (GUT) algorithm for the multi-robot Pursuit-Evasion problem in the [Robotarium](https://www.robotarium.gatech.edu/) simulator-hardware multi-robot testbed.

## Experiments Setup
This implementation requires Robotarium Python Simulator.
### Install Robotarium Python Simulator
```
Check the instruction: https://github.com/robotarium/robotarium_python_simulator
```
### Download the Code
```
$ git clone https://github.com/RickYang2016/Gut-Pursuit-Domain-Robotarium-ISR2022.git
```
### Run
1. CB with 1/3/5 Pursuer:
```
pyhton pursuit_game_1/3/5vs1_cb.py 
```
2. PP with 1/3/5 Pursuer:
```
pyhton pursuit_game_1/3/5vs1_pp.py 
```
3. GUT with 1/3/5 Pursuer:
```
cd ~/pursuit_game
pyhton gut_pursuit_game_1/3/5vs1.py 
```
