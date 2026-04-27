Wazuh SIEM Installation & Configuration Guide

This document contains the step-by-step commands used to set up the Wazuh SIEM on Ubuntu 22.04 and deploy the agent to a Windows 11 endpoint.

Ubuntu SIEM Setup (Wazuh Manager)

1. Update System
`sudo apt update && sudo apt upgrade -y`

2. Install dependencies
`sudo apt install curl apt-transport-https lsb-release gnupg2 -y`
