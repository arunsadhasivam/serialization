# serialization
https://developers.google.com/protocol-buffers/docs/proto
https://developers.google.com/protocol-buffers/docs/reference/java-generated

C:\Admin>protoc -I=C:/protoc/protobuf --java_out=C:/protoc/protobuf/java C:/protoc/protobuf/*.proto

C:\Admin>

folder structure:
=================

C:\protoc\protobuf\*.proto - all .proto files created newly 
acts as source
i.e C:\protoc\protobuf\ contains all proto files manually created message.

C:\protoc\protobuf\java - empty java folder destination dir

once run the above command it generate java file to C:\protoc\protobuf\java
