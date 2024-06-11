# OP Chain Helmfile

This is an example of using boost-rollups to deploy a new OP Stack blockchain with some basic add-ons, including a [Blockscout](https://www.blockscout.com) instance.

## Configuration

You should be able to deploy this Helmfile as-is, but there are a few things you may want to customize. The best place to start is the [OP Stack: Getting Started](https://stack.optimism.io/docs/build/getting-started/) docs. After a quick pass, you should be ready to fill in the missing values in the Helmfiles.

### genesis.json

The `genesis.json` file needs to be uploaded somewhere that can be accessed over HTTP. The `op-geth` deployment will attempt to download the genesis file during the first run. You can use the [genesis.json](./genesis.json) file in this repository as a starting point.

### rollup.json

You also need to add the `rollup.json` file. It will be attached as a ConfigMap. You can either go through the OP Stack tutorial to generate this file or use the [rollup.json](./rollup.json) file in this repository as a starting point.
