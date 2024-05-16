# terraform-rootmodule-template

This repository is a template for creating new Terraform root modules.  It includes the basic files and workflows for GitHub Actions that would be necessary for a new Terraform root module.

Files:

- `README.md`: Repository README file.
- `main.tf`: The main Terraform configuration file.
- `variables.tf`: The Terraform variables file.
- `outputs.tf`: The Terraform outputs file.
- `.github/actions/terraform_install/action.yml`: GitHub Actions composite reusable action for installing Terraform with tfenv.
- `.github/workflows/pull_request.yml`: GitHub Actions workflow for running Terraform plan on pull requests.
