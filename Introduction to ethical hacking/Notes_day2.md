### Notes:

---

#### Day2

* Nmap - Port scanning tool.
* Metasploit - Exploiting tool available from company "rapid 7". Basic penetration testing.
* Burpsuite - Web exploitation. Tracking requests and responses used for security testing of web application or a website.
* Etter cap - Ethernet capture, network security tool. man in the middle attack.

* `Process of ethical hacking`:
* Scanning --> Gaining access --> Maintaining access --> Clearing tracks --> Reporting --> Reconnaissance --> Repeat
* Analogous to how to rob a bank.. : 
  * Information gathering.
  * Scanning.
  * Gaining the access: how to enter into the bank.
  * Mainting the access: Have control over the bank during the whole process. 
  * Clearing tracks.
  * Reporting back to organization.

---

* `Reconnaissance` - First step of hacking. It is also called as footprinting or information gathering phase. Preparatory phase where we collect as much info as possible. We usually collect info regarding: Network, Host, People involved.
* `Three types of scanning`:
  * Port scanning
  * Vulnerability scanning
  * Network mapping

* Demonstration no. 1: Hacking microsoft.com to get it's info step by step.
* Useful website- whoislookup- It is used to get useful IP adresses.
* `netdiscover` - command used to figure out the networks and machines working under an IP range.
* `nmap` - Stealth scan - nmap -SS (used to avoid tracks)
* In a tcp connection, the client and server interact with each other and if a hacker tries to gain info, this connection will be recorded in the TCP connection or firewall. Using stealth scan, this connection is not established and hence no track.
* nmap -sS -p- IP address (192.168.56.103) for this demo. (-p- is used to scan for every address and ports).
* 
