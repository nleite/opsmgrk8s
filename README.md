# MongoDB.local Ops Manager Kubernetes

In this repository you will find the presentation and execution steps of the
[MongoDB Ops Manager + Kubernetes talk](https://sched.co/IJIU)

This presentation is supported by a [Jupyter](https://jupyter.org/) notebook
that explores the necessary steps to integrate [MongoDB Ops
Manager](https://www.mongodb.com/products/ops-manager) with a [Kubernetes
Cluster](https://kubernetes.io/) and a general review of Kubernetes and MongoDB
Clusters.

## Execute

To run this repository jupyter notebook execute the following steps:

- Create and enable a python virtual environment

```sh
python virtualenv venv
```

- Install ``jupyter``

```sh
pip install jupyter
```

- Run ``jupyter``

```sh
jupyter notebook opsmanager-kubernetes.ipynb
```
