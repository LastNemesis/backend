# Backend Project
This is the backend of the first project of Cloud Integration

## How to build and run the project 
Open the command line/terminal of the project

> Enter 'gradlew'

> Enter 'gradlew Bootrun'

## How to access the URL of the Item page

> Enter 'http://localhost:8080/api/items'

## How to access the URL of the Item with ID

> Enter 'http://localhost:8080/api/items/1'

## How to access the DB with URL

> Enter 'http://localhost:8080/h2-console' inside the Navigator

## How to create the Jar

> gradlew bootjar

## How to build

> java -jar build\libs\server.jar

## How to create the docker Image

> docker build --tag=server:latest .

## Execute l'Image docker créé

> docker run -d -p 8080:8080 server

## How to see the Instance running

docker ps