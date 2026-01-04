# Development Log
This is where we keep track of various day-to-day developments.

## Chronolog

> January 1st, 2026
> - Provisioned VPS: Debian13/6GB RAM/2 CPU/3TB HDD
> - Configured prerequisites: `containerd`, `noswap`, `ufw ports`, etc.
> - Intialized Kubernetes Cluster with `kubeadm init`
> - Merged `admin.conf` with `~/.kube/config` on `kuap` for `kubectl`
> - Set `KUBECONFIG` environment variable to `~/kube/merged-config`
> - The default `kubectl context` is now the new `ark` cluster

> January 2nd, 2026
> - Installed `helm`, `openlens`, and `openjdk` on `kuap`
> - Added the `cillium` helm repository
> - Installed `cillium` as the `ark` CNI

> January 3rd, 2026
> - nothing much, hbu?
<!--stackedit_data:
eyJoaXN0b3J5IjpbODg5OTM4ODg5XX0=
-->