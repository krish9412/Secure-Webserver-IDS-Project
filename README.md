# Secure Ubuntu Web Server with IDS/IPS

## Overview

This project demonstrates the deployment and hardening of a secure Ubuntu Server environment using multiple layers of security controls.

The environment was built in VMware and includes:

* Apache2 Web Server
* OpenSSH Server
* UFW Firewall
* Fail2Ban Intrusion Prevention
* Suricata Intrusion Detection System (IDS)

## Security Features

### Web Server Security

* Apache2 deployed and configured
* Remote web access validated

### Secure Administration

* SSH enabled for remote management
* Administrative access restricted

### Firewall Protection

* UFW configured to allow only required services
* Ports 22, 80 and 443 managed through firewall rules

### Intrusion Prevention

* Fail2Ban configured to monitor SSH authentication attempts
* Automated blocking of suspicious login activity

### Intrusion Detection

* Suricata IDS deployed with updated community rules
* Over 50,000 active detection signatures loaded
* Network traffic inspection and alert generation enabled

## Technologies

* Ubuntu Server 26.04 LTS
* Apache2
* OpenSSH
* UFW
* Fail2Ban
* Suricata
* VMware Workstation

## Skills Demonstrated

* Linux Administration
* Web Server Deployment
* Network Security
* Firewall Configuration
* Intrusion Detection
* Intrusion Prevention
* Security Monitoring
* Virtualization

## Screenshots

See the screenshots directory for deployment, configuration, and testing evidence.

## Future Improvements

* HTTPS with SSL/TLS
* SIEM integration
* Centralized logging
* Multi-factor authentication
* Suricata IPS mode
