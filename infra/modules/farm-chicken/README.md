# Chicken Module

This Terraform module creates a simple chicken resource using terraform_data.

## Usage

```hcl
module "chicken" {
  source = "./modules/chicken"
  
  name = "clucky"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| name | name | `string` | `""` | no |

## Outputs

| Name | Description |
|------|-------------|
| name | name |
