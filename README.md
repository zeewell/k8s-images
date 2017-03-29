# docker-library

kubernetes 相关 images 同步

--------------------------------------------------------------------------------

## images版本参见：

<https://console.cloud.google.com/gcr/images/google-containers/GLOBAL?project=google-containers>

## k8s 新版本发布后，可能需要更新的images有：

```
- kube-apiserver-amd64:v1.6.0-rc.1
- kube-controller-manager-amd64:v1.6.0-rc.1
- kube-proxy-amd64:v1.6.0-rc.1
- kube-scheduler-amd64:v1.6.0-rc.1
- kubernetes-dashboard-amd64:v1.6.0
```

## rpm版本

```
https://packages.cloud.google.com/yum/repos/kubernetes-el7-x86_64/repodata/primary.xml
```


## k8s v1.6.0 用到的 images


|                          Images                        | Version |
|                           :--                          |   --:  |
| gcr.io/google_containers/kube-apiserver-amd64          | v1.6.0 |
| gcr.io/google_containers/kube-controller-manager-amd64 | v1.6.0 |
| gcr.io/google_containers/kube-scheduler-amd64          | v1.6.0 |
| gcr.io/google_containers/kube-proxy-amd64              | v1.6.0 |
| gcr.io/google_containers/etcd-amd64                    | 3.0.17 |
| gcr.io/google_containers/pause-amd64                   | 3.0 |
| gcr.io/google_containers/k8s-dns-sidecar-amd64         | 1.14.1 |
| gcr.io/google_containers/k8s-dns-kube-dns-amd64        | 1.14.1 |
| gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64   | 1.14.1 |
