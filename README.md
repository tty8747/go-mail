# How to start

## Install go 

```bash
$ wget https://dl.google.com/go/go1.12.7.linux-amd64.tar.gz
$ sudo tar -C /usr/local -xzf go1.12.7.linux-amd64.tar.gz
$ export PATH=$PATH:/usr/local/go/bin
$ cat >> export GOPATH=$HOME/go
$ cat >> export PATH=$PATH:/usr/local/go/bin
$ source ~/.profile
```

## Clone repo

```bash
$ git clone git@github.com:tty8747/go-mail.git
```

## Install dependences
 - See GOPATH:
    ```bash
    $ go env GOPATH
    ```

 - Change directory who contained your project:
    ```bash
    $ cd ...
    ```
 - Export variables:
    ```bash
    export GOPATH=$(pwd)
    ```
 - Get your dependences:
    ```bash
    go get github.com/mailgun/mailgun-go
    ```

## How to compile

 - Linux:
    ```bash
    go build -o awesomname main.go
    ```
 
 - Cross compile for Windows from Linux
    ```bash
    GOOS=windows GOARCH=amd64 go build -o awesomname.exe main.go
    ```
