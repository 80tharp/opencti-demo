# opencti-demo
A slightly hacky demo version of opencti 

For this project you will need to have Docker Desktop (https://www.docker.com/products/docker-desktop/) as well as Git (https://git-scm.com/downloads/win).

OpenCTI is typically deployed as a container stack and Docker is an incredibly popular container management application that allows users to install and run containerized deployments on basically anything that can be called a computer. DOcker desktop is the docker application for desktop devices. Git is a version control system that will allow you to download a prewritten "Compose file".

We will go over the next steps and catch up anyone who had trouble with the intitial setup in class but if you want to play around with openCTI, follow the instructions below.

After you have installed Docker Desktop and Git:

1. Open your Command Line (terminal on mac, powershell as admin on windows)

2. Navigate to the directory you want to use
    - example: `cd Documents`

3. Create a directory to contain the required docker files

`mkdir docker-demo`

4. Navigate into that directory

`cd docker-demo`

4. Download the compose.yml and .env files from Github

`git clone https://github.com/80tharp/opencti-demo`

5. Run Docker in detached mode (use sudo if on mac)

`docker compose up -d`

6. Navigate to "http://localhost:8080" and enter the username and password from the .env file

   User: admin

   Password: hoyasaxa
