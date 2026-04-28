# Host-Based Firewall Configuration

## Overview
A host-based firewall was configured on Server 2 to control inbound traffic based on source networks.

## Rules Implemented

| Action | Protocol | Remote IP      | Wildcard Mask |
|--------|---------|---------------|---------------|
| Allow  | IP      | 192.168.1.0   | 0.0.0.255     |
| Deny   | IP      | 192.168.2.0   | 0.0.0.255     |
| Deny   | IP      | 192.168.3.0   | 0.0.0.255     |

## Purpose
This configuration ensures that only the administrative network can access the server while blocking other subnets.

## Evidence

![Host Firewall Policy](screenshots/host-firewall.png)
