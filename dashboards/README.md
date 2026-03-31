# SONiC Exporter Dashboards

This directory contains Grafana dashboards for the sonic-exporter These dashboards provide a comprehensive view of your SONiC Network Operating System (NOS) health and performance.

## 📊 Dashboard Overview

The included dashboard is designed to visualize metrics from all core collectors supported by the exporter:

* **Hardware (HW):** PSU status, Fan speeds, and thermal operation.
* **Interfaces:** throughput (bits/sec), packet rates, error counters.
* **Critical Resource Monitoring (CRM):** ACL, FDB, and Route table utilization.
* **Queues:** egress/ingress queue lenghts and packet drops.

## How to Import

1. Download the `sonic-exporter.json` file from this repository.
2. Import file in grafana
3. Select your Prometheus data source in the configuration screen.
