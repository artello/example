# orions-belt

Welcome to your insterra generated platform code. You can execute this code either via CLI from your local machine or via terraform cloud.

We recommend using terraform cloud for production setup.

## Terraform Cloud

Setup a free terraform cloud account and create a workspace. You'll need to connect the workspace to this repository. Follow the video below to learn more.

[![rick](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Terraform CLI

You'll need to install terraform on your local machine and create `.auto.tfvars` with the following content

```hcl
aws_access_key = "<replace with your values>"
aws_region = "<replace with your values>"
aws_secret_key = "<replace with your values>"
identifier = "orions-belt"
instellar_auth_token = "<replace with your values>"
instellar_host = "<replace with your values>"

```

Then simply run:

```bash
terraform init
terraform plan
terraform apply
```