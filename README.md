# Helm Chart Repository Using GitHub
This is an sample charts repository to test GitHub repository as Helm chart repository.

**This repository contains charts for below projects**
* [Application 1](charts/app1/)
* [Application 2](charts/app2/)

## Installing Charts from this Repository

**Add the Repository to Helm:**
```
    helm repo add helmchartrepo https://allwynthirupathi.github.io/helmchartrepo
```

**Install Application 1:**
```
    helm install myapp1 helmchartrepo/app1
```
**Install Application 2:**
```
    helm install myapp2 helmchartrepo/app2
```
