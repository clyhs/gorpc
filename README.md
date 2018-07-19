# gorpc
### examples 
* helloworld
* cd $GOPATH/goprc/examples/helloworld/helloworld/
* >protoc --go_out=plugins=grpc:. helloworld.proto 
* cd $GOPATH/goprc/examples/helloworld/greete_server/
* >go run main.go
* cd $GOPATH/goprc/examples/helloworld/greete_client/
* >go run main.go abigfish
* >hello abigfish

