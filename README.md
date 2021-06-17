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
-    Optional[String] $proxy_host,

[REFERENCE.md](REFERENCE.md)
