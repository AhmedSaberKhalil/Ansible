This project provides an automated and standardized way to provision a complete CI/CD environment using Ansible.
Instead of manually installing and configuring multiple DevOps tools across servers, the playbook delivers a fully orchestrated setup that is reliable, repeatable, and production-ready.

The automation installs and configures all core components required for modern CI/CD pipelines:

OpenJDK to support Java-based tools and Jenkins dependencies.

Docker for building and running containerized applications.

Jenkins for orchestrating continuous integration and continuous delivery workflows.

AWS CLI for programmatic interaction with AWS services.

eksctl and Amazon EKS for provisioning and managing Kubernetes clusters.

Amazon EBS for creating and attaching persistent storage volumes to EC2 instances.

