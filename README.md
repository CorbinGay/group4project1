# Team 4 MIST 4610 Group Project 1

## Team Name:
47114 Group 4

## Team Members:
1. Morgan Busbee [@morgan-busbee](https://github.com/Morgan-Busbee)
2. Corbin Gay [@corbinGay](https://github.com/CorbinGay)
3. Carson Harris [@clh15315](https://github.com/clh15315)
4. Ashley Seelochan [@as88578](https://github.com/as88578)
5. Hank Stocke [@hstocke1](https://github.com/hstocke1)
6. Katie White [@katieawhite29](https://github.com/katiewhite29)

## Problem Description:
The task for this project is to model and build a relational database as the owner of a soccer club. In the data model, the central entity is represented as Team which contains the attributes of all of the information for each of the teams that will be playing in matches at the soccer club. The Teams table will be connected with the information about the members on the team, the facilities, the individual matches, etc. We are interested in accurately modeling this data and their relationships, as well as generating sample data and understanding these entities and their attributes within the data. We will also be creating queries to help us understand the business insights and the operations throughout the soccer club. 

## Data Model:
Explanation of Data Model:

Our data model is based on a hypothetical soccer club composed of many complex relationships among the different entities of the club.

At the heart of AUSC are the teams, each embodying spirit, strategy, and sportsmanship. These teams engage in numerous matches throughout a season, illustrating a many-to-many relationship encapsulated within the entity known as matchSchedule. This associative entity is necessary for organizing the calendar of games, ensuring that each team has the opportunity to compete in multiple matches while facilitating the scheduling of matches between two teams. 

Each match is uniquely positioned within the boundary of a season, ensuring that the narrative of the league unfolds in a structured manner, culminating in climactic season finales that determine champions. Spatially, matches are anchored to specific facilities, which provide the stage for the game. This one-to-many relationship between venues and matches underscores the importance of place in the sport. 

The integrity and fairness of matches are upheld by referees, who navigate the complexities of the game with expertise. Recognizing the demanding nature of this role, AUSC employs a many-to-many relationship through the refSchedule entity, allowing referees to officiate multiple matches while enabling a single match to be overseen by multiple referees. This system ensures that matches are conducted fairly, with referees bringing varied perspectives and expertise to the game, enhancing the quality and fairness of the competition.

At the individual level, teams consist of players, each bringing unique skills and roles to their team. Players are supported by coaches, who provide strategic insight, training, and mentorship. This relationship is further enriched by the involvement of parents, who may have multiple children playing across different teams, creating a web of personal investment in the club's success. Training sessions are vital for team preparation, where strategies are honed, skills are developed, and bonds are strengthened. These sessions utilize various pieces of equipment, highlighting the material needs of teams and the importance of resources in their development.

AUSC's structure is rounded off by the leagues, which are composed of the myriad teams in competition. These leagues represent the broader organizational framework within which the drama of the soccer season unfolds. Members, through their financial contributions and fervent support, breathe life into the games. By paying a fee, they not only gain access to witnessing the matches but also contribute to the financial sustenance of the league, enabling it to thrive and grow.



<img width="576" alt="Screenshot 2024-03-27 at 8 33 54 PM" src="https://github.com/clh15315/group4project1/assets/150160152/da3db633-1876-4ab5-a25b-c73ab5eb8981">



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

### Query 1:
Write a query to list the name, contact information, and address of all parents whose children are on the mighty falcons team.
<img width="631" alt="Screenshot 2024-03-27 at 8 46 44 PM" src="https://github.com/clh15315/group4project1/assets/40582321/2c567a1a-ba09-40c8-bda9-808f4f08698d">

Query 1 gives a list of the names of the parents, their contact information and their address for the team "Mighty Falcons." This helps the soccer club to manage who each of the parents are for this specific team. They are able to easily access this information in case of an emergency or just to be able to contact the parents when certain information needs to be presented out.

### Query 2: 
Write a query to count how many matches each ref has refereed
<img width="628" alt="Screenshot 2024-03-27 at 8 47 14 PM" src="https://github.com/clh15315/group4project1/assets/40582321/842e6d08-c45d-4046-80f2-c9079a97c318">

### Query 3: 
Write a query to list out all players, and the name of their team, and their coaches
<img width="600" alt="Screenshot 2024-03-27 at 8 47 47 PM" src="https://github.com/clh15315/group4project1/assets/40582321/c61eb572-95ca-4376-92e8-54d98da5a194">

### Query 4: 
Write a query to find the total number of players in each age group
<img width="626" alt="Screenshot 2024-03-27 at 8 50 12 PM" src="https://github.com/clh15315/group4project1/assets/40582321/c73fb0e8-9833-477b-93fd-dce1b7e546bc">

### Query 5: 

### Query 6: 
Write a query to count how many players are in each team
<img width="626" alt="Screenshot 2024-03-27 at 8 51 23 PM" src="https://github.com/clh15315/group4project1/assets/40582321/a72ecca5-0cfb-4b7a-8bda-050c1b06d509">

### Query 7: 
Write a query to count the number of poor goalkeeper gloves

### Query 8: 
Write a query to list the names of players who played between 2012-2014

### Query 9:
Write a query to list the names of refs and the number of facilities they have refereed at
<img width="444" alt="Screenshot 2024-03-27 at 8 53 02 PM" src="https://github.com/clh15315/group4project1/assets/40582321/1b471d28-4f29-4486-9dcb-06a87659841e">

### Query 10:
Write a query to find the total fee cost of membership 9-11 and 12-14 age group
<img width="502" alt="Screenshot 2024-03-27 at 8 53 16 PM" src="https://github.com/clh15315/group4project1/assets/40582321/14b64f6d-f75b-46d9-9385-208a07f6eca8">


## Database Information: 
Name of the database: ns_Sp24_47114_Group4
