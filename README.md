# l2tp-ipsec-client
Installs xl2tpd and libreswan, provides a VPN client.

### Dependencies
None.

### Role variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|l2tp_ipsec_server_host|String|VPN server's host.|it.toyvpn.com|
|l2tp_ipsec_PSK|String|Pre-shared key.|toyvpn.com|
|l2tp_ipsec_client_username|String|Auth username.|freeit|
|l2tp_ipsec_client_password|String|Auth password|74158689|
|l2tp_ipsec_client_cidr|String|Local CIDR|192.168.1.0/24|
|l2tp_ipsec_mtu|Integer|Maximum Transmission Unit|1410|
|l2tp_ipsec_mru|Integer|Maximum Receive Unit|1410|
