# Kubernetes_state Integration

## Overview

Get metrics from kubernetes_state service in real time to:

* Visualize and monitor kubernetes_state states
* Be notified about kubernetes_state failovers and events.

## Setup
### Installation

Install the `sd-agent-kubernetes_state` package manually or with your favorite configuration manager

### Configuration

Edit the `kubernetes_state.yaml` file to point to your server and port, set the masters to monitor. See the [sample kubernetes_state.yaml](https://github.com/serverdensity/sd-agent-core-plugins/blob/master/kubernetes_state/conf.yaml.example) for all available configuration options.

### Validation

When you run `sd-agent info` you should see something like the following:

    Checks
    ======

        kubernetes_state
        -----------
          - instance #0 [OK]
          - Collected 39 metrics, 0 events & 7 service checks

## Compatibility

The kubernetes_state check is compatible with all major platforms

## Data Collected
### Metrics
See [metadata.csv](metadata.csv) for a list of metrics provided by this integration.

