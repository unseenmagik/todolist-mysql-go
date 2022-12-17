# todolist-mysql-go
 A simple to do list tool made using Golang and JS AJAX frontend.

# Steps to follow.
1. Clone this repository
2. Edit `todolist.go` line `16` and change these defaults to suit your needs. 
```
user:pass@/todolist
. . . . . . 
user = DB username
pass = DB Password
todolist = DB Name

``````
also on line `136` you can set your http port used.
```
http.ListenAndServe(":8000", handler)
. . . . . . 
8000 = default port
```
3. run `go build`
4. To start the app, run with `go run todolist-mysql-go` or `./todolist-mysql-go`
5. Visit your browser on the port set.