# ADS2-Drone-Challenge
A solution to the UofG ADS2 Drone Challenge

The Drone Delivery Problem (a challenge)
----------------------------------------

We have a collection of customers, each with an x/y coordinate. Customers have to be 
serviced by drones, i.e. goods are delivered to customers via drones. 

The problem is to specify where depots have to be placed, such that (1) customers
are serviced by drones from the customer's nearest depot (2) there is a cost of 2500
units (fixed cost) for setting up a depot, (3) delivery cost to a customer is the
Euclidean distance from their nearest depot (4) a drone can fly a distance of 
at most 150 units (i.e. no customer can be more than 150 units of distance away from a depot).

The object is to find the lowest cost solution: sum of distances plus sum of depot costs

Software and problems
---------------------
Given a file of customers (such as p22.txt or p317.txt) and a solution
(such as depot22.txt or depotP317) the program

 > java Warehouses depotP317.txt p317.txt
 
 will cost and display the solution.
 
 You can also look at a file of customers as follows
 
 > java DisplayCustomers pP317.txt
