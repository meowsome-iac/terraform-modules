# terraform-modules
meowsome terraform modules

This repository contains a collection of Terraform modules for various resources.

## Available Modules

- [cat](./modules/cat) - Cat module for creating cat resources
- [dog](./modules/dog) - Dog module for creating dog resources
- [chicken](./modules/chicken) - Chicken module for creating chicken resources
- [farm](./modules/farm) - Farm module for creating farm resources
- [barn](./modules/barn) - Barn module for creating barn resources

## Usage

Each module can be used independently. See the individual module READMEs for detailed usage instructions.

Example:
```hcl
module "example" {
  source = "./modules/cat"
  
  name = "whiskers"
}
```

## Versioning

This repository uses [release-please](https://github.com/googleapis/release-please) for automated versioning and releases. Each module is versioned independently.
