# swagger-tools

Docker image containing [swagger-tools](https://github.com/apigee-127/swagger-tools).

## Build it

Build the image by running:

`docker build -t rovecom/swagger-tools .`

## How to use

View help files:

`docker run -it --rm rovecom/swagger-tools --help`

Validate a file:

`docker run -it --rm -v ${pwd}:/work rovecom/swagger-tools validate swagger.yaml`