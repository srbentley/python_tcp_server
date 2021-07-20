# Python TCP Server in Docker Container

Multi-Threaded TCP Server that will accept binary data and send back a acknowledgement


## Prerequisites

* [Python 3.8.5 64-bit](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe)
* Docker
* Docker Compose

## Installing

Download the repository and run the following commands to build as a container.

```
docker-compose up --build -d
```

## Test
Run the client tcp.py to connect to the server
```
python3 client/tcp.py
```