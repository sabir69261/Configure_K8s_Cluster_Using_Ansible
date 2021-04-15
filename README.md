# Configure K8S Multi Node Cluster over AWS Cloud Using Ansible Role
- Create Ansible role to launch 3 AWS EC2 Instance
- Create Ansible role to configure Docker over those instances.
- Create Playbook to configure K8S Master, K8S Worker Nodes on the above created EC2 Instances using kubeadm.

## What is Kubernetes?
Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.

## What is Ansible ?
Ansible is an open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intraservice orchestration, and provisioning.

## What is AWS ?
Amazon web service is a platform that offers flexible, reliable, scalable, easy-to-use and cost-effective cloud computing solutions.

## Let's discuss about the project
Here we have created one ec2 role which will configure the ec2 instance on the top of AWS cloud 
![Image of ec2](https://cdn-images-1.medium.com/max/800/1*6jiQWBFav4BW3p3A6KRe-A.png)

