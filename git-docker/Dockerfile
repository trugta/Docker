# Dockerfile

# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Run app.py when the container launches
CMD ["uvicorn", "api:app", "--host", "0.0.0.0", "--port", "80"]
# docker build -t my-app .
# docker image ls |list ra image
# docker ps |list ra tat ca container dang chay
# neus xây image thành công thì tìm hiểu cách biến 1 imag thành 1 ctn