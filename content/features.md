---
title: "Features"
---

This application uses a lot of other tech to achieve a small subset of services similar to popular cloud vendors.

* VM Builds - Automate the build of VMs with easy set up and run, using packer and targeting vcenter. Output of builds is tracked and managed, to make consumption of the output easy for provisioning and other builds.

* VM Provisioning - Using cloud-init on top of linux, allow for quick, flexible and easy provisioning and configuration of linux machines. Uses the output of the VM builds for the base VM images.

* DNS - Integration with DNS tool, PowerDNS, to automate the creation of DNS records. Similar to Route53.

* Load Balancing - Designed for the express purpose of load balancing across docker containers, not a general load balancing solution. Similar to ALBs.

* Scaling Groups - All the creation of a collection of similar servers via a Scaling Group. Scaling groups can be easily resized to grow or shrink the collection as required, ideally quickly. Similar to an AWS autoscaling group but more simple.

* Environment creation - Using a declarative syntac, deploy a set of Scaling Groups using a particular configuration. Similar to CloudFormation. Also provide the ability to deploy a swarm stack into a docker swarm environment.

* Networking - Allow automatic static IP assignment from a pool of IPs, and to also assist in management of DNS entries.

* Storage - Using minio, providing s3-like storage.
