# Warung Pintar Pre-test

Warung Pintar Pre-test

## Requirement

- Go Lang (https://github.com/golang/go)
- Go Dep (Go Depedency Management Tool) (https://github.com/golang/dep)
- Gorilla Websocket (Go Websocket) (https://github.com/gorilla/websocket)

## Installations

Clone Project

```
$ git clone https://

# Install Dependecies
$ dep ensure
```

## Run Server

```
$ make run
```

## List API

```
# Get All Names
$ localhost:8080

# Submit Name
$ localhost:8080/submit
body : {
    name: "test"
}

# Connect Websocket
$ localhost:8080/ws
```
