# opencti-demo
A slightly hacky demo version of opencti 

Requirements:
- Git installed on your device (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Docker desktop or a connection to a device running docker (https://docs.docker.com/desktop/)

For Mac open terminal, for windows open powershell as an admin

navigate to the directory you want to use

example: `cd Documents`

Create a directory to contain the required docker files

`mkdir docker-demo`

Download the compose.yml and .env files from Github

`git clone https://github.com/80tharp/opencti-demo`

Run Docker in detached mode (use sudo if on mac)

`docker compose up -d`

Navigate to http://localhost:8080 and enter the username and password from the .env file
