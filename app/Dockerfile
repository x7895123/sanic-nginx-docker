# git config --global credential.helper store
# docker exec -it {container_id} /bin/sh

FROM python:3.8.7

# Set the working directory to /app
WORKDIR /usr/src

# Copy the current directory contents into the container at /app
ADD . /usr/src

# upgrade pip
RUN pip install --upgrade pip

# install requirements
RUN pip install -r requirements.txt