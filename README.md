# Nmap
#Task: Local Network Port Scanning
## Tools used
-Nmap

## IP Range Scanned
192.168.100.0/24

##Nmap Commands Used (CMD cmdlets)
nmap -sn 192.168.100.0/24
nmap -sV 192.168.100.0/24
nmap -sS 192.168.100.0/24
nmap -sT 192.168.100.0/24
nmap -sU 192.168.100.0/24

## Findings
When performed the -sV scan on local network, the scan showed that the port 23/tcp is open on ip: 192.168.100.1
The ip address belongs to a router is the local network.
This port (23/tcp) runs telnet server which is vulnerable.
Telnet services can also be exploited to leak information about the server (such as hostnames, IP addresses and brand) by packet sniffing the banner.

