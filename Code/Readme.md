# Intelligent Traffic Control Model Checking Using UPPAAL

## Overview


Model checking is a method for checking if a finite-state model of a system satisfies the specifications provided. Traffic-Light Control System is the system under consideration with respect to this paper. Traffic-Light system being a safety critical system, it’s failure can lead to heavy loss of property as well as life. The main focus of this project is= model checking of traffic light systems and verifying if all the states are reachable and if all the safety requirements are satisfied. Uppaal is the tool used for model checking in this work. It is an integrated tool for modeling, simulation and verification of real-time systems( in this case the traffic light system).

## Project Structure

Inside the project directory:


--> trafficLightModelChecker.xml  : The main code to be executed in UPPAAL

--> traceFileForFailedCondition.xtr  : This is trace file for the unverified property that both lights can't be red at the same time.

## Instructions  

--> Download UPPAAL Stratego

1) Go to https://uppaal.org/downloads/ . 
2) Download the latest verison of UPPAAL compatible with your system. Extract the files and install the software. 

--> Executing trafficLightModelChecker.xml files  

1) The uppaal-4.1.20-stratego-7 is available in your system now.
2) Open uppaal-4.1.20-stratego-7\uppaal-4.1.20-stratego-7\uppaal.jar  file.
3) Now in this application open trafficLightModelChecker.xml file present in the Code Folder.
4) In the Simulator, one can move from one state to other on his choice/random and observe the system.
5) The properties are verified in the Verifier.
6) If a certain property is not verified then the corresponding trace file can be seen in the simulator.

## Purpose  

The project 'Intelligent Traffic Control Model Checking Using UPPAAL' has been created as a mini project for the course IT303- Software Engineering.  

## Results

We have successfully modelled the traffic light system in UPPAAL and done the model checking. The reachability properties, deadlock condition, safety conditions and other properties are verified for the system.

## Contributors  

- Mohit Awachar (191IT231)  
- Rakshit Kulkarni (191IT245)  
- Anshul Patel (191IT208)
- Kiran Kumar J M (191IT126)  
