# Optimizely Agent Helm Chart

The Optimizely Agent allows you to run a proxy to Optimizely in your own infrastructure, to help prevent adblockers from interfering with A/B tests. This repository contains a Helm chart to make it easy to host the Optimizely Agent in your own Kubernetes infrastructure.

I am not affiliated in any way with Optimizely, Inc.

## Links

* <https://github.com/optimizely/agent>
* <https://docs.developers.optimizely.com/full-stack/docs/optimizely-agent>
* <https://hub.docker.com/r/optimizely/agent>
* [Config file reference](https://github.com/optimizely/agent/blob/master/config.yaml)

## Chart Repo

Add the following repo to use the chart:

```console
helm repo add optimizely-agent https://kieranajp.github.io/optimizely-agent-helm
```

