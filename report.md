# Port Scanner Project

Every computer on a network has thousands 
of ports acting as entry points for different 
services and applications. Some ports are 
meant to be open. Most should not be. The 
problem is that without actively checking 
you have no idea which ones are exposed on 
your system. That is the problem this 
project set out to solve.

## What We Built
A Python-based port scanner developed from 
scratch using the socket library that 
systematically checks ports 1 through 1024 
on a target machine and identifies which 
ones are actively responding.

## Tools Used
- Python 3 and socket library
- Kali Linux
- Metasploitable VM
- Nmap

## What We Found
Over 15 ports came back open including:
- Port 21 — FTP with no encryption
- Port 23 — Telnet in plain text
- Port 3306 — MySQL exposed to network
- Port 512, 513, 514 — Remote access open

## What We Learned
Open ports are one of the most overlooked 
security risks in any network.

## Conclusion
Regular port scanning should be a standard 
part of any security audit.
