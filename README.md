# Web Page Test Docker Compose

Compose files for private WebPagetest instance.

## Usage

### On Linux Server

run the following commands, and access to http://localhost:4000
```bash
sudo modprobe ifb numifbs=1
docker-compose up
```

### On MacOS PC
** MacOS does not support network shaping. **

run the following command, and access to http://localhost:4000
```bash
docker-compose -f docker-compose.yml -f docker-compose-macos.yml up
```
