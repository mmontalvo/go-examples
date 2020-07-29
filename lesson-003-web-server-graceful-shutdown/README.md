
## Trigger requests from the terminal with:
```
for ((i=1;i<=10;i++)); do curl http://localhost:8080;done
```

## commands to stop the server
```
pgrep -i main
kill -SIGTERM 69489
```

## command to build and run our server
```
go build main.go; ./main
```