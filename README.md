#  A2ZFilms Management System
A2ZFilms is a film production and publication house. It produces Hollywood films. A film cannot be made without a producer or a production company. This management system holds all the film records that have only been released to Hollywood through this company till now. A film is also not possible without the help of a director and cinematographer.  Corresponding to the films it also holds all the Directors and Cinematographer records who have worked for their company so far. A2ZFilms also holds their Agent records. Agent who works for them or approaches new directors and gives them this production company to make films. Agent is needed for the debut directors or, the directors who do not belong to the film industry before. The agent is the best help for the new directors to let their film script reach any producer. The directors who already belong to the film industry do not need an agent to reach any production company.



#**Entities**


Movies: It contains information like movie name, genre, runtime, release date, director id and cinematographer id for a movie.

Director: It has director name, id, and director age and agent id. 

Cinematographer: It contains cinematographer name, id, and age.

Business: It holds business rate of a movie like budget, box-office collection, hit or flop.

Agent: It holds agent name, id, and age.



A director can be either approached or not approached by an agent. If approached it means new director, if not it means old director. For the directors who do not have any agent the value would be Null in record. A director can have multiple films from this company. Also, an agent can approach many directors but a director can only have one agent.



# ER Diagram

![Picture1](https://github.com/user-attachments/assets/f1f80b58-420c-4da4-b7e6-5f64ad200b46)



# Schema Diagram

![Picture2](https://github.com/user-attachments/assets/e89d30c3-dff8-45a8-80c9-97924650c402)


**Operators used**

divide(/), equal to(=), greater than(>), BETWEEN, AND, ALL, IN, IS, LIKE, NOT, OR 

**Function used**

Count, WHERE, Group By, Order By, Null, Join, Distinct, AVG, MIN, MAX, UNION


# Queries

1.	Show all the movies and their records that have release from A2ZFIlms.

   ![1 1](https://github.com/user-attachments/assets/c0058f27-5ad6-4e55-91ca-5c931567da1a)


2.	Show only the unique cinematographer id from the movie table.

   ![2](https://github.com/user-attachments/assets/d3a13182-44dd-4e4a-b375-573ff447e68c)

3.	Show movies and their release date in the crime genre.

   ![3](https://github.com/user-attachments/assets/f596bf35-2ff0-4107-9cad-42c62e11d503)


4.	Show all the movies and their director name that have been released.

   ![4](https://github.com/user-attachments/assets/d68f2f7c-3889-4e79-9709-b31d20425ed7)


5.	Show the movie name, release date, and its runtime Steven Spielberg has directed.

   ![5](https://github.com/user-attachments/assets/59ee3dd7-cce7-4e07-ab3d-5bbe0799b034)


6.	Show movie names and their corresponding director and cinematographer name where both cinematographer and director age equal and greater than 50?

   ![6](https://github.com/user-attachments/assets/463a4d6a-f112-443c-83cb-63b9fdcbceaf)


7.	Show the movie that goes three hours in runtime.

   ![7](https://github.com/user-attachments/assets/8733fac6-43e5-4034-96cc-d73823e01720)


8.	Show cinematographer name , id , age where there age gets halved. Rename the row as halved.

   ![8](https://github.com/user-attachments/assets/ef462fb3-da9d-428a-affe-97cf397b70ef)

9.	Show movie name and the director name in ascending order of release date

   ![9](https://github.com/user-attachments/assets/f05a9c87-a676-43c6-93a0-6eebdd79291e)

10.	 Show the number of movies that became Blockbuster in business.

   ![10](https://github.com/user-attachments/assets/198f0855-e26d-4874-825b-bb2276d083bd)


11.	 Show all the movies which became flop and average in business.

   ![11](https://github.com/user-attachments/assets/407b9908-2a58-4a29-a4fa-c6be0dd0db2d)


12.  Show average agent age,maximum director age, minimum cinematographer age and rename their column.

   ![12](https://github.com/user-attachments/assets/c6a16ef5-5bad-4e4b-aa46-67f8789bbe21)


13.	 Show the director's name and id who hasn’t got any agent to approach.

   ![13](https://github.com/user-attachments/assets/f160701e-f26c-4dd9-a32a-dbcb23d12865)


14.	 Show number of movies each director has directed for A2ZFilms.

   ![14](https://github.com/user-attachments/assets/a8cf08f0-22f9-47c5-a23c-b2aa50f47c5f)

15.	 Show the movies that has got released between 2000 to 2001.

   ![15](https://github.com/user-attachments/assets/e4d56e70-21d6-4d7b-ae2c-e3874d397ba8)


16.	 Show director name where director age is greater than some directors who has agent id A49.

   ![16](https://github.com/user-attachments/assets/66b712e5-2cdc-4ebd-8ef1-86b16a055f20)
