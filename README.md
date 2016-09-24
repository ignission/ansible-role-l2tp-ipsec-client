# l2tp-ipsec-client
Installs xl2tpd and libreswan, provides a VPN client.

### Dependencies
None.

### Role variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|vpn_server|String|VPN server's host.|it.toyvpn.com|
|vpn_PSK|String|Pre-shared key.|toyvpn.com|
|vpn_username|String|Auth username.|freeit|
|vpn_password|String|Auth password|74158689|
|vpn_local_cidr|String|Local CIDR|192.168.1.0/24|
|vpn_mtu|Integer|Maximum Transmission Unit|1410|
|vpn_mru|Integer|Maximum Receive Unit|1410|
