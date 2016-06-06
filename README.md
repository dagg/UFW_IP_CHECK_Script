# UFW IP CHECK Script
Script for assigning a UFW rule for specific IP retrieved from Dynamic DNS host for a specific port

Usage :
```
$ ipcheck_set_ufw_rule.sh <dynamic_dns_domain_name> <port> <protocol>
```

Where:
- 'dynamic_dns_domain_name' is a dynamic domain like one from No-IP or from DynDNS
- 'port' is the port to be opened as a UFW Rule and
- 'protocol' is the UFW Rule Protocol setting, eg: "UDP" or "TCP"

Example:
```
$ ipcheck_set_ufw_rule.sh testdomain.ddns.net 22 TCP
```
