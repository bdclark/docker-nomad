# bdclark/nomad Docker Image

Simple Docker image to run Nomad.

### Description
This image is intended for use as a CLI tool, not a production client/server.
As such, there are no ports exposed, magic entrypoint scripts, etc.

### Example
```
docker run --rm -it \
  -e NOMAD_ADDR=$NOMAD_ADDR \
  bdclark/nomad job status
```
