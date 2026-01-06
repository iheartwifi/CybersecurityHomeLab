# CybersecurityHomeLab

<p>
	<img src="assets/proxmox.svg" alt="Proxmox" height="40" style="vertical-align:middle; margin-right:8px;" />
	<img src="assets/linux.svg" alt="Linux" height="40" style="vertical-align:middle; margin-right:8px;" />
	<img src="assets/windows.svg" alt="Windows" height="40" style="vertical-align:middle;" />
</p>

## Description

This homelab project is designed to create a controlled, virtualized environment for learning and practicing cybersecurity concepts, including network security, threat detection, system hardening, and incident response. Built on Proxmox, this setup provides an isolated sandbox where security scenarios can be safely tested without affecting production systems.

## Environment: Proxmox

### Infrastructure Setup

- Setting up a Proxmox server hosting multiple virtual machines to test virtualization, security, and routing scenarios in an isolated environment.
- Configuring a PfSense firewall, including WAN/LAN network management and internal routing.
- Creating and segmenting the network to isolate services using VLANs.
- Deploying Ubuntu machines for various roles and Windows Server, including:
	- Wazuh for monitoring and threat detection.
	- Docker containers for application testing.

## Project Objectives

- **Network Segmentation**: Learn and implement network isolation using VLANs and firewalls to prevent lateral movement.
- **Threat Detection**: Deploy and configure Wazuh for real-time security monitoring, log analysis, and threat detection.
- **Security Testing**: Test various attack scenarios, security configurations, and defensive measures in a safe environment.
- **System Hardening**: Practice hardening operating systems and applications to resist common vulnerabilities.
- **Incident Response**: Simulate and respond to security incidents to develop incident response procedures.
- **Containerization Security**: Evaluate and test Docker container security best practices and configurations.
