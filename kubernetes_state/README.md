# Kubernetes_state Integration

## Overview

Get metrics from kubernetes_state service in real time to:

* Visualize and monitor kubernetes_state states
* Be notified about kubernetes_state failovers and events.

## Setup
### Installation

Install the `dd-check-kubernetes_state` package manually or with your favorite configuration manager

### Configuration

Edit the `kubernetes_state.yaml` file to point to your server and port, set the masters to monitor. See the [sample kubernetes_state.yaml](https://github.com/DataDog/integrations-core/blob/master/kubernetes_state/conf.yaml.example) for all available configuration options.

### Validation

[Run the Agent's `info` subcommand](https://help.datadoghq.com/hc/en-us/articles/203764635-Agent-Status-and-Information) and look for `kubernetes_state` under the Checks section:

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
See [metadata.csv](https://github.com/DataDog/integrations-core/blob/master/kubernetes_state/metadata.csv) for a list of metrics provided by this integration.

### Events
The Kubernetes-state check does not include any event at this time.

### Service Checks
The Kubernetes-state check does not include any service check at this time.

## Troubleshooting

If you have any questions about Datadog or a use case our [Docs](https://docs.datadoghq.com/) didn’t mention, we’d love to help! Here’s how you can reach out to us:

### Visit the Knowledge Base

Learn more about what you can do in Datadog on the [Support Knowledge Base](https://datadog.zendesk.com/agent/).

### Web Support

Messages in the [event stream](https://app.datadoghq.com/event/stream) containing **@support-datadog** will reach our Support Team. This is a convenient channel for referencing graph snapshots or a particular event. In addition, we have a livechat service available during the day (EST) from any page within the app.

### By Email

You can also contact our Support Team via email at [support@datadoghq.com](mailto:support@datadoghq.com).

### Over Slack

Reach out to our team and other Datadog users on [Slack](http://chat.datadoghq.com/).

## Further Reading
Learn more about infrastructure monitoring and all our integrations on [our blog](https://www.datadoghq.com/blog/)