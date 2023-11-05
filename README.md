# docker-pipoe
Docker image for running [pipoe](https://pypi.org/project/pipoe/)

## Usage

```bash
podman run --rm -it -v $PWD:/work pipoe:latest pipoe --python python3 -p glob2
```
