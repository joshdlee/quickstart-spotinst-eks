# quickstart-spotinst-on-eks
## Spotinst Ocean for Amazon EKS nodes on the AWS Cloud

This Quick Start sets up an Amazon Web Services (AWS) architecture for Spotinst Ocean for Amazon Elastic Container Service for Kubernetes (Amazon EKS) and deploys it into your AWS account in about 10 minutes.

Spotinst Ocean is an application scaling service. Similar to Amazon Elastic Compute Cloud (Amazon EC2) Auto Scaling groups, Spotinst Ocean is designed to optimize performance and costs by leveraging Spot Instances combined with On-Demand and Reserved Instances.

With Spotinst Ocean, you can run multiple instance types and sizes, sharing the same configuration or using different configurations, within the Amazon EKS cluster. Spotinst Ocean then leverages the variety of instances with a prediction algorithm to choose the best Spot instances for you in terms of price and availability and to predict the Spot Instance interruption 15 minutes ahead of time. When an interruption is predicted, Ocean immediately spins up a new node in a different Spot capacity pool.

This Quick Start uses AWS CloudFormation templates to deploy Spotinst Ocean for Amazon EKS into a virtual private cloud (VPC) within a single AWS Region across multiple Availability Zones.

![Spotinst Ocean for Amazon EKS nodes architecture](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/spotinst-ocean-for-amazon-eks-nodes-on-aws-architecture-diagram.png)

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).
