## Docker Microservice - Communication between Containers

This project showcases a Docker microservice that facilitates communication between two containers. The microservice is designed to run on a shared bridge network and leverages Docker features to enable seamless interaction.

### Features

- Docker Containers: Utilizes Docker containers to isolate and encapsulate the microservice and its dependencies.
- Communication between Containers: Enables communication between two containers on the same bridge network, allowing them to exchange data and interact seamlessly.
- Published Docker Image: The microservice's Docker image is published on Docker Hub, making it easily accessible for deployment and use.
- docker-compose.yaml: Provides a ready-to-use `docker-compose.yaml` file that sets up the required environment and pulls the microservice image from Docker Hub.
- External Volume Support: Includes an attached external volume to enable access to external data within the microservice container.

### Usage

To execute the code and run the microservice, follow the steps below:

1. Clone the repository to your local machine.
2. Open a command prompt and navigate to the cloned repository's directory.
3. Run the command `docker-compose up` to start the service and set up the required environment.

To interact with the microservice, make an API call to `http://localhost:6000/calculate` with the following JSON body:

```json
{
    "file": "file.txt",
    "product": "wheat"
}

