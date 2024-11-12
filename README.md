### Ejemplo de un archivo `README.md` completo:

```markdown
# My Flask Project

This project is a simple web application that says "Hello World"

#Technologies Used
Python 3.11
Flask
Docker

## Installation
Follow the steps below to install the project on your local machine:

```bash
# Clone the repository
git clone https://github.com/SantiagoZ98/App-Python_Flask.git

# Pull the Docker image: Before running the container, pull the Docker image with the following command:
docker pull santiagozurita26/my-app-flask

# Run the Docker container: After pulling the image, run the container using this command:
docker run -p 5000:5000 my-app-flask

#Access the aplication: You can access the aplication by navigating to the following URL in your web browser: http://127.0.0.1:5000
