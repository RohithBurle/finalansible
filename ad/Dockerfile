# Use the official Python image as the base image
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy the local app.py file to the container
COPY . /app/

# Install Flask and dependencies
RUN pip install --no-cache-dir flask

# Expose the port that Flask will run on
EXPOSE 5000

# Define the command to run the Flask app when the container starts
CMD ["python", "app.py"]

