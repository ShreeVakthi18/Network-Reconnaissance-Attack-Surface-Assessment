# Nmap – Port Scanning and OS Detection Lab

## Overview
This lab demonstrates practical network reconnaissance using Nmap.  
The objective is to understand how port scanning and OS detection are used to assess a system’s network exposure.

## Tool & Environment
- Tool: Nmap  
- OS: Ubuntu Linux (WSL)  
- Target: Self system (local network IP)

## Methodology
- Performed basic TCP port scanning to identify open and closed ports  
- Used service version detection with the `-sV` option  
- Conducted OS detection using the `-O` option with root privileges  

## Observations
- The host was reachable on the network  
- All common TCP ports were found to be closed  
- No unnecessary services were exposed, indicating a hardened system  
- OS detection accuracy was limited due to the absence of open ports  

## Result
Successfully assessed the system’s network exposure using Nmap and identified a minimal attack surface.

## Ethical Notice
This lab was conducted only on my own system in a controlled environment.  
No unauthorized scanning of external systems was performed.

## Key Learnings
- Practical use of Nmap for port scanning and enumeration  
- Understanding how open ports contribute to an attack surface  
- Limitations of OS detection when services are not exposed  
- Importance of attack surface reduction for system security  

## Author
Third‑year Computer Science student with interest in Cybersecurity & Network Defense
