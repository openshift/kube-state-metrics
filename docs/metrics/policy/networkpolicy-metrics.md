# Network Policy Metrics


| Metric name                           | Metric type | Description                                                                                                               | Labels/tags                                                                   | Status       |
| ------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------------ |
| kube_networkpolicy_annotations        | Gauge       | Kubernetes annotations converted to Prometheus labels controlled via [--metric-annotations-allowlist](../../developer/cli-arguments.md) | `namespace`=&lt;namespace name&gt; `networkpolicy`=&lt;networkpolicy name&gt; | EXPERIMENTAL |
| kube_networkpolicy_created            | Gauge       |                                                                                                                           | `namespace`=&lt;namespace name&gt; `networkpolicy`=&lt;networkpolicy name&gt; | EXPERIMENTAL |
| kube_networkpolicy_labels             | Gauge       | Kubernetes labels converted to Prometheus labels controlled via [--metric-labels-allowlist](../../developer/cli-arguments.md)           | `namespace`=&lt;namespace name&gt; `networkpolicy`=&lt;networkpolicy name&gt; | EXPERIMENTAL |
| kube_networkpolicy_spec_egress_rules  | Gauge       |                                                                                                                           | `namespace`=&lt;namespace name&gt; `networkpolicy`=&lt;networkpolicy name&gt; | EXPERIMENTAL |
| kube_networkpolicy_spec_ingress_rules | Gauge       |                                                                                                                           | `namespace`=&lt;namespace name&gt; `networkpolicy`=&lt;networkpolicy name&gt; | EXPERIMENTAL |
