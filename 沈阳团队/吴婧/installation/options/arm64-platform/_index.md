---
title: Running on ARM64 (Experimental)
---

_Available as of v2.2.0_

> **Important:**
>
> Running on an ARM64 platform is currently an experimental feature and is not yet officially supported in Rancher. Therefore, we do not recommend using ARM64 based nodes in a production environment.

The following options are available when using an ARM64 platform:

- Running Rancher on ARM64 based node(s)
  - Only [Docker Install](/docs/installation/other-installation-methods/single-node-docker)
- Create custom cluster and adding ARM64 based node(s)
  - Kubernetes cluster version must be 1.12 or higher
  - CNI Network Provider must be [Flannel](/docs/faq/networking/cni-providers/#flannel)
- Importing clusters that contain ARM64 based nodes
  - Kubernetes cluster version must be 1.12 or higher

Please see [Cluster Options](/docs/cluster-provisioning/rke-clusters/options/) how to configure the cluster options.

The following features are not tested:

- Monitoring, alerts, notifiers, pipelines and logging
- Launching apps from the catalog
