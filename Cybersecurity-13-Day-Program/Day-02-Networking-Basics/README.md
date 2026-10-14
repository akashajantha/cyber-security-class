DAY 02: NETWORKING BASICS

1. What is a Network?
A network connects devices so they can exchange data and share resources.

2. IP Addresses
- IPv4 example: 192.168.1.10
- Private IP addresses are used inside private networks.
- Public IP addresses are used for internet-facing communication.
- A subnet mask or CIDR prefix identifies the network portion of an address.

3. Common Protocols
TCP: reliable connection-oriented transport.
UDP: connectionless transport.
HTTP: web communication.
HTTPS: HTTP protected by TLS.
DNS: resolves domain names to IP addresses.
SSH: secure remote command-line access.

4. Common Ports
22 SSH; 53 DNS; 80 HTTP; 443 HTTPS; 25 SMTP (commonly used for mail transfer).

5. Useful Linux Commands
ip addr
ip route
ss -tuln
ping -c 4 8.8.8.8
hostname

Note: ping may fail if ICMP is blocked. ss -tuln lists local listening sockets; it does not scan remote systems.

6. DNS
DNS translates domain names into IP addresses. An A record maps a name to IPv4; an AAAA record maps it to IPv6.

LEARNING OUTCOME
Understand IP addresses, ports, protocols, DNS, and basic network inspection commands.
