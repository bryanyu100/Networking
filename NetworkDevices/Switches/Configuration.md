# Basic Configuration
```
enable
configure terminal
hostname S1
enable secret class
line console 0
password cisco
login
line vty 0 15
password cisco
login
exit
service password-encryption
banner motd #No unauthorized access allowed !#
do copy running-config startup-config
```

# Virtual Interface Configuration
```
configure terminal
interface vlan 1
ip address ip-address subnet_mask
no shutdown
exit
ip default-gateway ip-gateway-address
```
