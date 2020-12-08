Random learnings on protobuf using https://www.youtube.com/watch?v=46O73On0gyI

To download the `protoc` compiler, find your OS here `https://github.com/protocolbuffers/protobuf/releases`

Run to generate the js file from `.proto` file.
```bash
<path_to_protoc_file> --js_out=import_style=commonjs,binary:. <proto_file>
```
e.g `~/Downloads/protoc-3.14.0-osx-x86_64/bin/protoc --js_out=import_style=commonjs,binary:. employees.proto`

#### Advantages
1. Schema
2. Size - small disk size
3. Language neutral

#### Disadvantages
1. Time to write and compile may just be the only disadvantage.
2. Maintaining protoc, if there are bugs then it affects your main app.
3. Need to have a schema.
