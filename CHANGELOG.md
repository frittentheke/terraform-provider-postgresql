## 0.1.2 (Unreleased)
## 0.1.1 (January 19, 2018)

DEPRECATED:

* `provider`: `sslmode` is the correct spelling for the various SSL modes.  Mark
  `ssl_mode` as the deprecated spelling.  In probably 6mo time `ssl_mode` will
  be removed as an alternate spelling.
  [https://github.com/terraform-providers/terraform-provider-postgresql/pull/27]

BUG FIXES:

* Mark Provider `password` as sensitive.
  [https://github.com/terraform-providers/terraform-provider-postgresql/pull/26]
* Fix destruction of databases created in RDS.
  [https://github.com/terraform-providers/terraform-provider-postgresql/issues/17]
* Fix DEFAULT values for the `postgresql_database` resource.
  [https://github.com/terraform-providers/terraform-provider-postgresql/issues/9]

## 0.1.0 (June 21, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
