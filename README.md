# helm-charts



## 使用

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add exxk https://iexxk.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
exxk` to see the charts.

To install the `nginx-file-browser`chart:

```bash
helm install my-nginx-file-browser exxk/nginx-file-browser
```

To uninstall the chart:

```bash
helm delete my-nginx-file-browser
```

