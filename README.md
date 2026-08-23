# Metrics Kubernetes system stack for Wodby

Metrics supplies Kubernetes resource and object-state metrics for Wodby cluster
operations.

This repository defines the Wodby stack manifests and default service
composition for Metrics.

<!-- wodby:generated:start -->

## Stack contract

- [Metrics stack on Wodby](https://wodby.com/stacks/metrics)
- [Wodby Kubernetes platform](https://wodby.com)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## System service definitions

- [Kube state metrics system service](https://github.com/wodby/service-kube-state-metrics)
- [Metrics server system service](https://github.com/wodby/service-metrics-server)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Kubernetes state metrics<br>`kube-state-metrics` | optional; enabled by default |
| Metrics server<br>`metrics-server` | optional; enabled by default |

System services are enabled or disabled according to the cluster provider and
infrastructure configuration.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
