## Kubernetes basics

The idea of this repo is to learn how Kubernetes works both internal and practical.

We are gonna be using Minikube n first place to set up a local cluster and eventually move to a cloud hosted solution and Docker as our containerization tool

Our main goal is to learn the internal concepts of Kubernetes:

* Components (nodes, kublets, clusters, etc...).
* Architecture (how those components interact between each other and the cloud provider API as well).
* Understand security best practices.
* Optimize and automate vertical and horizontal scaling. 
* Standardize a deployment workflow (with CI/CD ideally).
* Cloud provider (TDB) basics.
* How to create jobs and schedulers.

We are planning to understand and include the following tools:
* Prometheus (monitoring and metrics).
* Grafana (analytics and monitoring).
* HPA (horizontal pod auto-scaling).

Progressively we are gonna be adding advanced concepts and good practices.

# Minikube and Docker setup

Note: this is only for local development.

Dependencies:

In a single line:
* Docker is an OS-level virtualization by using the Linux kernel functionalities to automatize and standardize software package delivery. Install Docker from [here](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository).
* Minikube is a local cluster (we are gonna deep dive into that soon) that makes "easier to learn and develop". Install Minikube from [here](https://minikube.sigs.k8s.io/docs/start/).

Note: Give permissions to Docker if you are not root user either by file system or user level.

# Kubernetes components glossary

* 
