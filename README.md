# opencti-demo
A slightly hacky demo version of opencti 

You will need Git and Docker Desktop

1. Open your terminal (terminal on mac, powershel as admin on windows)

2. Navigate to the directory you want to use
    - example: `cd Documents`

3. Create a directory to contain the required docker files

`mkdir docker-demo`

4. Download the compose.yml and .env files from Github

`git clone https://github.com/80tharp/opencti-demo`

5. Run Docker in detached mode (use sudo if on mac)

`docker compose up -d`

6. Navigate to http://localhost:8080 and enter the username and password from the .env file
