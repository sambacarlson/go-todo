# go-todo

Learning golang from Hello world to Guru in one project

### PURPOSE

The purpose of this project is to get hands on with api services with Go, and other tools that are commonly used in the building apis in Go. \
The step by step implementation of everthing will be included in this readme file for reference and reproduciability. \
The structure, tools and practices here intend to be industry standard, but no undebatable. The main purpose is to learn, and some tools used may be unnecessary for functionality but useful for learning. \

### SOME GENERAL TOOLS USED/TO BE USED

- Golang v1.26.1^
- gRPC
- sqlc
- Postgres 18
- Github

### SOME ARCHITECTURAL SPECIFICATIONS

- Microservice architecture
- Testing emphasized

## FEATURES TO TACKLE

1. Create TODO CRUD api.
   ### Steps
   - Create Models for a `todo` (gRPC and protos in the future)
   - Intialize a postgres database with docker
   - Create simple net/http server (gRPC in the future)
   - Create handler methods for todo CRUD operations
   - Create persistent Layer methods for CRUD operations using GORM (SQLC in the future)
   - Run the program. Write tests. Deploy.

## PROCEDURE (STEP BY STEP FROM HELLO WORLD TILL NO NEW TECH IMPLS)

1. Initialize new repository on github with readme, .gitignore and license.
   - Liscence: MIT (added with github at repo initialization)
   - .gitignore: added for Go, with github at repo initialization
   - readme, added at db initialization
2. Add the main module and main file with hello world
   - Initialized a new module with `go mod init`
   - Created entry point (main.go) in cmd with hello world.
