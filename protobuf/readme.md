Random learnings on protobuf using https://www.youtube.com/watch?v=46O73On0gyI

To download the `protoc` compiler, find your OS here `https://github.com/protocolbuffers/protobuf/releases`

Run to generate the js file from `.proto` file.
```bash
<path_to_protoc_file> --js_out=import_style=commonjs,binary:. <proto_file>
```
e.g `~/Downloads/protoc-3.14.0-osx-x86_64/bin/protoc --js_out=import_style=commonjs,binary:. employees.proto`
