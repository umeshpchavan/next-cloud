1. Clone the Repository
    https://github.com/umeshpchavan/next-cloud.git
   
2. Start Nextcloud
  Run the following command:
    docker-compose up -d
   
3. Access Nextcloud
   Open your browser and go to:
   http://localhost:8080
  Login using the credentials set in docker-compose.yml.

4. Stop and Restart Nextcloud
   To stop the containers:
     docker-compose down
   To restart Nextcloud:
     docker-compose up -d
