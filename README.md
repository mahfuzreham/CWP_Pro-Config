# CWP Configuration Script

This script installs and configures **CWP (CentOS Web Panel)** according to the best practices for optimal performance, security, and configuration.
NOTE:
This script should only be installed on CentOS 7 or CentOS 8 Minimal.
The script will automatically check the CentOS version and install the appropriate supported version.
Features
The script performs the following tasks to optimize your server:

Network Configuration Optimization:

Configures network settings to enhance performance.
Configure DNS:

Adjusts DNS settings for more reliable domain name resolution.
Install the "Base" Package and Other Recommended Packages:

Installs necessary packages and dependencies that are essential for CWP and server performance.
Install and Configure CSF Firewall with Recommended Values:

Installs CSF (ConfigServer Security & Firewall) and configures it with recommended settings to secure the server.
Configure all php.ini Files with Recommended Values:

Optimizes PHP settings according to best practices, ensuring better security and performance for PHP applications.
Configure Recommended MySQL Settings:

Adjusts MySQL configuration for optimized performance and resource management.
Synchronize the Server Time with an NTP Server:

Ensures accurate server time by syncing with a Network Time Protocol (NTP) server.
Requirements
Operating System: CentOS 7 or 8 Minimal installation
Root Access: You must have root privileges to run the script
## Installation

To install and run the script, execute the following commands:

```bash
wget https://raw.githubusercontent.com/mahfuzreham/CWP_Pro-Config/master/cwp_pro_config.sh && bash cwp_pro_config.sh


