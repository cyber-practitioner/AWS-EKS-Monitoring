## Monitoring EKS & EC2 instances with MANAGED Prometheus & Grafana

This is based on a tutorial (You can find tutorial [here](https://youtu.be/-nUQNFAX5TI).)



# Monitoring EKS & EC2 instances with MANAGED Prometheus & Grafana

Welcome to the Monitoring EKS & EC2 Instances project! This project demonstrates how to monitor Amazon EKS (Elastic Kubernetes Service) and EC2 instances using AWS Managed Prometheus and Grafana.

## Overview

This project provides a setup for monitoring your Kubernetes clusters (EKS) and individual EC2 instances using the following components:

- AWS Managed Prometheus: A fully managed, highly available Prometheus service by AWS.
- Grafana: A popular open-source platform for monitoring and observability.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:

- An AWS account with the necessary permissions.
- AWS CLI installed and configured.
- Access to the AWS Management Console.

### Setup

1. **Create an AWS Managed Prometheus Workspace:**

   ```bash
   aws prometheus create-workspace --workspace-name <your-workspace-name>

