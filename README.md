# simple_flask_app_with_docker
What is Docker?
===============

Docker is a containerization platform that allows developers to package and deploy their applications in a portable and isolated environment. Containers are a lightweight alternative to virtual machines (VMs) and provide a way to run software in a consistent and predictable manner, regardless of the host environment

what is flask?
=============

Flask is a micro web framework for Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions.

Flask is a lightweight Python web framework that provides useful tools and features for creating web applications. It is a minimalistic framework that gives the developer full control over the application and the flexibility to choose the libraries and tools that best fit their needs.

Project
=======
A Flask application can be run in a Docker container, which allows for easy deployment and scaling. To do this, you will need to create a Dockerfile that specifies the dependencies and configuration for your application. The basic steps to create a Dockerfile for a Flask application are as follows:

Start with a base image, such as python:3.9
Copy the application code into the container
Install any dependencies using pip
Expose the port that the application will run on
Set the command to run the application

You can build the Docker image using the command docker build -t myapp . and run it with docker run -p 5000:5000 myapp.

Note
====
Please note that the above example is just a simple example, you might want to tweak the example based on your application requirement.

