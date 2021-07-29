# dns-server

Bind9 DNS server

* Edit the DNS configuration in `/etc/bind`
* Start the DNS server by running `service named start`
* If you want to run the DNS in foreground, then run `named -f -u bind -4`
* Refer [this document](https://www.alibabacloud.com/blog/how-to-setup-dns-server-using-bind9-on-ubuntu-16-04_594469) for configuring DNS zones
* Persist the directory `/etc/bind/` in GNS3, when creating the container template 