# VPS Server Setup Script

This script automates the configuration of a VPS server to run multiple privacy-focused protocols and services, including:

- **nginx** with SSL (Let's Encrypt)
- **Xray** (VMess and VLESS protocols)
- **Trojan-Go** with WebSocket and TLS
- **Hysteria** (UDP protocol over WebSocket)
- **SSH** and **Dropbear**
- Firewall rules with UFW
- A convenient **management menu**

## Features

- Fully automated installation and configuration
- Supports domain-based SSL or fallback to IP
- Easy service management via a custom menu
- Secure setup with DNS validation
- Re-usable setup to prevent reinstallation

## Prerequisites

- A fresh Ubuntu/Debian server (recommended)
- Root access
- Domain name (optional, for SSL)
- DNS records configured if using a domain

## Installation

### Run the script directly from GitHub

```bash
curl -fsSL https://raw.githubusercontent.com/NETHEAD001-vpsscript/my-cloudfront-vpsscript/refs/heads/main/my-cloudfront-vpsscript | bash
      Or, download and run manually

          
            
            
          
          curl -O https://raw.githubusercontent.com/NETHEAD001-vpsscript/my-cloudfront-vpsscript/refs/heads/main/my-cloudfront-vpsscript
chmod +x my-cloudfront-vpsscript
sudo ./my-cloudfront-vpsscript
      Usage
After the script completes, use the command:

          
            
            
          
          menu
      to access the management menu.
Notes

Ensure your DNS settings are correct if using a domain for SSL.
The script creates a command menu accessible system-wide for easy management.
Customize passwords or configurations as needed within the script.

Disclaimer
This script is provided as-is. Use it at your own risk. Review the code before execution.
