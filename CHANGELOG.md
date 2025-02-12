Changelog
=========

These versions correspond to Git tags.

## v0.5.0

 * Update Docker provider to new upstream `kreuzwerker/docker` (#5)

## v0.4.0

 * Upgrade to Terraform 0.13 (#2, #4)
   * Add `required_providers`
   * 0.13 no longer accepts attributes. Has to reference resources.
 * Terraform `required_version` is now `>= 0.13`

## v0.3.1

 * Terraform `required_version` is `~> 0.12` as this module does not work with 0.13 yet (#2)

## v0.3.0

 * Add variables `keep_locally` and `no_rmi`
 * Add outputs `dest_full`, `dest_full_sha`, and `sha256_digest`

## v0.2.0

 * Upgrade to Terraform 0.12

## v0.1.0

 * Initial release, Terraform 0.11 compatible
