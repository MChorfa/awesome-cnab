# CNAB [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome cnab (Cloud Native Applications Bundles)


## Contents

- [CNAB](#CNAB)

- [Platforms](#Platforms)

## CNAB

- [cnab.io](https://cnab.io/) - Learn all about CNAB
- [Specification](https://github.com/cnabio/cnab-spec) - Cloud Native Application Bundle Specification
- [cnab-community](https://github.com/cnabio/community) - This project collects the shared information about the CNAB projects
- [slack](https://cloud-native.slack.com/messages/CEX1W7WMD/) - CNCF Slack for discussions. Within the #cnab channel.
- [cnab-go](https://github.com/cnabio/cnab-go) - A Go implementation of CNAB Core 1.0
- [duffle](https://github.com/deislabs/duffle) - Duffle is the reference implementation of the CNAB specification
- [signy](https://github.com/cnabio/signy) - Signy is an experimental tool that implements the CNAB Security specification
- [cnab-to-oci](https://github.com/cnabio/cnab-to-oci) - Implementation for sharing a CNAB using an OCI
- [cnab-js](https://github.com/cnabio/cnabjs) - A JS library for loading and working with CNAB manifests.
- [cnab-rust](https://github.com/cnabio/cnab-rs) - This is a highly experimental (and currently unfinished) implementation of CNAB
- [cnab-workshop](https://github.com/deislabs/cnab-workshop) - CNAB / Duffle Workshop
- [oci-specification](https://github.com/opencontainers/image-spec) - OCI Image Format Specification
- [oci-runtime](https://github.com/opencontainers/runtime-spec) - Open Container Initiative Runtime Specification
- [oci-distribution](https://github.com/opencontainers/distribution-spec) - Open Container Initiative Distribution Specification
- [cnab-compatible-registries](https://cnab.io/registries/) - Compatible Registries

## Implementations

### Porter

- [porter.sh](https://porter.sh) - Learn all about Porter
- [porter-source](https://github.com/getporter/porter) - Porter makes CNAB bundles easier!
- [porter-community](https://github.com/getporter/community) -  Porter Community repo
- [Mailing List](https://porter.sh/mailing-list) - Great for following the project at a high level because it is low traffic
- [Slack](https://porter.sh/community/#slack) - Discuss #porter or #cnab with other users and the maintainers.
- [Open an Issue](https://github.com/deislabs/porter/issues/new/choose) - If you have a bug, feature request or question about Porter
- [skeletor](https://github.com/getporter/skeletor) - skeleton structure of a Porter Mixin
- [gh-action](https://github.com/getporter/gh-action) - Porter Setup Action. This action installs porter so that it can be used in pipelines
- [pipeline-demo](https://github.com/getporter/pipeline-demo) - This is an example bundle that uses the docker mixin along with a GitHub workflow to demonstrate how you can use a workflow with your bundle
- [porter-packages](https://github.com/getporter/packages) - This repository contains package listings for mixins and plugins available for Porter.
- [vscode-extension](https://github.com/getporter/vscode-extension) - kVisual Studio Code Porter Tools

#### Mixins

- [helm-mixin](https://github.com/getporter/helm-mixin) - Helm 2 Mixin for Porter
- [helm3-mixin](https://github.com/MChorfa/porter-helm3) - Helm 3 Mixin for Porter
- [kubernetes-mixin](https://github.com/getporter/kubernetes-mixin) - kubernetes Mixin for Porter
- [docker-mixin](https://github.com/getporter/docker-mixin) - Porter mixin provides the Docker CLI
- [docker-compose-mixin](https://github.com/getporter/docker-compose-mixin) - Porter mixin for the docker-compose CLI
- [terraform-mixin](https://github.com/getporter/terraform-mixin) - Terraform Mixin for Porter
- [gcloud-mixin](https://github.com/getporter/gcloud-mixin) - Porter mixin for the gcloud CLI
- [aws-mixin](https://github.com/getporter/aws-mixin) - Porter mixin for the AWS CLI
- [az-mixin](https://github.com/getporter/az-mixin) - An Azure CLI mixin for Porter
- [arm-mixin](https://github.com/getporter/arm-mixin) - A Porter Mixin for using ARM


#### Plugins

- [azure-plugins](https://github.com/getporter/azure-plugins) - Azure Plugins for Porter
- [hashicorp-plugins](https://github.com/dev-drprasad/porter-hashicorp-plugins) - Hashicorp's Vault plugin for Porter plugin


### Docker-App

- [docker-app](https://www.docker.com/products/docker-app) - Learn all about Docker-App
- [app](https://github.com/docker/app) - Docker-App implementation of CNAB


### Articles

- [The state of CNAB: Part 1](https://deislabs.io/posts/state-of-cnab-part-1/) The state of CNAB: Part 1 - CNAB Core
- [The state of CNAB: Part 2](https://deislabs.io/posts/state-of-cnab-part-2/) The state of CNAB: Part 2 - CNAB Registries
- [Bringing container magic to cloud](https://cloudblogs.microsoft.com/opensource/2019/09/10/cloud-native-application-bundle-cnab-1-0-updates/) - Bringing container magic to cloud-native applications
- [Pivotal Build Service](https://tanzu.vmware.com/content/blog/pivotal-build-service-now-alpha-assembles-and-updates-containers-in-kubernetes) - Pivotal Build Service, Now VMware Tanzu Function Service, Assembles and Updates Containers in Kubernetes


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mohamed Chorfa has waived all copyright and
related or neighboring rights to this work.
