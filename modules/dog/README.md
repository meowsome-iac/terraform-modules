# Dog Module

This Terraform module creates a simple dog resource using terraform_data.

## Usage

```hcl
module "dog" {
  source = "./modules/dog"
  
  name = "buddy"
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
