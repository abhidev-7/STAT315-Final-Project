# Docker Setup

Once the Repository is cloned you will need to go to the directory where the reporsitory was cloned and run the following 2 commands.
The first command builds the Docker image while the second command runs the docker container.

docker build -t nba-shooting-project:latest .

docker run -p 8888:8888 nba-shooting-project:latest

Once the second command runs there will be a link that will take you to the juypter notebook were you can access the file with the report and code.

If you ever need to restart the container you can open up DockerHub where you will see the container saved and you can simply run it.

You can also use this command again

docker run -p 8888:8888 nba-shooting-project:latest

