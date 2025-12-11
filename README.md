# Experiment-5-Multiple-Sever-with-infinite-capacity-(M/M/k)-(oo/FIFO)
# Aim
 	To find 
  
a)	Average number of materials in the system 

b)	Average number of materials in the conveyor

c)	Waiting time of each material in the system 

d)	Waiting time of each material in the conveyor

If the arrival of materials follow poisson process with mean interval time 10 seconds, service time of two lather machine follow exponential distribution with mean sevice time 1 second and average service time of robot is 7 seconds.

# Software required: Visual Components and Python
# Theory: 
Queueing shows up everywhere: cafeterias, libraries, banks—anywhere arrivals need service and may face delay. Waiting can’t be removed entirely, but it can be controlled. Adding more servers reduces delays, though it may increase idle time.
In an M/M/∞ system, there are infinitely many servers, so every arrival begins service immediately and no one waits. Arrivals follow a Poisson rate λ, and each server provides exponential service with rate μ.
If there are k customers in the system, then k servers are busy. Each works independently, so the total service-completion rate is the minimum of k exponential clocks, giving an overall departure rate of kμ.
This lets us treat the M/M/∞ model as a simple Markov chain and find the distribution of the number of customers in service.
# Algorithm
<img width="806" height="297" alt="image" src="https://github.com/user-attachments/assets/e08285b0-8d2d-4b63-8e52-4bf2d065b0ff" />

# Program

# Output

# Result
       The average number of material in the system and in the conveyor and waiting are  successfully found.

