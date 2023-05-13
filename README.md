# Docker
Explored features of Docker Container and created a microservice which is used to communicate between two docker containers and set up on same bridge-network.
Published an image on Docker HUB
Created a docker-compose.yaml file which is used to setup the required environment and pull image from docker hub.
Attached an external Volume to access in the container.
To Execute the code follow this step 
Clone the repository.
In Command prompt where the repo is cloned type "docker-compose up".
This will automatically starts the service.

Make an api call on
http://localhost:6000/calculate
and pass the body
{
 "file": "file.txt",
 "product": "wheat"
}


