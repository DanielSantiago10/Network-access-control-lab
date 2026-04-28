# Network-Based Firewall (ACL Configuration)

## Overview
An extended ACL was implemented on the router to control traffic to a web server.

## Configuration

```bash
enable
configure terminal

ip access-list extended webserver
 permit tcp host 192.168.3.2 any eq www

interface g6/0
 ip access-group admin1 out

exit
exit

show access-list
show access-list webserver
