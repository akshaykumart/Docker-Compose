# Docker-Compose
Wordpress app deployment along with Mysql using Docker-compose

Pre-requisites:
1.   Ubuntu machine
2.   Docker installed into it (sudo apt install docker.io)

Steps:

1.	Create a folder and get into it

             •   mkdir <folder_name>
 
             •    cd <folder_name>

2.	Create a yaml file

             •   sudo nano docker-compose.yml
 
 
3.	Build the docker compose file:

             •   sudo docker-compose up -d
 
4.	Ensure the containers are running:

             •   sudo docker ps

5.	 Take the public Ip address and paste it in the browser with port as mentioned in script.


             •   <public_IP>:<port>

 


