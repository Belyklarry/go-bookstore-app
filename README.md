# Go Bookstore App
## Introduction
To set up our go environment, we need to run the following commands to download the necessary packages for our go-bookstore app:
```console
go mod init github.com/Belyklarry/go-bookstore-app
```
```console
go get "github.com/jinzhu/gorm"
```
```console
go get "github.com/jinzhu/gorm/dialects/mysql"
```
```console
go get "github.com/gorilla/mux"
```
Inside our ```go-bookstore``` directory, create two directories, i.e., ```cmd``` and ```pkg```.
Inside ```cmd``` create ```main``` directory, and inside the ```main``` directory create a ```main.go``` file.
Inside the ```pkg``` directory, create the following directories: ```config```, ```controllers```, ```models```, ```routes```, and ```utils```.
Inside ```config```, create ```app.go```, inside ```controllers``` create ```book-controller.go```, inside ```models``` create ```book.go```, inside ```routes``` create ```bookstore-routes.go```, and inside ```utils``` create ```utils.go```.
## Coding Steps
- start with the routes then config (app.go), then utils, then main.go, then models.go, and finally, the book controller.
