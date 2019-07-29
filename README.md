This repository keeps
[SuSEfirewall2](https://github.com/openSUSE/susefirewall2) configuration files
in a central place after [removal of SuSEfirewall2 from
openSUSE](https://lists.opensuse.org/opensuse-factory/2019-01/msg00490.html).

For SuSEfirewall2 service configuration files placed in
/etc/sysconfig/SuSEfirewall2.d/services have been spread across many different
packages in openSUSE. These service files have been installed on demand so
that only those service files have been kept on the system for which actually
packages have been installed. A downside of this approach is that now after
decommission of SuSEfirewall2 it's difficult for users that still want to use
SuSEfirewall2 some way to get these service files.

Therefore this repository is now a central place to keep all SuSEfirewall2
service files for reference. Furthermore you can also find a piece of
fail2ban configuration for SuSEfirewall2.
