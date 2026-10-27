# gcp-slz-configconnector

A placeholder for a Google Cloud Secure Landing Zone built with Terraform and
[Config Connector](https://cloud.google.com/config-connector/docs/overview). **The repository has no code yet.**

## Description

The repo was created to explore a variant of a Google Cloud Secure Landing Zone in which Config Connector manages
the organization's resources as Kubernetes custom resources (KRM YAML reconciled by a GKE cluster), with Terraform
used next to it. So far only the initial commit exists: this README and a `.gitignore`.

For a working Terraform-only landing zone (folders, groups, org policies, Shared VPC, logging, billing, and
business-unit projects), see the sibling repo [GCP-SLZ](https://github.com/Lapeyus/GCP-SLZ).

## Features

None yet. The repo contains no Terraform, no Config Connector manifests, and no scripts.

## Architecture

There is nothing to diagram yet. The design is not written down in this repo, so this README does not describe a
target architecture.

## Requirements

None for the current contents.

## Installation and quick start

```bash
git clone https://github.com/Lapeyus/gcp-slz-configconnector.git
```

There is nothing to run after cloning.

## Repository layout

```text
.
├── .gitignore   # Terraform ignores: .terraform/, *.tfstate*, *.tfvars, override files, CLI config
└── README.md
```

## Configuration

None. The `.gitignore` already excludes Terraform state, `*.tfvars` / `*.tfvars.json`, override files, and
`.terraformrc` / `terraform.rc`, so local variables and state stay out of Git once code is added.

## Tests

There are no tests.

## Status and known limitations

- **Status:** placeholder, inactive. The only commit is from 2023-10-04.
- No implementation exists.

## License

The repo has no `LICENSE` file.
