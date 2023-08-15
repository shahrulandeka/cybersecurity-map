# Cybersecurity Map
<h1>A comprehensive map to act as a guide book into the immeasurable world of Cybersecurity.</h1>

Editor's note* <br/>
Dear all, the intention of this repository is to list anything and everything related to the field of Cybersecurity. As I continue to learn about this industry, there is just too many things to digest. I feel like a kid in an all-you-can-eat buffet. Like a teen who just discovered who Zyzz is. Don't worry, it's a good thing.

Feel free to review this repository, or add anything to it.

<h2>Whether for good or bad, whichever path you choose to take, have a firm conviction and believe in yourself.</h2>

Languages:
1. Javascript
2. Java
3. HTML
4. Python
5. SQL
6. R
7. Lisp
8. C
9. C#
10. C++
11. CSS
12. PHP
13. Ruby
14. Rust
15. Fortran
16. Haskell
17. Dart
18. Scala
19. Typescript
20. Solidity
21. Swift


Tools:
1.	Burp Suite
2.	Nessus
3.	OpenVAS
4.	Scapy
5.	Wireshark
6.	Nmap
7.	SQLMap
8.	SSLyze
9.	THC-IPV6
10.	BeEF
11.	ELK Stack
12.	Splunk

Frameworks:
1.	NIST Cybersecurity Framework
2.	Cyber Kill Chain
3.	PASTA Threat Model Framework (Process for Attack Simulation and Threat Analysis)
   - Popularly used across many industries
   - 7 steps
     1. Define the business and security objectives - Before starting, team needs to what their goals are. E.g. Protect customer data. Ask a LOT of questions. Understand things like how PII is handled.
     2. Define the technical scope - Team's focus is to identify the application components that must be evaluated. E.g Identify attack surface.
     3. Decompose the application - Identify the existing controls that will protect user data from threats. Normally means working with application developers to produce a data flow diagram.
     4. Perform a threat analysis - Team gets into their attacker mindset. Do research, collect latest information on the types of attack being used. Attack vectors change regularly, so team would reference resources to stay up-to-date.
     5. Perform a vulnerability analysis - Perform deep investigation by considering the root of the problem. 
     6. Conduct attack modeling - Team would test the vulnerabilities that were analyzed by simulating attacks. Use an attack tree.
     7. Analyze risk and impact - Assemble all the information the team has collected from stage 1 to 6. By this stage, the team is in position to make an informed risk management recommendations to business stakeholders that align with their goals.

Methodologies:
1.	Challenger Sales Model

Concepts:
1. TCP/IP Model
2. Threat Modelling (The process of identifying assets, their vulnerabiliities and how each is exposed to threats)
   - A lengthy and detailed process usually performed by a group of individuals with years of experience in the field.
   - Considered to be an advanced skill in cybersecurity
   - Each threat model can be tailored differently, e.g. for network security, Information Security or application development.
   - 6 steps
     1. Define the scope - Determine what you're building by building an inventory of assets and classifying them.
     2. Identify threats - Define all potential threat actors, internal or external. After which you'll put together an Attack Tree.
     3. Characterize the environment - Apply an attacker mindset to the business. Factor in how customers or employees interact with the environment, as well as external partners and third party vendors.
     4. Analyze threats - Examine existing protections and identify gaps. Then, rank threats according to their assigned risk score.
     5. Mitigate risks - Create plan for defending against threats. Either you avoid risk, transfer it, reduce it or accept it.
     6. Evaluate findings - Document EVERYTHING during your exercise. Fixes should have been applied, makes notes of your successes. Record any lessons learned, so you can inform how you approach future threat models.
4. Attack Tree (A diagram that maps threats to assets)
   - [Example 1]<br><img src="https://i.imgur.com/xr4pW7b.png" height="80%" width="80%" alt="Example 1"/>
   - [Example 2]<br><img src="https://i.imgur.com/RCZjoMq.png" height="80%" width="80%" alt="Example 2"/>
   - [Example 3]<br><img src="https://i.imgur.com/drK6qz8.png" height="80%" width="80%" alt="Example 3"/>

Types of Attacks:
1. Cross Site Scripting (XSS)(Used to steal sensitive information)
   - Reflected 
   - Stored (hard to know whether a website is infected beforehand)
   - DOM-based (Document Object Model = basically source code of a website)(Malicious code can be seen in the URL e.g my.website.com/mything?theme=<script>alert(1);</script>)

2. SQL Injection (Web-based exploit)(Occurs due to a lack of sanitized input)
   - In-band (Classic)(uses the same communication channel to launch the attack and gather the results. E.g. Search box)
   - Out-of-band (Uncommon)(uses a different communication channel  to launch the attack and gather the results.)
   - Inferential (Blind)(unable to directly see the results of their attack.)(interpret results by analyzing the behavior of the system)
   - To defend against this attack,
       - Prepared Statement: coding technique that executes SQL statements before passing them on to the database
       - Input sanitization: programming that removes user input which could be interpreted as code.
       - Input validation: programming that ensures user input meets a system's expectations.
    - [Useful link](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/05-Testing_for_SQL_Injection)

Network Protocols:
1.	TCP (Transmission Control Protocol)
2.	IP (Internet Protocol)
3.	UDP (User Datagram Protocol)
4.	POP (Post office Protocol)
5.	SMTP (Simple mail transport Protocol)
6.	FTP (File Transfer Protocol)
7.	HTTP (Hyper Text Transfer Protocol)
8.	HTTPS (Hyper Text Transfer Protocol Secure)
9.	Telnet
10.	Gopher
11.	ARP (Address Resolution Protocol)
12.	DHCP (Dynamic Host Configuration Protocol)
13.	IMAP4 (Internet Message Access Protocol)
14.	SIP (Session Initiation Protocol)
15.	RTP (Real-Time Transport Protocol)
16.	RLP (Resource Location Protocol)
17.	RAP (Route Access Protocol)
18.	L2TP (Layer Two Tunneling Protocol)
19.	PPTP (Point To Point Tunneling Protocol)
20.	SNMP (Simple Network Management Protocol)
21.	TFTP (Trivial File Transfer Protocol)
22.	IDS (Intrusion Detection System)
23.	IPS (Intrusion Prevention System)
24.	IDE (Integrated Development Software

Types of Malware:
1. Virus
2. Worm
3. Trojan
4. Ransomware
5. Spyware
6. Adware
7. Phishing
8. Rootkit
9. Backdoor
10. Keystroke Logging
11. Bot
12. Botnet
13. Logic Bomb
14. Fileless Malware
15. Mobile Malware
16. Wiper Malware
17. Malvertising


Acronyms:
1. CSV Comma-seperated Values
2. TSV Tab-seperated values
3. MITM Man-In-The-Middle
4. DOS Denial-of-Service
5. DDOS Distributed Denial-of-Service
