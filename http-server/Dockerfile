FROM golang:1.13-alpine
RUN mkdir -p /opt/httpserver
ADD http-server /opt/httpserver
WORKDIR /opt/httpserver
EXPOSE 9001
CMD ./http-server