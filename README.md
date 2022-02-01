Docker compose project README

This project demonstrates the proper docker compose usage.
It uses a webpage run by Flask to get input from a user that asks for a name, email, and password
The user can then choose to save inputted data to a Redis cache or to a PostgreSQL database.

Instructions
1) open the terminal and issue the following git clone command:
git clone https://github.com/oneboostedboy/docker-compose-project.git

2) change directory into the docker compose project folder
cd docker compose project

3) issue the following command into the terminal
docker compose down && docker compose build && docker compose up

4) navigate to your browser and go to localhost:5000
