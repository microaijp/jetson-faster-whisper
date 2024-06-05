# jetson-faster-whisper
A Docker image for using faster-whisper on Jetson.

## Usage
```
$ docker run --rm -it --runtime=nvidia --name jetson-faster-whisper ghcr.io/microaijp/jetson-faster-whisper:latest
```

## Testing
After logging into the container:
```
# cd /root/
# python3 ./faster-whiper.py
```