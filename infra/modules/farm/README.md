# Farm Module

This Terraform module creates a simple farm resource using terraform_data.

## Usage

```hcl
module "farm" {
  source = "./modules/farm"
  
  name = "green-acres"
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
