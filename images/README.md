# Development Environments 

### Build a new development environment image
```docker build -t <image-name>:<tag> <relative/path/to/dockerfile>```

### Run environment and mount the current directory
```docker run -it -v $(pwd)/:/code <image-name:<tag>```