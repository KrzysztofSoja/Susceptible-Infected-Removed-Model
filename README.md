# Susceptible-Infected-Removed Model

This model is simple simulation of pandemic. In this simulation we have three type of people: susceptible - it's person who can be infected, infected and removed, who represent dead or cured unit.

Infected person can infect other susceptible people in neighborhood radius with some probability (in code it calls probability of contagion). In every move every infected unit can be change our state to removed with some probability (in code it calls probability of death).

In simulation every unit make Brownian motion (https://en.wikipedia.org/wiki/Brownian_motion) in every step.

This work is inspired, by: https://www.youtube.com/watch?v=gxAaO2rsdIs. Thank you :)

You can see the result of the simulation in the video below. Each frame in the video corresponds to one step in the simulation. A susceptible person is represented by a blue dot, an infected person by a red dot, and a removed person by a black dot.

[![Watch the video](https://github.com/KrzysztofSoja/Susceptible-Infected-Removed-Model/blob/master/pandemic_step.png)](https://youtu.be/-t2xeYIK8HY)
