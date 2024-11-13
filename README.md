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
