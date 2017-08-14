# Define parent image
FROM python:3.6-slim

# Set working directory
WORKDIR /app

# Copy current directory contents into the container at /app
ADD . /app

# Install dependencies 
RUN pip install -r requirements.txt

# Define environment variable
ENV NAME World

# Run app.py
CMD ["python", "app.py"]

