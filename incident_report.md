# SOC Incident Report

## Incident
SSH Brute Force Attack Simulation

## Detection Method
System Log Monitoring using journalctl

## Tools Used
Kali Linux
Nmap
Hydra

## Observations
Multiple failed SSH login attempts detected.
Repeated authentication failures observed.

## Indicators of Compromise
- Failed password attempts
- Unauthorized login attempts
- SSH service targeted

## Mitigation
Disable password login
Use SSH keys
Install Fail2Ban
Enable monitoring alerts
