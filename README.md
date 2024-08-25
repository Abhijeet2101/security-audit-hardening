# Security Audit and Hardening Script

## Overview
This script automates security audits and hardening processes on Linux servers.

## Usage
Run the script as root to perform security audits and hardening:

```bash
sudo ./security_audit_hardening.sh -c

for hardening only 
sudo ./security_audit_hardening.sh -H1~sudo ./security_audit_hardening.sh -H

For both checks and hardening 
sudo ./security_audit_hardening.sh -c -H
