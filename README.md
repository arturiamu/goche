## goche

goche is a simple distributed caching system written in Go (Golang). Used to learn and understand cache, LRU, locks, consistent hashing,protobuf, etc., the code comes from [geektutu/7days-golang](https://github.com/geektutu/7days-golang)

## Features

- Single-machine cache and HTTP-based distributed cache
- Least Recently Used (LRU) cache policy
- Prevent cache penetration using Go locking mechanism
- Use consistent hashing to select nodes for load balancing
- Optimize inter-node binary communication using protobuf
