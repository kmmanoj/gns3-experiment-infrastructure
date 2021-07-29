FROM ubuntu
RUN apt-get update 
RUN apt-get install -y isc-dhcp-server
RUN touch /var/lib/dhcp/dhcpd.leases
RUN apt-get install -y iproute2 vim net-tools