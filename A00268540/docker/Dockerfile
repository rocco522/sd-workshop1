FROM ubuntu:16.04
MAINTAINER ridel007@gmail.com

#Install package
RUN apt-get update -y
RUN apt-get install postgresql -y

#Configuracion del puerto de postgres
EXPOSE 5432
CMD postgresql -m http.server 5432



#--------------
# Use an official Python runtime as a parent image
#FROM python:2.7-slim

# Set the working directory to /app
#WORKDIR /app

# Copy the current directory contents into the container at /app
#ADD . /app

# Install any needed packages specified in requirements.txt
#RUN pip install -r requirements.txt

# Make port 80 available to the world outside this container
#EXPOSE 80

# Define environment variable
#ENV NAME World

# Run app.py when the container launches
#CMD ["python", "app.py"]
