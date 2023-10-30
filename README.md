go run server/server.go -port 5454

go run client/client.go -cID 1 -cPort 8080 -sPort 5454 

go run client/client.go -cID 2 -cPort 8080 -sPort 5454 

go run client/client.go -cID 3 -cPort 8080 -sPort 5454 
