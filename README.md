# golang-lambda
Golang lambda example.

# How to start?

Compile the project and compress the binary. Make sure to configure the GOOS and GOARCH environment variables.

``` shell
set GOOS=linux
set GOARCH=amd64
go build -o main main.go
%USERPROFILE%\Go\bin\build-lambda-zip.exe -o main.zip main
```