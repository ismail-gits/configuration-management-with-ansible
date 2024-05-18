# Configuration Management with Ansible

This repository is dedicated to showcasing Ansible playbooks for configuration management tasks. Ansible is an open-source automation tool that simplifies IT orchestration, configuration management, and application deployment.

## Submodules

This repository is organized using Git submodules, each containing specific Ansible playbooks. Below are the submodules included:

### [ansible-playbook-with-roles](https://github.com/ismail-gits/ansible-playbook-with-roles)

This submodule demonstrates Ansible playbooks structured with roles for streamlined configuration management. Refer to the provided [README.md](https://github.com/ismail-gits/ansible-playbook-with-roles/blob/main/README.md) for detailed instructions.

### [ansible-playbook-aws-eks](https://github.com/ismail-gits/ansible-playbook-aws-eks)

These playbooks are tailored for managing deployments on Amazon EKS (Elastic Kubernetes Service) with Ansible. Find usage instructions in the [README.md](https://github.com/ismail-gits/ansible-playbook-aws-eks/blob/main/README.md) within this submodule.

### [ansible-playbook-docker-and-terraform](https://github.com/ismail-gits/ansible-playbook-docker-and-terraform)

Explore Ansible playbooks for orchestrating Docker containers alongside Terraform for infrastructure provisioning in this submodule. Refer to the [README.md](https://github.com/ismail-gits/ansible-playbook-docker-and-terraform/blob/main/README.md) for usage details.

### [ansible-playbook-dynamic-inventory](https://github.com/ismail-gits/ansible-playbook-dynamic-inventory)

Learn how to dynamically generate inventory for Ansible from various sources like cloud providers or databases with the playbooks in this submodule. Check the [README.md](https://github.com/ismail-gits/ansible-playbook-dynamic-inventory/blob/main/README.md) for instructions.

### [ansible-playbook-nexus-deployment](https://github.com/ismail-gits/ansible-playbook-nexus-deployment)

Automate the deployment and configuration of Sonatype Nexus, a repository manager, using Ansible playbooks available in this submodule. Refer to [README.md](https://github.com/ismail-gits/ansible-playbook-nexus-deployment/blob/main/README.md) for usage guidelines.

### [ansible-playbook-nodejs-app-deployment](https://github.com/ismail-gits/ansible-playbook-nodejs-app-deployment)

This submodule contains Ansible playbooks for deploying and managing Node.js applications in various environments. Detailed instructions can be found in the [README.md](https://github.com/ismail-gits/ansible-playbook-nodejs-app-deployment/blob/main/README.md).

## Usage

To clone this repository along with its submodules, use the following command:

```bash
git clone --recurse-submodules <repository_url>
```

If you've already cloned the repository without its submodules, initialize and update them using:

```bash
git submodule update --init --recursive
```