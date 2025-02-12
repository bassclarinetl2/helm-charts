# Helm Charts

Add chart repository
```shell
$ helm repo add bassclarinetl2 https://bassclarinetl2.github.io/helm-charts/
```

## Install Charts
[Install Folding@Home via Helm](foldingathome)


## Publish Chart

```shell
$ helm package foldingathome
$ mv foldingathome-*.tgz docs
$ helm repo index docs --url https://bassclarinetl2.github.io/helm-charts/
```
