# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install dependencies
RUN pip install flask

# Expose the port Flask will run on
EXPOSE 5000

# Set the environment variable for Flask
ENV FLASK_APP=server.py

# Run the Flask app
CMD ["python", "server.py"]