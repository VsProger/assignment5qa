# Assignment 5

## Requirements
```
1)	Implement TestNG annotations (30 pts)
2)	Configure and implement logging (Log4j) (30 pts)
3)	Implement Extent Report and Screenshots (40 pts)
```

## Test locates here
```
internal/handlers/user_test.go
```

## How to implement auto report
### Install go-junit-report
```
go install github.com/jstemmer/go-junit-report/v2@latest
```
### Go to the folder
```
cd internal/handlers/
```
### Run the test
```
go test ./... | go-junit-report > report.xml
```
    
