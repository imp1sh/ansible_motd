# ansible_motd
Part of nftwall. Sets a beautiful ASCII art login screen together with helpful information about the host.

Example of motd variables making use of this role:
```
motd_purpose: "demo alpine system"
motd_site: "Information about the site. This is usually being defined with group_vars instead of host_vars."
```
