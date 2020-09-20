# CNAB [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome cnab (Cloud Native Applications Bundles)


## Contents

- [CNAB](#CNAB)
- [Implementations](#Implementations)
- [Community-Projcts](#Community-Projcts)
- [Articles](#Articles)
- [Videos](#Videos)
- [Talks](#Talks)
- [Varia](#Varia)

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
- [cnab-dot-net](https://github.com/deislabs/cnab-netstandard) - .NET Standard 2.0 Client Library for CNAB
- [cnab-workshop](https://github.com/deislabs/cnab-workshop) - CNAB / Duffle Workshop
- [oci-specification](https://github.com/opencontainers/image-spec) - OCI Image Format Specification
- [oci-runtime](https://github.com/opencontainers/runtime-spec) - Open Container Initiative Runtime Specification
- [oci-distribution](https://github.com/opencontainers/distribution-spec) - Open Container Initiative Distribution Specification
- [cnab-compatible-registries](https://cnab.io/registries/) - Compatible Registries

## Bundles

- [CNAB-Quickstarts](https://github.com/Azure/azure-cnab-quickstarts)- Azure CNAB Quickstarts
- [KubeCon EU 2020](https://github.com/chris-crone/kubecon-eu-20)- Simplify Your Cloud Native Application Packaging and Deployment
- [porter-bundles](https://github.com/vdice/porter-bundles)- porter-bundles
- [duffle-bag](https://github.com/deislabs/duffle-bag)- A template for graphical user interfaces for working with CNAB bundles.


## Implementations

### Porter

- [porter.sh](https://porter.sh) - Learn all about Porter
- [porter-source](https://github.com/getporter/porter) - Porter makes CNAB bundles easier!
- [porter-community](https://github.com/getporter/community) -  Porter Community repo
- [mailing List](https://porter.sh/mailing-list) - Great for following the project at a high level because it is low traffic
- [slack](https://porter.sh/community/#slack) - Discuss #porter or #cnab with other users and the maintainers.
- [open an Issue](https://github.com/deislabs/porter/issues/new/choose) - If you have a bug, feature request or question about Porter
- [skeletor](https://github.com/getporter/skeletor) - skeleton structure of a Porter Mixin
- [gh-action](https://github.com/getporter/gh-action) - Porter Setup Action. This action installs porter so that it can be used in pipelines
- [pipeline-demo](https://github.com/getporter/pipeline-demo) - This is an example bundle that uses the docker mixin along with a GitHub workflow to demonstrate how you can use a workflow with your bundle
- [porter-packages](https://github.com/getporter/packages) - This repository contains package listings for mixins and plugins available for Porter.
- [vscode-extension](https://github.com/getporter/vscode-extension) - kVisual Studio Code Porter Tools

#### Mixins

- [helm-mixin](https://github.com/getporter/helm-mixin) - Helm 2 Mixin for Porter  by @get_porter
- [helm3-mixin](https://github.com/MChorfa/porter-helm3) - Helm 3 Mixin for Porter by @MChorfa
- [helm3-mixin](https://github.com/squillace/porter-helm3) - Helm3 Mixin for Porter by @ralph_squillace
- [kubernetes-mixin](https://github.com/getporter/kubernetes-mixin) - kubernetes Mixin for Porter  by @get_porter
- [docker-mixin](https://github.com/getporter/docker-mixin) - Porter mixin provides the Docker CLI  by @get_porter
- [docker-compose-mixin](https://github.com/getporter/docker-compose-mixin) - Porter mixin for the docker-compose CLI by @get_porter
- [terraform-mixin](https://github.com/getporter/terraform-mixin) - Terraform Mixin for Porter  by @get_porter
- [gcloud-mixin](https://github.com/getporter/gcloud-mixin) - Porter mixin for the gcloud CLI  by @get_porter
- [aws-mixin](https://github.com/getporter/aws-mixin) - Porter mixin for the AWS CLI  by @get_porter
- [az-mixin](https://github.com/getporter/az-mixin) - An Azure CLI mixin for Porter  by @get_porter
- [arm-mixin](https://github.com/getporter/arm-mixin) - A Porter Mixin for using ARM   by @get_porter
- [kustomize-mixin](https://github.com/donmstewart/porter-kustomize) - Kustomize Mixin for Porter  @donmstewart
- [jq-mixin](https://github.com/squillace/porter-jq) - JQ Mixin for Porter by @ralph_squillace
- [azure-functions-mixin](https://github.com/squillace/porter-azure-functions) - Azure Functions Mixin for Porter by @ralph_squillace
- [paconn-mixin](https://github.com/squillace/porter-paconn) - Paconn Mixin for Porter by @ralph_squillace

#### Plugins

- [azure-plugins](https://github.com/getporter/azure-plugins) - Azure Plugins for Porter  by @get_porter
- [hashicorp-plugins](https://github.com/dev-drprasad/porter-hashicorp-plugins) - Hashicorp's Vault plugin for Porter plugin  by @dev-drprasad


### Docker-App

- [docker-app](https://www.docker.com/products/docker-app) - Learn all about Docker-App
- [app](https://github.com/docker/app) - Docker-App implementation of CNAB
- [Docker Application Docs](https://docs.docker.com/engine/reference/commandline/app/) - Docs - A tool to build and manage Docker Applications

## Community-Projcts

- [openfaas-cnab](https://github.com/johnmccabe/openfaas-cnab) - OpenFaaS CNAB Duffle Packaging
- [buck-porter](https://github.com/technosophos/buck-cnab)- This is an example of using Buck and Porter together to create a Porter CRD.
- [lupo](https://github.com/jdolitsky/lupo)- lupo is a pre-processor for Porter which allows you to build bundles with Lua
- [cnab-azure-driver](https://github.com/deislabs/cnab-azure-driver) Azure CNAB Driver
- [pycnab](https://github.com/garethr/pycnab)- Python CNAB Library


## Articles

- [The state of CNAB: Part 1](https://deislabs.io/posts/state-of-cnab-part-1/) The state of CNAB: Part 1 - CNAB Core
- [The state of CNAB: Part 2](https://deislabs.io/posts/state-of-cnab-part-2/) The state of CNAB: Part 2 - CNAB Registries
- [Bringing container magic to cloud](https://cloudblogs.microsoft.com/opensource/2019/09/10/cloud-native-application-bundle-cnab-1-0-updates/) - Bringing container magic to cloud-native applications
- [Pivotal Build Service](https://tanzu.vmware.com/content/blog/pivotal-build-service-now-alpha-assembles-and-updates-containers-in-kubernetes) - Pivotal Build Service, Now VMware Tanzu Function Service, Assembles and Updates Containers in Kubernetes
- [powering-docker-app-next-steps-for-cnab](https://www.docker.com/blog/powering-docker-app-next-steps-for-cnab/) Powering Docker App: Next Steps for Cloud Native Application Bundles (CNAB)
- [Free Glue Code - Porter](https://carolynvanslyck.com/blog/2019/04/porter) - Free Glue Code - Porter

## Videos

- [Introducing CNAB](https://www.youtube.com/watch?v=26e5-UK4YRA)- Introducing Cloud Native Application Bundle (CNAB), standard for defining distributed applications
- [Intro to CNAB](https://www.youtube.com/watch?v=r6aqKhvdsRs)- Intro to CNAB: Packaging Cloud Native Applications with Multiple Toolchains - Chris Crone, Docker
- [Docker App and CNAB](https://www.youtube.com/watch?v=O3___BrE_MU)- Deploying Distributed Applications with Docker App and CNAB
- [Understanding-CNAB](https://www.youtube.com/watch?v=QE-zAyz3tbM) - Understanding Cloud Native Application Bundles (CNAB)
- [Understanding Cloud Native Application Bundles](https://www.youtube.com/embed/1FGMrv_xfqY) - understanding-cloud-native-application-bundles
- [Porter: Digital Ocean, Terraform, Kubernetes](https://www.youtube.com/embed/ciA1YuGOIo4) - A demo video of using Porter to deploy infrastructure to Digital Ocean and Kubernetes using Terraform and Helm.
- [Porter Bundle with K3D, Helm3 and Brigade by Nuno Do Carmo](https://www.youtube.com/embed/9egipQjUgD0) - Nuno Do Carmo demonstrates how to use Porter and CNAB to install Brigade on a new Kubernetes cluster using k3d and Helm.
- [Porter: An Opinionated CNAB Authoring Experience](https://www.youtube.com/embed/__fim6RIW1s) - Porter: An Opinionated CNAB Authoring Experience

## Talks

- [sharing-is-caring](https://kccnceu20.sched.com/event/Zemr/sharing-is-caring-push-your-cloud-application-to-an-oci-registry-silvin-lubecki-djordje-lukic-docker)
- [simplify-your-cloud-native-application](https://kccnceu20.sched.com/event/Zet9/simplify-your-cloud-native-application-packaging-and-deployments-chris-crone-docker)
- [deep-dive-harbor](https://kccnceu20.sched.com/event/Zexh/deep-dive-harbor-enterprise-cloud-native-artifact-registry-steven-zou-daniel-jiang-vmware)
- [notary-v2-introduction](https://kccnceu20.sched.com/event/Zewy/notary-v2-introduction-and-status-report-justin-cormack-docker-omar-paul-amazon)

## Varia

- [Registries that are [OCI compliant] Community Investigation](https://github.com/bloodorangeio/oci-conformance/tree/master/distribution-spec) - OCI Distribution Spec Conformance Results


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mohamed Chorfa has waived all copyright and
related or neighboring rights to this work.
