# demo-node-apis
A set of node.js micro services to demonstrate cloud native API best practices

## Building and publishing the docker image

1. Authenticate to docker hub

```
docker build . -t adamfowleruk/address-book-manage-api:v0.1.4