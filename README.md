# EKS Cluster Config

eksctl YAML configuration for creating an EKS cluster. Used by `terraform-aws-workstation` to auto-provision a cluster on EC2 startup.

## Files

| File | Purpose |
|---|---|
| `eks.yaml` | eksctl cluster specification (node groups, version, region) |

## Quick Start

```bash
eksctl create cluster -f eks.yaml
```