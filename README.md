# Secure Ubuntu Web Server with Intrusion Detection and Prevention

## Project Overview

This project demonstrates the design and implementation of a secure Ubuntu-based web server environment.

The system combines web hosting, firewall protection, intrusion prevention, and intrusion detection technologies to improve the security of a Linux server.

## Technologies Used

- Ubuntu Server 26.04 LTS
- Apache2
- OpenSSH
- UFW Firewall
- Fail2Ban
- Suricata IDS
- VMware Workstation

## Objectives

- Deploy a web server using Apache2
- Configure secure SSH remote access
- Implement firewall protection using UFW
- Prevent brute-force attacks using Fail2Ban
- Detect suspicious network traffic using Suricata
- Monitor system and security logs

## System Architecture

Windows Host
│
VMware Workstation
│
Ubuntu Server
├── Apache2
├── SSH
├── UFW Firewall
├── Fail2Ban
└── Suricata IDS

## Features

### Web Hosting
Apache2 web server deployed successfully.

### Remote Administration
Secure remote administration through SSH.

### Firewall Protection
UFW configured to allow only required services.

### Intrusion Prevention
Fail2Ban configured to block repeated failed login attempts.

### Intrusion Detection
Suricata configured with over 50,000 detection rules.

## Testing

- Apache service tested
- SSH connectivity verified
- Firewall rules validated
- Fail2Ban status confirmed
- Suricata rule engine tested

## Screenshots

Screenshots are available in the screenshots folder.

## Author

Krishan