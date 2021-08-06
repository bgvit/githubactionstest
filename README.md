# Go Hello World

This is a simple Go web application that prints a "Hello World" message.

## Run the application

This application listens on port `6111`

To run the application, use the following command:
```
go run main.go 
```

or
```
docker pull bgvit/go-helloworld
docker run --name go-helloworld -p 6111:6111 -d go-helloworld
```


Access the application on: http://127.0.0.1:6111/ 
