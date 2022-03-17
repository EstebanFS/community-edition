| CPU | RAM  | Required software |
|:----|:-----|:------------------|
|2|8 GB|[Docker Desktop for Windows](https://docs.docker.com/desktop/mac/release-notes/#docker-desktop-420)<br> - Ensure your bootstrap machine is using [cgroup v1](https://man7.org/linux/man-pages/man7/cgroups.7.html). (Docker Desktop for Windows versions prior to 4.3.0 use cgroup1). For more information, see [Check and set the cgroup](../support-matrix/#check-and-set-the-cgroup).<br> - Note: Bootstrapping a cluster to Docker from a Windows bootstrap machine is currently experimental, for more information, see [Docker-based Clusters on Windows](../ref-windows-capd).|