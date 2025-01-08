Project URL
https://github.com/Fredlin2k03/Deploying-BLUE-AND-GREEN-Method
https://roadmap.sh/projects/blue-green-deployment


# Deploying-BLUE-AND-GREEN-Method 
# Blue-Green Deployment with Docker Compose

This project demonstrates a Blue-Green Deployment strategy for a simple containerized web application using Docker Compose. The goal is to deploy the next version of the application in a separate container and switch traffic only when the new version is ready. Additionally, this setup simulates a basic CI/CD pipeline with Docker Compose.

## Features

- **Blue-Green Deployment**: Deploy a new version of the application in a separate container and switch traffic once the new version is ready.
- **Docker Compose**: Use Docker Compose to manage multi-container applications.
- **Simulated CI/CD**: Automate the deployment process using Docker Compose.

## Prerequisites

Before running the project, make sure you have the following installed:

- [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/install/)
- A text editor (e.g., Visual Studio Code) for editing files.

## Setup Instructions

### 1. Clone the Repository

Clone this repository to your local machine or create a new directory for the project.

```bash
git clone <your-repository-url>
cd <your-repository-directo
2. Create Dockerfile
Create a Dockerfile to define the application container. The sample file below sets up a Python Flask app.
3. Create Docker Compose File
Create the docker-compose.yml file for defining the services (app and test).
4. Build and Run the Application
Once the Dockerfile and docker-compose.yml are set up, run the following command to build and start the services:
5. Verify the Deployment
Visit http://localhost:5000 in your browser. You should see the web app's "Hello, World!" response.

