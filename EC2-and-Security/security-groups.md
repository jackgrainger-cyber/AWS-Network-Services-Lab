# Security Groups

- Created custom Security Group for EC2 instance.
- Allowed inbound **SSH (22)** and **HTTP (80)** from specific IPs only.
- Denied all other inbound traffic.
- Outbound traffic restricted to HTTPS.

**Key Learning:** Security Groups act as stateful firewalls at the instance level.
