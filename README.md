# afterburner-helm-chart

To deploy afterburner in a kubernetes cluster.

Base on https://tanzu.vmware.com/developer/guides/deploy-spring-boot-application-production-helm/

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add afterburner https://perfana.github.io/afterburner-helm-chart
```

You can then run `helm search repo afterburner` to see the charts.

