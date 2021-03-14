FROM golang:1.13-alpine
RUN mkdir -p /opt/grpcserver
ADD grpc-server /opt/grpcserver
WORKDIR /opt/grpcserver
EXPOSE 9001
CMD ./grpc-server