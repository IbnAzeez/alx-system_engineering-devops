0x08. Networking basics #1
Resources
Localhost wiki
0.0.0.0 wiki
How to Modify and Manage the Hosts File on Linux
Linux Netcat (nc) command examples

For reference:
TCP/IP Illustrated

man or help:
ifconfig
telnet
nc
cut
Learning Objectives
What is localhost/127.0.0.1
What is 0.0.0.0
What is /etc/hosts
How to display your machine’s active network interfaces
Tasks
0-localhost
Q: What is localhost?
A: A hostname that means /this computer/.
1-wildcard
Q: What is 0.0.0.0?
A: All IPv4 addresses on the local machine.
2-change_your_home_IP // a Bash script that configures an Ubuntu server with the below requirements.
Requirements:

localhost resolves to 127.0.0.2
facebook.com resolves to 8.8.8.8.
The checker is running on Docker, so make sure to read this
3-show_attached_IPs // a Bash script that displays all active IPv4 IPs on the machine it’s executed on.

4-port_listening_on_localhost // a Bash script that listens on port 98 on localhost.
