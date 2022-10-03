# Project-Management-Range-Lab

Current Goals:
- Lab Outline
- Lab Module HTML Document
- Build out Range VMs
- Screenshots
- Integration Test

https://www.rapid7.com/db/vulnerabilities/msft-cve-2022-26820/


## Attack Stages:
1. Attacker performs reconaissance of Range network using Kali Linux box.
2. Attacker identifies vulnerable Microsoft DNS server.
3. Attacker uses Metasploit module to exploit vulnerability and gain DNS server RCE.
4. Hacker clones legitimate range site and hosts it on their Linux webserver.
5. Attacker modifies DNS ARP Tables to redirect the valid IP to hacker's Linux server.
6. Attacker / Range demoer then uses the compromised DNS server to visit the hacker's Linux webserver via the altered domain's table entry.
7. Attacker / Range demoer enters their credentials and the Attacker views these credentials.
