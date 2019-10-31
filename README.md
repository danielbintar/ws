# ws

ws is a simple command line websocket client designed for exploring and debugging websocket servers. ws includes readline-style keyboard shortcuts, persistent history, and colorization.

![Example usage recording](https://hashrocket-production.s3.amazonaws.com/uploads/blog/misc/ws/ws.gif)

### Pre-requisite
- Go 1.13.3

## Usage

Simply run ws with the destination URL.
```
go run main.go connection.go ws://localhost:8002/chat
```
