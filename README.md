# serialization
https://developers.google.com/protocol-buffers/docs/proto
https://developers.google.com/protocol-buffers/docs/reference/java-generated

C:\Users\Sales-PC>protoc -I=C:/protoc/protobuf --java_out=C:/protoc/protobuf/java C:/protoc/protobuf/*.proto

C:\Users\Sales-PC>

folder structure:
=================

C:\protoc\protobuf\*.proto - all .proto files created newly 
acts as source
i.e C:\protoc\protobuf\ contains all proto files manually created message.
C:\protoc\protobuf\java - empty java folder destination dir
