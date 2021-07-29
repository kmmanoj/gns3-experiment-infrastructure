# firewall

iptables as firewall

* Edit the iptables configuration via `iptables` command
* After configuring iptables via CLI persist the configuration by running `iptables-save > /configuration/iptables.conf`
* Restore the configuration by running `iptables-restore < /configuration/iptables.conf`
* Persist the directory `/configuration/` in GNS3, when creating the container template 
* Ensure to provide multiple interface when creating the container template