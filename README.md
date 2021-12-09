# bbms-docker-compose.yml 
RUN Service Blood Bank Managment System
## Installation
1. git clone project
2. cd restrict
3. run docker-compose up --build -d
4. Visit browser on ip address your virtual machines.
## Structure directories
          restrict
              |
---------------------------------------------------
   |        |            |                 |
conternt  nginx         php      docker-compose.yml
            |            |
         site.conf  Dockerfile
