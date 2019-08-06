* go-mail

* install src
  - go env GOPATH
  - cd ...
  - export GOPATH=$(pwd)
  - go get github.com/mailgun/mailgun-go

* cross compile for windows on linux

GOOS=windows GOARCH=amd64 go build
