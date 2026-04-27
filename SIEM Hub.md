Wazuh SIEM Installation & Configuration Guide

This document contains the step-by-step commands used to set up the Wazuh SIEM on Ubuntu 22.04 and deploy the agent to a Windows 11 endpoint.

Ubuntu SIEM Setup (Wazuh Manager)

1. Update System
  
   `sudo apt update && sudo apt upgrade -y`

2. Install dependencies

   `sudo apt install curl apt-transport-https lsb-release gnupg2 -y`
   
3. Run Wazuh All-in-One Installation Script:
  
   `curl -sO [https://packages.wazuh.com/4.7/wazuh-install.sh](https://packages.wazuh.com/4.7/wazuh-install.sh) && sudo bash wazuh-install.sh -a`

   This script installs the Wazuh manager, indexer, and dashboard.

   Note: Once finished, the credentials (admin/password) will be displayed. Save them immediately.
