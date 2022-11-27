# proglog

A distributed commit log. Following the travis jeffery book Distributed Services with Go

## Compiling protobufs

Make sure GOPATH and GOBIN are in your PATH, then...

```bash
protoc api/v1/*.proto --go_out=. --go_opt=paths=source_relative --proto_path=.
```
