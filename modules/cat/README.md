# Cat Module

This Terraform module creates a simple cat resource using terraform_data.

## Usage

```hcl
module "cat" {
  source = "./modules/cat"
  
  name = "whiskers"
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
