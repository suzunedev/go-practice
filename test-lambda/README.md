```bash
$ go mod tidy
$ GOARCH=amd64 GOOS=linux go build -o hello
$ zip handler.zip ./hello
```

Lambda event json
```json
{
  "What is your name?": "John"
}
```

Result
```json
{
  "Answer:": "Hello John!!"
}
```
