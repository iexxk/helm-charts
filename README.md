# helm-charts



## 使用

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add exxk https://github.com/iexxk/helm-charts
helm repo add <alias> https://<orgname>.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
exxk` to see the charts.

To install the <chart-name> chart:

```bash
helm install my-<chart-name> exxk/<chart-name>
```

To uninstall the chart:

    helm delete my-<chart-name>