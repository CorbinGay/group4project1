# Team 4 MIST 4610 Group Project 1

## Team Name:
47114 Group 4

## Team Members:
1. Morgan Busbee
2. Corbin Gay @corbinGay
3. Carson Harris @clh15315
4. Ashley Seelochan
5. Hank Stocke
6. Katie White @katiewhite29

## Problem Description:
The task for this project is to model and build a relational database as the owner of a soccer club. In the data model, the central entity is represented as Team which contains the attributes of all of the information for each of the teams that will be playing in matches at the soccer club. The Teams table will be connected with the information about the members on the team, the facilities, the individual matches, etc. We are interested in accurately modeling this data and their relationships, as well as generating sample data and understanding these entities and their attributes within the data. We will also be creating queries to help us understand the business insights and the operations throughout the soccer club. 

## Data Model:
Explanation of Data Model:

Our data model is based on a hypothetical soccer club composed of many complex relationships among the different entities of the club.

The club revolves around the teams and their matches. This many to many relationship is displayed in our model by the associative entity matchSchedule which allows a team to participate in many matches and allows a match to be played between two teams. 

A match can only exist within a single season and can only be held at one facility. A match can have multiple referees and referees can participate in more than one match. This many to many relationship is displayed by the associative entity refSchedule. 

Teams are made of many players and a parent can have multiple players. Teams are made of multiple coaches and teams practice in multiple training sessions. Teams can own and use many different pieces of equipment.

Leagues are composed of many teams that play each other and members that pay a fee to watch games of a certain league. 


<img width="569" alt="Screenshot 2024-03-25 at 3 01 07 PM" src="https://github.com/clh15315/group4project1/assets/150160152/12570176-a2c6-43ad-86ae-68122175b83b">




## Data Dictionary:
### Table: Players
<img width="536" alt="Screenshot 2024-03-27 at 3 40 20 PM" src="https://github.com/clh15315/group4project1/assets/40582321/20808343-391b-42ad-b2ed-4b66a8771211">

### Table: Teams
<img width="536" alt="Screenshot 2024-03-27 at 3 40 40 PM" src="https://github.com/clh15315/group4project1/assets/40582321/8781ae18-2e50-4221-9992-0c8df8b82f07">

### Table: Coaches
<img width="526" alt="Screenshot 2024-03-27 at 3 40 55 PM" src="https://github.com/clh15315/group4project1/assets/40582321/511b44e7-7d93-46dc-89c7-2e2165793c76">

### Table: Leagues
<img width="555" alt="Screenshot 2024-03-27 at 3 41 12 PM" src="https://github.com/clh15315/group4project1/assets/40582321/6a783ab9-5474-4464-8cef-3209739fa9b6">

### Table: Matches
<img width="630" alt="Screenshot 2024-03-27 at 3 41 49 PM" src="https://github.com/clh15315/group4project1/assets/40582321/0e9bf639-2dcc-4215-8b0e-243333989e74">

### Table: Match Schedule
<img width="553" alt="Screenshot 2024-03-27 at 3 42 10 PM" src="https://github.com/clh15315/group4project1/assets/40582321/26f675e4-60bf-425a-b51c-bb5c9b2e9752">

### Table: Training Sessions
<img width="627" alt="Screenshot 2024-03-27 at 3 42 32 PM" src="https://github.com/clh15315/group4project1/assets/40582321/2da6d861-e5d9-4156-9038-f27298d43947">

### Table: Season
<img width="554" alt="Screenshot 2024-03-27 at 3 42 52 PM" src="https://github.com/clh15315/group4project1/assets/40582321/8b4285ad-0cef-41a0-8e6e-17bdf2df93b5">

### Table: Facilities
<img width="548" alt="Screenshot 2024-03-27 at 3 43 07 PM" src="https://github.com/clh15315/group4project1/assets/40582321/9bcf1220-1519-4f78-8783-56ced195a13d">

### Table: Equipment
<img width="569" alt="Screenshot 2024-03-27 at 3 43 22 PM" src="https://github.com/clh15315/group4project1/assets/40582321/4f9be525-908d-4f28-b901-aa6ab96fe392">

### Table: Parents
<img width="570" alt="Screenshot 2024-03-27 at 3 43 39 PM" src="https://github.com/clh15315/group4project1/assets/40582321/fde4bf88-080c-4d8c-801e-762e27f9c7af">

### Table: Memberships
<img width="569" alt="Screenshot 2024-03-27 at 3 45 01 PM" src="https://github.com/clh15315/group4project1/assets/40582321/46b244eb-c206-4692-9485-e558d8589da3">

### Table: Referees
<img width="567" alt="Screenshot 2024-03-27 at 3 45 15 PM" src="https://github.com/clh15315/group4project1/assets/40582321/256dc2e4-4ed7-4e29-ac0f-40d89f9de1d9">

### Table: Referee Schedule
<img width="568" alt="Screenshot 2024-03-27 at 3 45 37 PM" src="https://github.com/clh15315/group4project1/assets/40582321/35ddc1d0-5747-47bb-95e4-e1369a6fb9ac">


## Queries:

## Database Information: 
Name of the database: ns_Sp24_47114_Group4
