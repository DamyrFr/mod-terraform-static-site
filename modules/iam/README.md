# Local module : IAM

This module deploy a deployement user and tow roles for there actions :

* Push files (web assets) on S3 bucket
* Invalid cache on CDN (Cloudfront)

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| bucket\_arn | Hosting bucket ARN | `string` | `"arn:aws:s3:::*/*"` | no |
| cdn\_arn | Cloudfront distribution ARN | `string` | `"arn:aws:cloudfront::*:*/*"` | no |
| domain | The domain name | `string` | `"exemple.org"` | no |

## Outputs

No output.

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
