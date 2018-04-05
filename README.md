terraform-datadog-timeboard-rds
=================

Terraform module to create Datadog Timeboard for RDS.



Usage
-----

```hcl
module "timeboard_rds_beical-db-01" {
  source         = "github.com/traveloka/terraform-datadog-timeboard-rds.git?ref=0.1.0"
  product_domain = "${var.product_domain}"
  rds_name        = "${var.rds_name}"
}
```

Terraform Version
-----------------

This module was created using Terraform 0.11.5. 
So to be more safe, Terraform version 0.11.5 or newer is required to use this module.

Authors
-------

* [Karsten Ari Agathon](https://github.com/karstenaa)

License
-------

Apache 2 Licensed. See LICENSE for full details.
