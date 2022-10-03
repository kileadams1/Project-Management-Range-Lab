# Project-Management-Range-Lab

Current Goals:
- Lab Outline
- Lab Module HTML Document
- Build out Range VMs
- Screenshots
- Integration Test

https://github.com/chompie1337/SIGRed_RCE_PoC
https://www.youtube.com/watch?v=yiqLmfQCqeY
https://www.tenable.com/blog/cve-2020-1350-wormable-remote-code-execution-vulnerability-in-windows-dns-server-sigred
https://msrc.microsoft.com/update-guide/vulnerability/CVE-2020-1350


## Attack Stages:
1. Attacker performs reconaissance of Range network using Kali Linux box.
2. Attacker identifies vulnerable Microsoft DNS server.
3. Attacker uses Metasploit module to exploit vulnerability and gain DNS server RCE.
4. Hacker clones legitimate range site and hosts it on their Linux webserver.
5. Attacker modifies DNS ARP Tables to redirect the valid IP to hacker's Linux server.
6. Attacker / Range demoer then uses the compromised DNS server to visit the hacker's Linux webserver via the altered domain's table entry.
7. Attacker / Range demoer enters their credentials and the Attacker views these credentials.
