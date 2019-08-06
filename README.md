* installing go (https://golang.org/doc/install?download=go1.12.7.linux-amd64.tar.gz)
  - $ wget https://dl.google.com/go/go1.12.7.linux-amd64.tar.gz
  - $ sudo tar -C /usr/local -xzf go1.12.7.linux-amd64.tar.gz
  - $ export PATH=$PATH:/usr/local/go/bin
  - $ cat >> export GOPATH=$HOME/go
  - $ cat >> export PATH=$PATH:/usr/local/go/bin
  - $ source ~/.profile

* go-mail

* install src
  - go env GOPATH
  - cd ...
  - export GOPATH=$(pwd)
  - go get github.com/mailgun/mailgun-go

* cross compile for windows on linux
  GOOS=windows GOARCH=amd64 go build
