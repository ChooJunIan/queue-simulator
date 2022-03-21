# Queue Simulator 

A small queue simulator made from FreeMat. The simulator's purpose is to simulate customer arrivals at a typical service centre. As there is a Movement Control Order
present, only limited customers are allowed to be in the service centre at one time. 

At the beginning of the simulation, the user chooses a type of random generator consisting of Uniformly Distributed Integer (randi), Exponentially Distributed Integer
(randexp) and Uniform Random Number Generator (rand). **Each generator is capable of auto generating the random numbers for customers’ inter-arrival time, service time 
for two counters each and customers’ temperature.**

Then, the user is able to enter the number of customers for the whole simulation and maximum number of customers that are allowed to be in the centre.

Furthermore, the system will auto-generate and display probability tables with appropriate range of customers’ inter-arrival time and service time for each two counters.

As customers arrive at the service centre, the simulation restricts customer entry based on 3 conditions: 
1. Only customers with temperature below 37.8 celsius are allowed to enter the centre.
2. Customers will be served immediately as long as counters are available. If one of the counter is occupied with another customer, the current customer can go to the next 
available counter. Otherwise, if both counters are occupied with customers, the next customer entry has to wait to be served. 
3. If the number of customers in the service centre has reached its maximum number of customers entered by the user earlier, the next customer will have to wait to be 
served after one of the counters becomes available.

Moreover, the simulation is capable of displaying a table of customer entries and a table of
both service counters. The customer's status on arrival, entering the centre and departure of
customers by which minute will also be displayed in the command window, after displaying both
of the service counter tables

Finally, the simulation is capable of evaluating the results of the simulation for 
customers that are allowed to enter the service centre. These include: 
1. Average waiting time
2. Average time spent
3. Probability that a customer has to wait 
4. Average service time for each counter

Special thanks to my friends on this assignment: 
- Aiman Izzwan bin Zam Ariffin
- Iman Aisyah binti Zailani
- Nur Adlina Marini binti Amir Suharman
