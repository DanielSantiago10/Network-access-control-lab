---

## 🔹 04 → `rationale.md` 

```md
# Security Analysis

## Network Segmentation
Network segmentation was achieved using host-based firewall rules that allow traffic from the administrative subnet while denying other networks. This limits access to trusted sources and reduces the attack surface.

## Least Privilege
The FTP server enforces least privilege by assigning permissions based on user roles. Administrative users have full access, while standard users are restricted to read-only capabilities.

## Network Isolation
Extended ACLs were used to restrict traffic at the network level. By allowing only HTTP traffic to the web server, the configuration ensures controlled communication between systems.
