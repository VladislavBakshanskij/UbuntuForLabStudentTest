# Simple docker file

# import python v3.8 from dockerhub
FROM python:3.8 

# make app directory
RUN mkdir -p /src/app

# select working directory
WORKDIR /src/app

# copy all files to app directory
COPY . /src/app

# run python script
CMD ["python3", "main.py"]
