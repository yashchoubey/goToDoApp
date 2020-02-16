# Backend in golang for To-Do App
Basic app-backend configured with mongo database.

### Requirements
1. golang https://golang.org/dl/
2. gorilla/mux library for router `go get -u github.com/gorilla/mux`
3. mongo-driver library to connect with mongoDB `go get go.mongodb.org/mongo-driver`

### Functionalities
1. Create task
2. Task Complete
3. Undo a task
4. Delete a task

### Start the application

1. Make sure your mongoDB is started
2. From server directory, open a terminal and run
   `go run main.go`
