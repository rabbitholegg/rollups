# OP Chain Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/boost-rollups)](https://artifacthub.io/packages/search?repo=boost-rollups)

> [!CAUTION]
> This repository is a work in progress and is not yet ready for production use.

This repository contains helm charts for deploying fresh OP Stack blockchains. It was originally forked from [op-charts](https://github.com/testinprod-io/op-charts) and has been standardized to deploy the latest canonical OP Stack components and provide a more consistent deployment experience.

## Install

```
helm repo add boost-rollups https://rabbitholegg.github.io/rollups
```

## Helmfile Example

An example Helmfile for deploying all these components together can be found [here](./example/).