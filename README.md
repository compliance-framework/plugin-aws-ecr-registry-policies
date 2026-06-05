# plugin-aws-ecr-registry-policy

OPA policy bundle for AWS ECR registry-level compliance checks.

## Policies

| Policy | Description | Controls |
|--------|-------------|----------|
| `ecr_require_registry_scanning` | Registry must use an approved scanning mode | CC5.2, CC5.3, CC7.1 |

## data.json reference

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| `approved_registry_scan_types` | `string[]` | `["ENHANCED"]` | Allowed registry scan modes |
