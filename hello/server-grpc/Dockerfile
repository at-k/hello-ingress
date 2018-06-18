FROM grpc/go:1.0
EXPOSE 50051
RUN go get -u google.golang.org/grpc/examples/helloworld/greeter_server
RUN go get -u google.golang.org/grpc/examples/helloworld/greeter_client
CMD greeter_server
