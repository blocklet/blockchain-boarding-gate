# Blockchain Boarding Gate

> A simple blocklet that helps you to onboarding users to your forge-powered blockchain.

## Install on my ABT Node

[![Install on my ABT Node](https://raw.githubusercontent.com/blocklet/development-guide/main/assets/install_on_abtnode.svg)](https://install.arcblock.io/?action=blocklet-install&meta_url=https%3A%2F%2Fgithub.com%2Fblocklet%2Fblockchain-boarding-gate%2Freleases%2Fdownload%2F1.1.6%2Fblocklet.json)

## Getting started

### Configuration

Put following contents in `.env`:

```ini
SKIP_PREFLIGHT_CHECK=true

# server side
BLOCKLET_PORT="3030"
BLOCKLET_APP_SK="0x7ebe8ba807cb217c57563aeb96b5c4c755af29a4bb935d77b1af549edaddf3a09bff6e162bd8a2fbfb6284921ecc243c209339f2e14f5eb64c5f7e5dccdc6700"
BLOCKLET_APP_ID="zNKn6o1t7CPMWU4wrbNnLuzKvoPWMVyhVgaf"
BLOCKLET_DATA_DIR="/tmp/abtnode/blockchain-boarding-gate"

REACT_APP_BASE_URL="http://192.168.1.2:3030"
REACT_APP_APP_NAME="Blockchain Boarding Gate"
REACT_APP_API_PREFIX=""
```

### Start hacking

```shell
mkdir -p /tmp/abtnode/blockchain-boarding-gate
npm run start:server
npm run start:client
```

### Deploy to local ABT Node

```shell
blocklet deploy .
```
