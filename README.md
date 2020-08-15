# docs-terraform-public-modules

- [docs-terraform-public-modules](#docs-terraform-public-modules)
  - [Overview](#overview)
  - [Modules index](#modules-index)
    - [VPC Configruations](#vpc-configruations)
    - [EC2 Addons and Configurations](#ec2-addons-and-configurations)
    - [VPC Parts](#vpc-parts)
  - [CI\CD Approuch](#cicd-approuch)
  - [References](#references)

## Overview

Docs: [docs-terraform-public-modules][docs-home]

## Modules index

### VPC Configruations

| Module name | Module repo | Module registry | Notes |
| --- | --- | --- | --- |
| terraform-aws-btlabz-vpc-ha-2x | [GITHub][gh-vpc-ha-2x] | [TFRegistry][tf-vpc-ha-2x] | VPC, 2x AZs, HA NAT |
| terraform-aws-btlabz-vpc-ha-3x | [GITHub][gh-vpc-ha-3x] | [TFRegistry][tf-vpc-ha-2x] | VPC, 3x AZs, HA NAT |

### EC2 Addons and Configurations

| Module name | Module repo | Module registry | Notes |
| --- | --- | --- | --- |
| ... | ... | ... | ... |
| ... | ... | ... | ... |

### VPC Parts

| Module name | Module repo | Module registry | Notes |
| --- | --- | --- | --- |
| terraform-aws-btlabz-vpc-base | [GITHub][gh-vpc-base] | [TFRegistry][tf-vpc-base] | Basic VPC |
| terraform-aws-btlabz-nat-base | [GITHub][gh-nat-base] | [TFRegistry][tf-nat-base] | Basic NAT |
| terraform-aws-btlabz-pri-sn | [GITHub][gh-pri-sn] | [TFRegistry][tf-pri-sn] | Private network |
| terraform-aws-btlabz-pub-sn | [GITHub][gh-pub-sn] | [TFRegistry][tf-pub-sn] | Public network |

## CI\CD Approuch

CI\CD Layer ...

CI\CD Gists ...

Flow ...

## References

[docs-home]: <https://btower-labz.github.io/docs-terraform-public-modules/> "docs-terraform-public-modules"

[gh-vpc-base]: <https://github.com/btower-labz/terraform-aws-btlabz-vpc-base> "terraform-aws-btlabz-vpc-base"
[gh-nat-base]: <https://github.com/btower-labz/terraform-aws-btlabz-nat-base> "terraform-aws-btlabz-nat-base"
[gh-pri-sn]: <https://github.com/btower-labz/terraform-aws-btlabz-pri-sn> "terraform-aws-btlabz-pri-sn"
[gh-pub-sn]: <https://github.com/btower-labz/terraform-aws-btlabz-pub-sn> "terraform-aws-btlabz-pub-sn"
[gh-vpc-ha-2x]: <https://github.com/btower-labz/terraform-aws-btlabz-vpc-ha-2x> "terraform-aws-btlabz-vpc-ha-2x"
[gh-vpc-ha-3x]: <https://github.com/btower-labz/terraform-aws-btlabz-vpc-ha-3x> "terraform-aws-btlabz-vpc-ha-3x"

[tf-vpc-base]: <https://registry.terraform.io/modules/btower-labz/btlabz-vpc-base> "terraform-aws-btlabz-vpc-base"
[tf-nat-base]: <https://registry.terraform.io/modules/btower-labz/btlabz-nat-base> "terraform-aws-btlabz-nat-base"
[tf-pri-sn]: <https://registry.terraform.io/modules/btower-labz/btlabz-pri-sn> "terraform-aws-btlabz-pri-sn"
[tf-pub-sn]: <https://registry.terraform.io/modules/btower-labz/btlabz-pub-sn> "terraform-aws-btlabz-pub-sn"
[tf-vpc-ha-2x]: <https://registry.terraform.io/modules/btower-labz/btlabz-vpc-ha-2x> "terraform-aws-btlabz-vpc-ha-2x"
[tf-vpc-ha-3x]: <https://registry.terraform.io/modules/btower-labz/btlabz-vpc-ha-3x> "terraform-aws-btlabz-vpc-ha-3x"
