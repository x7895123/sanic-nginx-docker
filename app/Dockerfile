# git config --global credential.helper store
# docker exec -it {container_id} /bin/sh

FROM python:3.8.7

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD ./app /app

# upgrade pip
RUN pip install --upgrade pip

# install requirements
RUN pip install -r requirements.txt