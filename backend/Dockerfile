# This tells Docker to use Python
FROM python:3.10-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements file and install Django/MySQL tools
COPY requirements.txt .
RUN pip install -r requirements.txt


COPY . .