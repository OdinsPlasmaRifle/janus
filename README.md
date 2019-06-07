# Janus

## Protocol Buffers

Generate the GRPC `.pb.go` file after every `.proto` change:

```bash
protoc -I proto/ proto/janus.proto --go_out=plugins=grpc:proto/
```
