# Todo App 

This is a full-stack To-Do application built with:
- *Frontend:Angular
- *Backend:Spring Boot
- *Database:MySQL
- *Dockerized:with `docker-compose`



---------------Instructions to build and run the project----------------------------------------------------------
1.)  open docker desktop application
2.) Clone the github repository ->       git clone https://github.com/HeshMra/To-do-Task-App.git
3.) cd To-do-Task-App 
3.) docker-compose up --build   (run this command and wait untill finish,then minimize it do-not close)
4.)open->        http://localhost:4000/        from browser,(Note-if its redirected to ngnix page please press - CTRL+SHIFT+R for reset the page)



----------------NOTE - If its not working------------------------------
** Once you run "docker-compose up --build" if its not started properly follow below steps-

1. Stop the running containers- " CTRL+C "  or  "docker-compose down"
2.run again-->     "docker-compose up --build"
3.Optional-> Then you can open new terminal and go to "cd To-do-Task-App " and run "docker ps" the you can see the running containers(It should be three)











