# Philosophers

Eat, Sleep, Spaghetti, repeat. </br>
This project is about learning how threads work by precisely timing a group of philosophers on when to pick up forks and eat spaghetti without dying from hunger. </br>

- This problem states that N philosophers seated around a circular table with one fork between each pair of philosophers. A philosopher may eat if he can pick up the two forks adjacent to him. One fork may be picked up by any one of its adjacent followers but not both.

- Each time a philosopher finish eating, they will drop drop their forks and start sleeping. Once they have finished sleeping, the will start thinking and waiting to eat.

- Simulation stops when a philosopher dies.

- Every philosopher needs to eat and they should never starve.

- Philosophers do not speak with each other.

- Philosophers do not know when another philospher is about to die.

- And of course, philosophers should avoid dying.

*****Solutions*** philosophers with threads and mutex. One fork between each pair of philosophers.**

# Usage
Go to **Philosophers** folder and run **make**.
```
cd ./Philosophers && make
```
```
./philo [N PHILOS] [DIE TIME] [EAT TIME] [SLEEP TIME] (OPT)[PHILO EAT N TIMES] 
```
```
//example: ./philo 4 800 200 200
```
