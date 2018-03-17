# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
Existing resources can be used to determine the county or counties that correspond to a particular ZIP code. My project 
would allow a person to input a Missouri ZIP code and, for each corresponding county, get the judicial circuit, 
Missouri court district, and federal court district in which that county is located, along with the address of the 
county’s circuit court. 

This idea comes from my work as an attorney, in which one of the first things I try to determine if I take a case in an 
unfamiliar jurisdiction within the state is whether the case is in circuit court or municipal court. Unless the 
municipal court shares an address with the circuit court, looking at the court address and comparing it to that of the 
circuit court would allow this determination.

### Features
•	Search by county, by court address (to see whether a court address is within the database of circuit court 
            addresses), by ZIP code, and possibly by address (to see what county the address is in)
•	Users will be able to create an account
•	Users, after logging, in, will be able to input a custom set of addresses to augment the existing database.

### Technologies
•	Java
•	MySQL (for the list connecting ZIP codes to addresses)
•	Gradle
•	Thymeleaf


### What I'll Have to Learn
I’ll have to learn how to use existing resources that connect an address or ZIP code to a county. I will also have to 
figure out how to have a shared database for all users that interacts with custom database entries submitted by each 
user so that they can search both simultaneously.