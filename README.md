# Docker Tutorial


## Project setup
To create the image of the docker file
```
docker build -t getting-started .
```
To Run the container after you have successfully build the docker image
```
docker run -dp 3000:3000 getting-started
```
