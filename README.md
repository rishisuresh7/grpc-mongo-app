# gRPC-mongo-app

## A basic grpc-http-mongo application for CRUD operations

## Pre-requisites
```
- docker
- docker-compose
```

- To run the application, configure the docker-compose file with your required config(such as PORT, IP, etc.).
- Before building the images, compile and place the binaries from [http](https://github.com/rishisuresh7/http-server) and [grpc](https://github.com/rishisuresh7/grpc-server) into [http-server](http-server) and [grpc-server](grpc-server)  respectively.
- After placing the binaries, use the following cmd to run the images.
  - ```shell
    $ docker-compose up -d
    ```
    
- Use ```curl -X GET http://localhost:$HTTP_SERVER_PORT/health``` to check application status.
