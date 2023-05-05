# rosbot-xl-rosds

Working setups for ROSDS.

## Quick Start

### Clonning on ROSbot XL

```
git clone https://github.com/DominikN/rosbot-xl-rosds.git
cd rosbot-xl-rosds
```

### Choosing a DDS config

Uncomment one of four available options in `net.env` file.

For local connections use `LAN` options, and for connections with ROS DS use `VPN` option.

### Pulling the Docker Images

```
docker compose pull
```

### Starting the Docker Images

```
docker compose up -d
```

### Stopping the Docker Images

```
docker compose down
```