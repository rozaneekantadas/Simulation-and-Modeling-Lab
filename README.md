# Simulation-and-Modeling-Lab

##Tool
Arena - 

## Model 1 Problem Statement
In a Car Repair shop , car arrives to take the service. Time between car arrivals is 4 minutes(Random expo) . After arrival they wait in the single channel queue to get serviced. Servicing each car requires constant time of 5 minutes by the resource. After getting serviced they exit the system. Setup: Replication Length 60 minutes , base unit in minutes, replication 1.

## Model 2 Problem Statement
In a Car Repair shop , car arrives to take the service. Time between car arrivals is 4 minutes(Random expo ) There are two resources. Any Car after entering first try to get serviced from 1st resource if it is busy with another car then the car try to get serviced by 2nd resource, if 2nd is also busy then wait to get serviced by 2nd resource. Servicing each car requires constant time of 5 minutes (each resource). After getting serviced they exit the system. Setup: Replication Length 60 minutes , base unit in minutes, replication 1.

## Model 3 Problem Statement
In a Car Repair shop , car arrives to take the service. Time between car arrivals is 4 minutes(Random expo).Resource or machine of the shop is capable of repairing 5 cars only .so After arrival Car or customer check the number of cars serviced by the resource ,if the number is 5 or more they exit and if not then they wait in the single channel queue to get serviced. Servicing each car requires constant time of 5 minutes by the resource. After getting serviced they exit the system. Setup: Replication Length 60 minutes , base unit in minutes, replication 1.


## Model 4 Problem Statement
In a Potato chips factory , Potatoes are given as input. Inter arrival time between Potatoes is 5 minutes (Random expo).Then potatoes are processed by a chips maker and converted into crispy chips. Time required by chips maker to convert a potato into chips is uniformly distributed between .5 to 1.5 . Only 50% chips are inspected to be good. Then good chips go for packaging. Bad chips go into dump. Packaging requires constant amount of 1 minute. Setup: Replication lenth:60 minutes , Replication 1.

## Model 5 Problem Statement
In a Potato chips factory , Potatoes are given as input. Inter arrival time between Potatoes is 5 minutes (Random expo).Then potatoes are processed by a chips maker and converted into crispy chips. Time required by chips maker to convert a potato into chips is uniformly distributed between .5 to 1.5 . Only 50% chips are inspected to be good. Then good chips go for packaging. Assume that inspector is greedy person, so every time he get bad chips he check the number of packed chips ,if it is less than 12 he send bad chips for packaging else Bad chips go into dump. Packaging requires constant amount of 1 minute. Setup: Replication lenth:120 minutes , Replication 1.
