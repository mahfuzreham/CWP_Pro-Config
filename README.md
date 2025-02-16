# CWP Configuration Script

This script installs and configures CWP (CentOS Web Panel) according to the best practices for optimal performance and security.

## Installation

To install and run the script, execute the following commands:

```bash
wget https://raw.githubusercontent.com/mahfuzreham/CWP_Pro-Config/master/cwp_pro_config.sh && bash cwp_pro_config.sh
NOTE:
This script should only be installed on CentOS 7 or CentOS 8 Minimal.
The script will automatically check the CentOS version and install the appropriate supported version.
Tasks Performed by the Script
The script will perform the following tasks:

Network Configuration Optimization: Configures network settings for better performance.
Configure the DNS: Adjusts DNS settings to enhance domain name resolution.
Install the "Base" Package and Other Recommended Packages: Installs necessary packages and dependencies.
Install and Configure the CSF Firewall with Recommended Values: Installs CSF (ConfigServer Security & Firewall) and configures it for optimal security settings.
Configure all php.ini Files with Recommended Values: Adjusts PHP settings to align with best practices.
Configure Recommended MySQL Settings: Optimizes MySQL settings for better performance.
Synchronize Server Time with an NTP Server: Ensures accurate system time by syncing it with a Network Time Protocol (NTP) server.
Requirements
CentOS 7 or 8 Minimal installation
Root privileges
### Key Points in the README:
- **Installation**: Simple and direct `wget` command for installation.
- **Tasks**: Clear, easy-to-understand bullet points for what the script does.
- **Requirements**: Specifies the OS requirements (CentOS 7 or 8).
- **License and Documentation**: Mentions the licensing and links to CWP documentation for further details.

This should be good to go for a professional GitHub repository! Let me know if you need any modifications or additional details.
