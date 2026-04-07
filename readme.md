# 4640 Makeup Terraform Lab - Rachel Sen-Laurenz

## Terraform Errors and Fixes

### Screenshot of all errors

![all errors](/errors.png)

### Error 1: `route_tble_id` → `route_table_id` (typo)

### Error 2: `subnt_id` → `subnet_id` (typo)

### Error 3: `from_prt` → `from_port` (typo)

### Error 4: Wrong path to `cloud-init.yaml`

path included extra `/module/` directory. Changed `${path.module}/module/scripts/cloud-init.yaml` to `${path.module}/scripts/cloud-init.yaml`.

### Error 5: `aws_sbnet` → `aws_subnet` (typo)
