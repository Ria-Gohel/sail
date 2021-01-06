## Sail CMD
It is a command line utility for sail project

## How to run
**1. Build cmd using the following command in cmd folder**

``` 
go build sail.go
```
**2. Run cmd using command**
```
./sail <command> [arguments]
```
For the list of commands, type
```
./sail help
```

## List of commands
**1. List all process**
```
./sail list --all process
```
**2. Dockerize**
```
./sail dockerize --pid <pid of process> --imageName <image name you want>
