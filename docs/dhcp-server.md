# DHCP Server Configuration

## Objective
Configure ISC DHCP Server.

## Scope
192.168.56.100 - 192.168.56.200

## Gateway
192.168.56.1

## DNS Servers
8.8.8.8
1.1.1.1

## Commands Used

apt install isc-dhcp-server

dhcpd -t

systemctl start isc-dhcp-server

journalctl -u isc-dhcp-server

ss -ulpn

## Result

Successfully configured enterprise DHCP service.
