# ![AWS](aws-logo.png) KMS customer-managed key (CMK)

Purpose: Configure a KMS key

## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| admins | A list of principal ARNs for key administrators | `list(string)` | `[]` | no |
| alias | An alias string associated with the key | `any` | `null` | no |
| description | The key description | `any` | `null` | no |
| users | A list of principal ARNs for key users | `list(string)` | `[]` | no |

## Outputs

| Name | Description |
|------|-------------|
| key\_arn | The ARN of the customer-managed key |

