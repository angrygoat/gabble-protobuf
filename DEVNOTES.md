
# Developer notes

### Handy links

* protobuf compiler usage - https://developers.google.com/protocol-buffers/docs/proto3#generating
* protobuf compiler releases - https://github.com/protocolbuffers/protobuf/releases/tag/v3.11.2


### Gen notes

Currently python and java are the tested targets. After installing protobuf compiler from the link above, this generates java and python artifacts
from the root of the checked-out repo


```

 protoc  --python_out=target/python --java_out=target/java src/v1/auth.proto

```