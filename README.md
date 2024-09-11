# Voting App
A comprehensive guide for setting up a Kubernetes cluster using Kind on an AWS EC2 instance, installing and configuring Argo CD, and deploying applications using Argo CD.

## Overview
This covers the steps to:
- Launch an AWS EC2 instance.
- Install Docker and Kind.
- Create a Kubernetes cluster using Kind.
- Install and access kubectl.
- Set up the Kubernetes Dashboard.
- Install and configure Argo CD.
- Connect and manage your Kubernetes cluster with Argo CD.

## Architecture
![4](https://github.com/user-attachments/assets/393283ff-aaad-459a-b753-4648bfc019cd)

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app which shows the results of the voting in real time

## Kuberentes Dashboard
![3](https://github.com/user-attachments/assets/8ad198eb-50c5-4833-8858-4cc01559cc21)

## ArgoCD
![2](https://github.com/user-attachments/assets/edcd8c56-79e9-4e7b-92aa-6055cc98657a)

## Voting
<img width="529" alt="5" src="https://github.com/user-attachments/assets/a638dff6-2775-4b61-a8be-a31ba9d61668">


## Voting results
![1](https://github.com/user-attachments/assets/8b85665c-5ef0-4135-81d4-5bdfd93ff60d)
