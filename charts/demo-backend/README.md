# proxy

## v2fly as a tcp proxy

v2fly in kubernetes with ambassador gateway

## QuickStart

```bash
$ helm repo add proxy https://yushiwho.github.io/charts
$ helm repo update
$ helm install foo proxy/proxy --namespace proxy
```

## Introduction

This chart deploys v2fly

## Prerequisites

- Kubernetes 1.14+

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install my-release proxy/proxy --namespace proxy
```

> **Tip**: List all releases using `helm list`

In order to deploy this chart under Kubernetes 1.9+, the `k8sApiVersion` MUST be set to "apps/v1".

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
$ helm delete my-release --purge
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The configurable parameters of the chart and
their descriptions can be seen in `values.yaml`. 
> **Tip**: You can use the default [values.yaml](values.yaml)
