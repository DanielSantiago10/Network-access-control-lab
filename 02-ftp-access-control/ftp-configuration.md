# FTP Server Access Control

## Overview
The FTP server was configured with role-based access control to enforce the principle of least privilege.

## User Permissions

| Username | Permission |
|----------|-----------|
| cisco    | rwdnl     |
| jsmith   | rl        |
| bjones   | rl        |
| amin01   | rwdnl     |

## Explanation
- Full access users (rwdnl) can read, write, delete, rename, and list files
- Limited users (rl) can only read and list files

## Purpose
This ensures users only have access necessary for their roles, reducing risk.

## Evidence

![FTP Configuration](screenshots/ftp-users.png)
