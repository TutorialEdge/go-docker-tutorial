# Go Docker Tutorial
[Tutorial link](https://tutorialedge.net/golang/go-docker-tutorial/)

[Video link](https://www.youtube.com/watch?time_continue=617&v=lIbdPrUpGz4&feature=emb_logo)

# Run with Golang
```
go run main.go
```
which will kick of a server on http://localhost:8081.

# Run with Docker
```
docker build -t my-go-app .
docker run -p 8080:8081 -it my-go-app
```