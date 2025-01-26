---
title: Personal DIY Projects Management
tags:
  - devops
  - research
  - infosec
  - devsecops
  - self-hosted
  - cloud-services
  - DIY
  - docker
  - usage
  - solutions
  - architecture
  - k8s
---

>[!quote]
>*Most of those topics which i consider for contributing and find out the best way to apply this functionality, if you find the same mindset or want to collaboration, feel free meet me. Always wait with some reason* 😄😄😄

>[!note]
>The icon to telling you about what task is on progress or pending 😄
>
>- ✍ : On progressing, It usually attaches with `github` and blog
>- 🚧 : Pending, just stop like a note, and idea to doing something around that. Waiting for new information LOL
>- ✅ : Already hand on and release as blog, , find in [[All Blogs|all blogs page]]
>- ⌛ : On my way, just wait for couple weeks

# Kubewekend

Github: [kubewekend](https://github.com/Xeus-Territory/kubewekend)

>[!summary]
>Use the interesting and couple of candidate technologies for setting up Kubernetes cluster in locally. Learn and do some incredible thing with self-hosted and we capture that as the adventure to figure out and work with more concept of Kubernetes
## The major session ✍

- Session 1: Use `Vargrant` to configuration the VM with provider in `VirtualBox` ✅
- Session 2: Ansible - To setup and run script and bring up `kubernetes` cluster on locally, Use `kind` ✅
- Session 3: Exploring, understanding and provisioning require components inside the `kind` cluster ✅
- Session 4: `cilium` and `ebpf` - The powerful kernel service of `kubewekend` cluster ✅
- Session 5: How to build the High Availability (HA) Cluster.  ✅
- Session 6: Use extend `CSI` for volume and storage class with `Ceph` ✅
- Session 7: Setup new `app`, use `cilium` to route traffic into cluster via gateway ⌛
- Session 8: Setup the monitoring cluster inside the `kubernetes` with `node-exporter`, `prometheus` and `grafana` ⌛
- Session 9: Setup tracing, logging, profiling components in `kubewekend` cluster ⌛
## The extra session

- Session Extra 1: Longhorn and the story about NFS in Kubernetes ✅
- Session Extra 2: Rebuild Cluster with Rancher or K3S
- Session Extra 3: Combination GitOps with ArgoCD into Kubewekend Cluster
- Session Extra 4: Learn and use security, network context for Kubernetes
- Session Extra 5: Customize default scheduled in `kubernetes` cluster with `kube-scheduler` ⌛
- Session Extra 6: Service mesh inside Kubewekend Cluster
- Session Extra 7: Learn about virtualization inside Kubewekend with `kubevirt`
# Hackwekend

## HTTP Tunneling for secure connection 🚧

>[!summary]
>Tunneling the request to internet to HTTP and return response to currently browser like VPN but alternative

Reference technics : `ZTM (Zero Trust Mesh)` , `wstunnel`

## Lateral Movement Attack 🚧

>[!summary]
>Find the way to perform LM, how affect of them, provisioning lab and find the way to patching it.

# wouops
## Sidecar for remote profiling applications 🚧

>[!summary]
>Make a container can distribute and mental monitoring, profiling application with remotely by Sidecar pattern

![[design-sidecar-injection.png]]

## Pre-hook framework 🚧

Github: **[distribute-git-hook](https://github.com/wouops/distribute-git-hook)**

>[!summary]
>Create a framework on light weight and isolation components for check commit and push event in currently source code to repositories, with features like
>- Code smell and validate code for improving the code quality
>- Handling prehook for pentesting surface application on whitebox like secret leak, CVE, misconfiguration
>- Offer the announcement location, can be grafana or report with dashboard about your commit

# fast_deployment

>[!info]
>About the methodology which can apply for release or deploy the application which no down time, rapidly and more efficience work with script, DevOps circle

## Blue Green 🚧

>[!note]
>Feel free to read about small article about operating 👉 [[0-downtime with Blue-Green Deployment]]
## Canary 🚧

# DataOps and MLOps

## Milvus Cluster ✅

Documentation: https://milvus.io/docs

>[!info]
>Try to learn and explore vector database of Linux Foundation Opensource, and try to practical with feature and grasp the infrastructure of `milvus` with `kubewekend` cluster

