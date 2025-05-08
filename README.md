Build the image using the following command

$ docker build -t bhaskarit/python:version-2.3 .

Run the Docker container using the command shown below.

$ docker run -d -p 5000:5000 bhaskarit/python:version-2.3

The application will be accessible at http://localhost:8080/
