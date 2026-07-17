# Wazuh SIEM Security Monitoring Lab

## Overview
Implemented a Wazuh SIEM environment to monitor security events in a Linux-based infrastructure.

## Architecture

Linux Mint (Agent)
        ↓
Wazuh Manager
        ↓
Wazuh Indexer
        ↓
Wazuh Dashboard

## Environment

- Ubuntu VM (Wazuh Manager, Indexer, Dashboard)
- Linux Mint Host (Wazuh Agent)

## Features

- Centralized log collection
- Security event monitoring
- SSH authentication monitoring
- Privilege escalation detection
- Application activity monitoring
- Threat detection and alert analysis

## Security Events Tested

### Failed SSH Login Detection
- Generated failed SSH login attempts
- Wazuh generated authentication alerts

### Unauthorized sudo Access
- Generated privilege escalation attempts
- Wazuh detected suspicious authentication events

### Application Monitoring
- Monitored package installation activities
- Generated software change logs

## Technologies

- Wazuh
- Ubuntu Linux
- Linux Mint
- Syslog
- SSH
- SIEM

## Skills Demonstrated

- SIEM Operations
- Security Monitoring
- Log Analysis
- Threat Detection
- Linux Administration
- Incident Detection
- Security Event Analysis
