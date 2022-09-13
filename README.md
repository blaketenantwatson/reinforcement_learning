# reinforcement_learning
Python implementations of value iteration, policy iteration, and Q-learning using pacman simulations

## Description
This project contains numerous files, some of which are not described here.

#### valueIterationAgents.py
Implementation of a value iteration agent for solving MDPs

#### qlearningAgents.py
Q learning agents for pacman and other similar entities

#### analysis.py
A completed analysis of project outcomes

#### mdp.py
General MDP method definitions

#### learningAgents.py
Base classes for learning agents to utilize

#### util.py
A variety of utilites to be used by learning agents

#### gridworld.py
Backing code for the grid playing field for pacman and the ghosts

#### featureExtractors.py
Classes that extract state action pairs, used mainly for the q learning agents

## Executing Code
The base gridworld can be run with
```
python gridworld.py -m
```
There are also a number of options within gridworld.py that can be listed using
```
python gridworld.py -h
```
The test file contains tests for all pacman agent functions, and can be run in its entirety with
```
python autograder.py -q q<number>
```
where \<number\> is a number from 1 to 6. Very specific tests can be run with the '-t' option and any test case found in the 'test_cases' folder.

## Credits
This project was completed as part of CS3600 at the Georgia Institute of Technology, and a significant portion of the code was provided by the teaching staff. All proper credit is given to the GaTech teaching staff and TAs for their portions of the presented code.
