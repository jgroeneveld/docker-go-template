# docker-go-template

Smallest possible docker & go version using docker multistage and scratch images to have a super small final image.

## Usage

- Adjust the module in `go.mod`
- Build with docker

      docker build -t docker-go-template .
      docker run -p 9000:8080 docker-go-template
      http :9000/
