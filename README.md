# My Flask Project

This project is a simple web application that displays "Hello World".

## Technologies Used

- Python 3.11
- Flask
- Docker

## Installation

Follow the steps below to install and run the project on your local machine:

### 1. Clone the Repository

First, clone the repository to your local machine by running the following command:

```bash
git clone https://github.com/SantiagoZ98/App-Python_Flask.git

2. Pull the Docker Image

Before running the container, you need to pull the Docker image. Use the following command to do so:

docker pull santiagozurita26/my-app-flask

3. Run the Docker Container

After pulling the image, run the Docker container using this command:

docker run -p 5000:5000 my-app-flask

4. Access the Application

Once the container is running, you can access the application by navigating to the following URL in your web browser:
      
http://127.0.0.1:5000
