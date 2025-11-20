# Barn Module

This Terraform module creates a simple barn resource using terraform_data.

## Usage

```hcl
module "barn" {
  source = "./modules/barn"
  
  name = "red-barn"
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
