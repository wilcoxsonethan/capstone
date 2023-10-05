# Use an official Python runtime as a parent image
FROM python:3.11

# Set the working directory in the container
WORKDIR /app

# Create a virtual environment and activate it
RUN python -m venv venv
RUN /bin/bash -c "source venv/bin/activate"

# Copy the local requirements file to the container
COPY requirements.txt .

# Install the requirements inside the virtual environment
RUN pip install --no-cache-dir -r requirements.txt

# Copy the local project directory to the container
COPY . .

# Define the command to run your Django app
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
