# charts
[![LICENSE](https://img.shields.io/github/license/kubevela/charts.svg?style=flat-square)](/LICENSE)

The chart repo for holding KubeVela's helm charts.

## Usage
```shell
helm repo add kubevela https://kubevela.github.io/charts/
helm repo update kubevela
```

## Install

```shell
helm install kubevela kubevela/vela-core # install vela-core
helm install kubevela kubevela/vela-workflow # install vela-workflow
```