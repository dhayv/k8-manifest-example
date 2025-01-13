# Understanding Kubernetes Manifests

**[Read the full guide here](https://dev.to/dhayv/understanding-kubernetes-manifests-a-beginners-guide-to-deployments-and-services-2h90)**

## Overview
This repository accompanies a comprehensive guide to understanding Kubernetes manifests, focusing on two fundamental resources: Deployments and Services. The guide breaks down the structure and purpose of basic Kubernetes YAML configurations that every developer should understand when starting with Kubernetes.

## Prerequisites
- Basic understanding of YAML syntax
- Kubernetes cluster (local or cloud-based)
- kubectl CLI installed
- Basic understanding of containers

## Repository Structure
```bash
Repository Structure:
├── deploy.yaml     # Deployment examples
├── service.yaml    # Service examples         
└── README.md       # Documentation
```

## Getting Started
### 1. Clone the Repository
```bash
git clone k8-manifest-example
cd k8-manifest-example
```

### 2. Follow the Guide
The accompanying blog post provides detailed explanations of:
- Basic Kubernetes manifest structure
- Understanding metadata, spec, and status
- Connecting Services to Deployments
- Port configurations and networking

### 3. Try the Examples
Examples in this repository correspond to the concepts explained in the guide. Use them to practice and understand the core concepts.

## Important Notes
1. The examples focus on basic configurations for learning purposes
2. Always refer to the official Kubernetes documentation for production use
3. YAML formatting is crucial - use proper indentation
4. Validate your manifests before applying them

## Additional Resources
- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
- [YAML Lint](http://www.yamllint.com/)
