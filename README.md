# GameTunnel Core

GameTunnel is a custom transport extension for xray-core.

This repository is currently focused on internal testing and iterative development.

## Build

```bash
git clone https://github.com/it2konst/game-tun.git
cd game-tun
CGO_ENABLED=0 go build -o game-tun -trimpath -ldflags="-s -w" -v ./main
./game-tun version
```

Requires Go 1.22+.

## Details

Detailed setup, client/server examples, and advanced usage:

[transport/internet/gametunnel/README.md](./transport/internet/gametunnel/README.md)
