System Health Monitor Script

Description
This bash script monitors system health by providing options to check disk usage, active services, memory status, CPU load, and email a full system report.

Usage
To change the Permissions ...
chmod +x menu.sh

To run the Script ...
./menu.sh
Required Packages

mailutils (or bsd-mailx) — for sending email
systemd (for systemctl)

sudo apt-get update
sudo apt-get install mailutils
Ensure your system is configured to send emails via the mail command.
