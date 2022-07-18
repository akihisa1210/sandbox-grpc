# Example service

## Generate gRPC code

```sh
@example
protoc --go_out=./api --go-grpc_out=./api proto/example.proto
```

## Run

### Server

```sh
@example/api
go run ./server/server.go
```

### Client

```sh
@example/api
go run ./client/client.go
```
