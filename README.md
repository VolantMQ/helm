# The VolantMQ Library for Kubernetes

All the charts here provided by [VolantMQ](https://volantmq.io), ready to launch on Kubernetes using [Kubernetes Helm](https://github.com/helm/helm).

## TL;DR

```bash
$ helm repo add volantmq https://volantmq.github.io/helm/
$ helm search repo volantmq
$ helm install my-release volantmq/<chart>
```
## Before you begin


### Install Helm

Helm is a tool for managing Kubernetes charts. Charts are packages of pre-configured Kubernetes resources.

To install Helm, refer to the [Helm install guide](https://github.com/helm/helm#install) and ensure that the `helm` binary is in the `PATH` of your shell.

### Add Repo

The following command allows you to download and install all the charts from this repository:

```bash
$ helm repo add volantmq https://volantmq.github.io/helm/
```

### Using Helm

Once you have installed the Helm client, you can deploy a VolantMQ Helm Chart into a Kubernetes cluster.

Please refer to the [Quick Start guide](https://github.com/helm/helm/blob/master/docs/quickstart.md) if you wish to get running in just a few commands, otherwise the [Using Helm Guide](https://github.com/helm/helm/blob/master/docs/using_helm.md) provides detailed instructions on how to use the Helm client to manage packages on your Kubernetes cluster.

Useful Helm Client Commands:
* View available charts: `helm search repo`
* Install a chart: `helm install my-release volantmq/<package-name>`
* Upgrade your application: `helm upgrade`


### Available Charts:
   - [VolantMQ](/charts/volantmq)