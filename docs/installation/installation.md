---
title: "Installation"
weight: 20
---

This section contains instructions for installing K3s in various environments. Please ensure you have met the [Requirements](/docs/installation/requirements/) before you begin installing K3s.

[Configuration Options](/docs/installation/configuration/) provides guidance on the options available to you when installing K3s.

[High Availability with an External DB](/docs/installation/ha/) details how to set up an HA K3s cluster backed by an external datastore such as MySQL, PostgreSQL, or etcd.

[High Availability with Embedded DB](/docs/installation/ha-embedded/) details how to set up an HA K3s cluster that leverages a built-in distributed database.

[Air-Gap Installation](/docs/installation/airgap/) details how to set up K3s in environments that do not have direct access to the Internet.

[Disable Components Flags](/docs/installation/disable-flags/) details how to set up K3s with etcd only nodes and controlplane only nodes

### Uninstalling

If you installed K3s with the help of the `install.sh` script, an uninstall script is generated during installation. The script is created on your node at `/usr/local/bin/k3s-uninstall.sh` (or as `k3s-agent-uninstall.sh`).