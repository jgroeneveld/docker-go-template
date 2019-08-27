# docker-go-starter

Smalles possible docker & go version using docker multistage and scratch images to have a super small final image.

## Usage

- Adjust the module in `go.mod`
- Build with docker

      docker build -t docker-go-starter .
      docker run -p 9000:8080 docker-go-starter
      http :9000/
