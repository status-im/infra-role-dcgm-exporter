# Description

This role configures [`dgcm-exporter`](https://github.com/NVIDIA/dcgm-exporter), a metrics exporter for nvidia [dgcm](https://developer.nvidia.com/dcgm), a suite of tools for managing and monitoring NVIDIA Datacenter GPUs.

# Installation

```yaml
- name: infra-role-dcgm-exporter
  src: git+git@github.com:status-im/infra-role-dcgm-exporter.git
  scm: git
```

# Configuration

The port `9400` need to be open for Prometheus to fetch the metrics.
