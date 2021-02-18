+++
title = "Amazon Elastic Load Balancing"
chapter = false
weight = 20
+++

## Introduction to Amazon Elastic Load Balancer (ELB)

### What to expect BlueGreen

This workshop shows some of the basic networking aspects of sharing a Load Balanced Application internally and externally.

Within your own AWS account, you can explore how to provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.

![End-to-end Apps](/images/r53-diagram.png)

You will use the following services:

- **AWS Network Load Balancers** for a scalable application
- **AWS Privatelink** and **Transit Gateway** for cross VPC communication
- **Amazon Route 53** for DNS and directing clients to the correct resource
