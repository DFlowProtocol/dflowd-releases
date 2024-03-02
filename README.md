# dflowd

dflowd is the CLI and validator binary for the DFlow network. It is based on the Cosmos SDK.

## Installation

Releases are available on the [releases page](https://github.com/DFlowProtocol/dflowd-releases/releases/latest). Download the binary for your platform, untar, and move the binary to your path.

## Usage
```bash
dflowd --help
```

## CLI Examples

### Generate a key
You can generate a mnemonic for a DFlow wallet using the following command
```bash
dflowd keys add <name>
```

### Query auctions
```bash
dflowd query auction list-order-flow-auction
```
