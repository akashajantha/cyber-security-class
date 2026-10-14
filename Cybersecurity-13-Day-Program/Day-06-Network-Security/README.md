DAY 06: NETWORK SECURITY

1. What is Network Security?
Network security protects network devices, services, traffic, and connections against unauthorized access and disruption.

2. Common Controls
Firewalls, network segmentation, secure remote access, intrusion detection/prevention, patch management, monitoring, and least-privilege access.

3. Useful Linux Commands
ip addr       Display network interfaces and addresses
ip route      Display routing table
ss -tuln      Show listening TCP/UDP sockets
ping -c 4 8.8.8.8   Test basic IP reachability where permitted
hostname      Display system hostname

4. Ports and Services
A listening port indicates a service is accepting connections locally. It does not automatically mean the service is exposed to the internet; firewall and cloud security-group rules also matter.

5. EC2 Security Group Basics
For a public website, HTTP TCP 80 and HTTPS TCP 443 may need inbound rules from the internet. SSH TCP 22 should generally be limited to trusted administrator IP addresses.

6. Defensive Checklist
Close unused ports, keep services updated, restrict administrative access, review firewall rules, and monitor logs.

LEARNING OUTCOME
Understand ports, listening services, network access controls, and basic network inspection.
