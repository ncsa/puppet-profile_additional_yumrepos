# DEPRECATED

> :warning: This module is no longer recommended for configuring yum repos or yum proxy.
> Instead use puppet-yum directly
>
> See [ncsa/control-repo/examples/common.yaml](https://github.com/ncsa/control-repo/blob/36fd465d9e322bf80ea9c16fc2a2645e1aef3cc7/examples/common.yaml)

# NCSA Puppet Profiles - Additional YumRepos

[![pdk-validate](https://github.com/ncsa/puppet-profile_additional_yumrepos/actions/workflows/pdk-validate.yml/badge.svg)](https://github.com/ncsa/puppet-profile_additional_yumrepos/actions/workflows/pdk-validate.yml)
 [![yamllint](https://github.com/ncsa/puppet-profile_additional_yumrepos/actions/workflows/yamllint.yml/badge.svg)](https://github.com/ncsa/puppet-profile_additional_yumrepos/actions/workflows/yamllint.yml)

Collect repo definitions from hiera and ensure they are created.

Can also optionally be used to define a global proxy in /etc/yum.conf
 
## Dependencies

- [puppet-yum](https://forge.puppet.com/modules/puppet/yum)
 
## Reference
 
### class profile_additional_yumrepos (
-    Hash $repo_list,
-    Optional[String] $proxy_url,

[REFERENCE.md](REFERENCE.md)
