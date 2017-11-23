# WebPagetest Docker Compose

Docker Compose files for private [WebPagetest](https://www.webpagetest.org/) instance.

## Usage

### Startup the WebPagetest server and agent

#### On Linux Server

Run the following commands, and access to http://localhost:4000
```bash
sudo modprobe ifb numifbs=1
docker-compose up
```

#### On MacOS PC
** MacOS does not support network shaping. **

Run the following command, and access to http://localhost:4000
```bash
docker-compose -f docker-compose.yml -f docker-compose-macos.yml up
```

### Installation Check

Access to http://localhost:4000.
You can watch the Installation Check page.

### Test test results
Test results are saved in `wpt_data` directory.
