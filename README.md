# Hack The World With Ruby

> A collection of awesome penetration testing resources.

[Penetration testing](https://en.wikipedia.org/wiki/Penetration_test) is the practice of launching authorized, simulated attacks against computer systems and their physical infrastructure to expose potential security weaknesses and vulnerabilities.

Your contributions and suggestions are heartily♥ welcome. (✿◕‿◕). Please check the [Contributing Guidelines](CONTRIBUTING.md) for more details. This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

[This project is supported by Netsparker Web Application Security Scanner](https://www.netsparker.com/?utm_source=github.com&utm_content=awesome+penetration+testing&utm_medium=referral&utm_campaign=generic+advert)

## Contents

* [Anonymity Tools](#anonymity-tools)
* [Anti-virus Evasion Tools](#anti-virus-evasion-tools)
* [Books](#books)
  * [Defensive Programming Books](#defensive-programming-books)
  * [Hacker's Handbook Series Books](#hackers-handbook-series-books)
  * [Lock Picking Books](#lock-picking-books)
  * [Malware Analysis Books](#malware-analysis-books)
  * [Network Analysis Books](#network-analysis-books)
  * [Penetration Testing Books](#penetration-testing-books)
  * [Reverse Engineering Books](#reverse-engineering-books)
  * [Social Engineering Books](#social-engineering-books)
  * [Windows Books](#windows-books)
* [CTF Tools](#ctf-tools)
* [Collaboration Tools](#collaboration-tools)
* [Conferences and Events](#conferences-and-events)
* [Docker Containers](#docker-containers)
  * [Docker Containers of Intentionally Vulnerable Systems](#docker-containers-of-intentionally-vulnerable-systems)
  * [Docker Containers of Penetration Testing Distributions and Tools](#docker-containers-of-penetration-testing-distributions-and-tools)
* [File Format Analysis Tools](#file-format-analysis-tools)
* [GNU/Linux Utilities](#gnulinux-utilities)
* [Hash Cracking Tools](#hash-cracking-tools)
* [Hex Editors](#hex-editors)
* [Industrial Control and SCADA Systems](#industrial-control-and-scada-systems)
* [Multi-paradigm Frameworks](#multi-paradigm-frameworks)
* [Network Tools](#network-tools)
  * [DDoS Tools](#ddos-tools)
  * [Exfiltration Tools](#exfiltration-tools)
  * [Network Reconnaissance Tools](#network-reconnaissance-tools)
  * [Protocol Analyzers and Sniffers](#protocol-analyzers-and-sniffers)
  * [Network Traffic Replay and Editing Tools](#network-traffic-replay-and-editing-tools)
  * [Proxies and Machine-in-the-Middle (MITM) Tools](#proxies-and-machine-in-the-middle-mitm-tools)
  * [Transport Layer Security Tools](#transport-layer-security-tools)
  * [Wireless Network Tools](#wireless-network-tools)
* [Network Vulnerability Scanners](#network-vulnerability-scanners)
  * [Web Vulnerability Scanners](#web-vulnerability-scanners)
* [OSINT Tools](#osint-tools)
* [Online Resources](#online-resources)
  * [Online Code Samples and Examples](#online-code-samples-and-examples)
  * [Online Exploit Development Resources](#online-exploit-development-resources)
  * [Online Lock Picking Resources](#online-lock-picking-resources)
  * [Online Open Sources Intelligence (OSINT) Resources](#online-open-sources-intelligence-osint-resources)
  * [Online Operating Systems Resources](#online-operating-systems-resources)
  * [Online Penetration Testing Resources](#online-penetration-testing-resources)
  * [Online Social Engineering Resources](#online-social-engineering-resources)
  * [Other Lists Online](#other-lists-online)
  * [Penetration Testing Report Templates](#penetration-testing-report-templates)
* [Operating System Distributions](#operating-system-distributions)
* [Periodicals](#periodicals)
* [Physical Access Tools](#physical-access-tools)
* [Reverse Engineering Tools](#reverse-engineering-tools)
* [Security Education Courses](#security-education-courses)
* [Side-channel Tools](#side-channel-tools)
* [Social Engineering Tools](#social-engineering-tools)
* [Static Analyzers](#static-analyzers)
* [Vulnerability Databases](#vulnerability-databases)
* [Web Exploitation](#web-exploitation)
* [Android Utilities](#android-utilities)
* [Windows Utilities](#windows-utilities)
* [macOS Utilities](#macos-utilities)

## Anonymity Tools

* [I2P](https://geti2p.net/) - The Invisible Internet Project.
* [Nipe](https://github.com/GouveaHeitor/nipe) - Script to redirect all traffic from the machine to the Tor network.
* [OnionScan](https://onionscan.org/) - Tool for investigating the Dark Web by finding operational security issues introduced by Tor hidden service operators.
* [Tor](https://www.torproject.org/) - Free software and onion routed overlay network that helps you defend against traffic analysis.
* [What Every Browser Knows About You](http://webkay.robinlinus.com/) - Comprehensive detection page to test your own Web browser's configuration for privacy and identity leaks.
* [dos-over-tor](https://github.com/zacscott/dos-over-tor) - Proof of concept denial of service over Tor stress test tool.
* [kalitorify](https://github.com/brainfuckSec/kalitorify) - Transparent proxy through Tor for Kali Linux OS.

## Anti-virus Evasion Tools

* [AntiVirus Evasion Tool (AVET)](https://github.com/govolution/avet) - Post-process exploits containing executable files targeted for Windows machines to avoid being recognized by antivirus software.
* [CarbonCopy](https://github.com/paranoidninja/CarbonCopy) - Tool that creates a spoofed certificate of any online website and signs an Executable for AV evasion.
* [Hyperion](http://nullsecurity.net/tools/binary.html) - Runtime encryptor for 32-bit portable executables ("PE `.exe`s").
* [Shellter](https://www.shellterproject.com/) - Dynamic shellcode injection tool, and the first truly dynamic PE infector ever created.
* [UniByAv](https://github.com/Mr-Un1k0d3r/UniByAv) - Simple obfuscator that takes raw shellcode and generates Anti-Virus friendly executables by using a brute-forcable, 32-bit XOR key.
* [Veil](https://www.veil-framework.com/) - Generate metasploit payloads that bypass common anti-virus solutions.
* [peCloak.py](https://www.securitysift.com/pecloak-py-an-experiment-in-av-evasion/) - Automates the process of hiding a malicious Windows executable from antivirus (AV) detection.
* [peCloakCapstone](https://github.com/v-p-b/peCloakCapstone) - Multi-platform fork of the peCloak.py automated malware antivirus evasion tool.
* [shellsploit](https://github.com/Exploit-install/shellsploit-framework) - Generates custom shellcode, backdoors, injectors, optionally obfuscates every byte via encoders.

## Books

See also [DEF CON Suggested Reading](https://www.defcon.org/html/links/book-list.html).

### Defensive Programming Books

* [Holistic Info-Sec for Web Developers (Fascicle 0)](https://leanpub.com/holistic-infosec-for-web-developers)
* [Holistic Info-Sec for Web Developers (Fascicle 1)](https://leanpub.com/holistic-infosec-for-web-developers-fascicle1-vps-network-cloud-webapplications)

### Hacker's Handbook Series Books

* [Android Hacker's Handbook by Joshua J. Drake et al., 2014](http://www.wiley.com/WileyCDA/WileyTitle/productCd-111860864X.html)
* [Car Hacker's Handbook by Craig Smith, 2016](https://nostarch.com/carhacking)
* [The Browser Hacker's Handbook by Wade Alcorn et al., 2014](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118662091.html)
* [The Database Hacker's Handbook, David Litchfield et al., 2005](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0764578014.html)
* [The Mac Hacker's Handbook by Charlie Miller & Dino Dai Zovi, 2009](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0470395362.html)
* [The Mobile Application Hacker's Handbook by Dominic Chell et al., 2015](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118958500.html)
* [The Shellcoder's Handbook by Chris Anley et al., 2007](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047008023X.html)
* [The Web Application Hacker's Handbook by D. Stuttard, M. Pinto, 2011](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118026470.html)
* [iOS Hacker's Handbook by Charlie Miller et al., 2012](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118204123.html)

### Lock Picking Books

* [Eddie the Wire books](https://www.dropbox.com/sh/k3z4dm4vyyojp3o/AAAIXQuwMmNuCch_StLPUYm-a?dl=0)
* [Keys to the Kingdom by Deviant Ollam, 2012](https://www.elsevier.com/books/keys-to-the-kingdom/ollam/978-1-59749-983-5)
* [Lock Picking: Detail Overkill by Solomon](https://www.dropbox.com/s/y39ix9u9qpqffct/Lockpicking%20Detail%20Overkill.pdf?dl=0)
* [Practical Lock Picking by Deviant Ollam, 2012](https://www.elsevier.com/books/practical-lock-picking/ollam/978-1-59749-989-7)

### Malware Analysis Books

* [Malware Analyst's Cookbook and DVD by Michael Hale Ligh et al., 2010](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0470613033.html)
* [Practical Malware Analysis by Michael Sikorski & Andrew Honig, 2012](https://nostarch.com/malware)
* [The Art of Memory Forensics by Michael Hale Ligh et al., 2014](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118825098.html)

### Network Analysis Books

* [Network Forensics: Tracking Hackers through Cyberspace by Sherri Davidoff & Jonathan Ham, 2012](http://www.amazon.com/Network-Forensics-Tracking-Hackers-Cyberspace-ebook/dp/B008CG8CYU/)
* [Nmap Network Scanning by Gordon Fyodor Lyon, 2009](https://nmap.org/book/)
* [Practical Packet Analysis by Chris Sanders, 2011](https://nostarch.com/packet2.htm)
* [Wireshark Network Analysis by by Laura Chappell & Gerald Combs, 2012](https://www.amazon.com/Wireshark-Network-Analysis-Second-Certified/dp/1893939944)

### Penetration Testing Books

* [Advanced Penetration Testing by Wil Allsopp, 2017](https://www.amazon.com/Advanced-Penetration-Testing-Hacking-Networks/dp/1119367689/)
* [Advanced Penetration Testing for Highly-Secured Environments by Lee Allen, 2012](http://www.packtpub.com/networking-and-servers/advanced-penetration-testing-highly-secured-environments-ultimate-security-gu)
* [Advanced Persistent Threat Hacking: The Art and Science of Hacking Any Organization by Tyler Wrightson, 2014](http://www.amazon.com/Advanced-Persistent-Threat-Hacking-Organization/dp/0071828362)
* [Black Hat Python: Python Programming for Hackers and Pentesters by Justin Seitz, 2014](http://www.amazon.com/Black-Hat-Python-Programming-Pentesters/dp/1593275900)
* [Btfm: Blue Team Field Manual by Alan J White & Ben Clark, 2017](https://www.amazon.de/Blue-Team-Field-Manual-BTFM/dp/154101636X)
* [Bug Hunter's Diary by Tobias Klein, 2011](https://nostarch.com/bughunter)
* [Fuzzing: Brute Force Vulnerability Discovery by Michael Sutton et al., 2007](http://www.fuzzing.org/)
* [Metasploit: The Penetration Tester's Guide by David Kennedy et al., 2011](https://nostarch.com/metasploit)
* [Penetration Testing: A Hands-On Introduction to Hacking by Georgia Weidman, 2014](https://nostarch.com/pentesting)
* [Penetration Testing: Procedures & Methodologies by EC-Council, 2010](http://www.amazon.com/Penetration-Testing-Procedures-Methodologies-EC-Council/dp/1435483677)
* [Professional Penetration Testing by Thomas Wilhelm, 2013](https://www.elsevier.com/books/professional-penetration-testing/wilhelm/978-1-59749-993-4)
* [Rtfm: Red Team Field Manual by Ben Clark, 2014](http://www.amazon.com/Rtfm-Red-Team-Field-Manual/dp/1494295504/)
* [The Art of Exploitation by Jon Erickson, 2008](https://nostarch.com/hacking2.htm)
* [The Basics of Hacking and Penetration Testing by Patrick Engebretson, 2013](https://www.elsevier.com/books/the-basics-of-hacking-and-penetration-testing/engebretson/978-1-59749-655-1)
* [The Hacker Playbook by Peter Kim, 2014](http://www.amazon.com/The-Hacker-Playbook-Practical-Penetration/dp/1494932636/)
* [Unauthorised Access: Physical Penetration Testing For IT Security Teams by Wil Allsopp, 2010](http://www.amazon.com/Unauthorised-Access-Physical-Penetration-Security-ebook/dp/B005DIAPKE)
* [Violent Python by TJ O'Connor, 2012](https://www.elsevier.com/books/violent-python/unknown/978-1-59749-957-6)

### Reverse Engineering Books

* [Gray Hat Hacking The Ethical Hacker's Handbook by Daniel Regalado et al., 2015](http://www.amazon.com/Hacking-Ethical-Hackers-Handbook-Edition/dp/0071832386)
* [Hacking the Xbox by Andrew Huang, 2003](https://nostarch.com/xbox.htm)
* [Practical Reverse Engineering by Bruce Dang et al., 2014](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118787315.html)
* [Reverse Engineering for Beginners by Dennis Yurichev](http://beginners.re/)
* [The IDA Pro Book by Chris Eagle, 2011](https://nostarch.com/idapro2.htm)

### Social Engineering Books

* [Ghost in the Wires by Kevin D. Mitnick & William L. Simon, 2011](http://www.hachettebookgroup.com/titles/kevin-mitnick/ghost-in-the-wires/9780316134477/)
* [No Tech Hacking by Johnny Long & Jack Wiles, 2008](https://www.elsevier.com/books/no-tech-hacking/mitnick/978-1-59749-215-7)
* [Social Engineering in IT Security: Tools, Tactics, and Techniques by Sharon Conheady, 2014](https://www.mhprofessional.com/9780071818469-usa-social-engineering-in-it-security-tools-tactics-and-techniques-group)
* [The Art of Deception by Kevin D. Mitnick & William L. Simon, 2002](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471237124.html)
* [The Art of Intrusion by Kevin D. Mitnick & William L. Simon, 2005](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0764569597.html)
* [Unmasking the Social Engineer: The Human Element of Security by Christopher Hadnagy, 2014](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118608577.html)

### Windows Books

* [Troubleshooting with the Windows Sysinternals Tools by Mark Russinovich & Aaron Margosis, 2016](https://www.amazon.com/Troubleshooting-Windows-Sysinternals-Tools-2nd/dp/0735684448/)
* [Windows Internals by Mark Russinovich et al., 2012](http://www.amazon.com/Windows-Internals-Part-Developer-Reference/dp/0735648735/)

## CTF Tools

* [Pwntools](https://github.com/Gallopsled/pwntools) - Rapid exploit development framework built for use in CTFs.
* [RsaCtfTool](https://github.com/sourcekris/RsaCtfTool) - Decrypt data enciphered using weak RSA keys, and recover private keys from public keys using a variety of automated attacks.
* [ctf-tools](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools easily and quickly deployable to new machines.
* [shellpop](https://github.com/0x00-0x00/shellpop) - Easily generate sophisticated reverse or bind shell commands to help you save time during penetration tests.

## Collaboration Tools

* [RedELK](https://github.com/outflanknl/RedELK) - Track and alarm about Blue Team activities while providing better usability in long term offensive operations.

## Conferences and Events

* [44Con](https://44con.com/) - Annual Security Conference held in London.
* [AppSecUSA](https://appsecusa.org/) - Annual conference organized by OWASP.
* [BSides](http://www.securitybsides.com/) - Framework for organising and holding security conferences.
* [BalCCon](https://www.balccon.org) - Balkan Computer Congress, annually held in Novi Sad, Serbia.
* [Black Hat](http://www.blackhat.com/) - Annual security conference in Las Vegas.
* [BruCON](http://brucon.org) - Annual security conference in Belgium.
* [CCC](https://events.ccc.de/congress/) - Annual meeting of the international hacker scene in Germany.
* [CHCon](https://2016.chcon.nz/) - Christchurch Hacker Con, Only South Island of New Zealand hacker con.
* [CarolinaCon](https://carolinacon.org/) - Infosec conference, held annually in North Carolina.
* [DEF CON](https://www.defcon.org/) - Annual hacker convention in Las Vegas.
* [DeepSec](https://deepsec.net/) - Security Conference in Vienna, Austria.
* [DefCamp](http://def.camp/) - Largest Security Conference in Eastern Europe, held annually in Bucharest, Romania.
* [DerbyCon](https://www.derbycon.com/) - Annual hacker conference based in Louisville.
* [Ekoparty](http://www.ekoparty.org) - Largest Security Conference in Latin America, held annually in Buenos Aires, Argentina.
* [FSec](http://fsec.foi.hr) - FSec - Croatian Information Security Gathering in Varaždin, Croatia.
* [HITB](https://conference.hitb.org/) - Deep-knowledge security conference held in Malaysia and The Netherlands.
* [Hack.lu](https://2016.hack.lu/) - Annual conference held in Luxembourg.
* [Hackfest](https://hackfest.ca) - Largest hacking conference in Canada.
* [Infosecurity Europe](http://www.infosecurityeurope.com/) - Europe's number one information security event, held in London, UK.
* [LayerOne](http://www.layerone.org/) - Annual US security conference held every spring in Los Angeles.
* [Nullcon](http://nullcon.net/website/) - Annual conference in Delhi and Goa, India.
* [PhreakNIC](http://phreaknic.info/) - Technology conference held annually in middle Tennessee.
* [RSA Conference USA](https://www.rsaconference.com/) - Annual security conference in San Francisco, California, USA.
* [SECUINSIDE](http://secuinside.com) - Security Conference in [Seoul](https://en.wikipedia.org/wiki/Seoul).
* [ShmooCon](http://shmoocon.org/) - Annual US East coast hacker convention.
* [SkyDogCon](http://www.skydogcon.com/) - Technology conference in Nashville.
* [SummerCon](http://www.summercon.org/) - One of the oldest hacker conventions, held during Summer.
* [Swiss Cyber Storm](https://www.swisscyberstorm.com/) - Annual security conference in Lucerne, Switzerland.
* [ThotCon](http://thotcon.org/) - Annual US hacker conference held in Chicago.
* [Troopers](https://www.troopers.de) - Annual international IT Security event with workshops held in Heidelberg, Germany.
* [Virus Bulletin Conference](https://www.virusbulletin.com/conference/index) - Annual conference going to be held in Denver, USA for 2016.

## Docker Containers

### Docker Containers of Intentionally Vulnerable Systems

* [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/) - `docker pull citizenstig/dvwa`.
* [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--) - `docker pull bkimminich/juice-shop`.
* [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/) - `docker pull citizenstig/nowasp`.
* [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker) - `docker-compose build && docker-compose up`.
* [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/) - `docker pull ismisepaul/securityshepherd`.
* [OWASP WebGoat Project 7.1 docker image](https://hub.docker.com/r/webgoat/webgoat-7.1/) - `docker pull webgoat/webgoat-7.1`.
* [OWASP WebGoat Project 8.0 docker image](https://hub.docker.com/r/webgoat/webgoat-8.0/) - `docker pull webgoat/webgoat-8.0`.
* [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/) - `docker pull hmlio/vaas-cve-2014-0160`.
* [Vulnerability as a service: SambaCry](https://hub.docker.com/r/vulnerables/cve-2017-7494/) - `docker pull vulnerables/cve-2017-7494`.
* [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/) - `docker pull hmlio/vaas-cve-2014-6271`.
* [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/) - `docker pull wpscanteam/vulnerablewordpress`.

### Docker Containers of Penetration Testing Distributions and Tools

* [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/) - `docker pull diogomonica/docker-bench-security`.
* [Official Kali Linux](https://hub.docker.com/r/kalilinux/kali-linux-docker/) - `docker pull kalilinux/kali-linux-docker`.
* [Official OWASP ZAP](https://github.com/zaproxy/zaproxy) - `docker pull owasp/zap2docker-stable`.
* [Official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/) - `docker pull wpscanteam/wpscan`.
* [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/) - `docker pull opendns/security-ninjas`.
* [docker-metasploit](https://hub.docker.com/r/phocean/msf/) - `docker pull phocean/msf`.

## File Format Analysis Tools

* [Hachoir](https://hachoir.readthedocs.io/) - Python library to view and edit a binary stream as tree of fields and tools for metadata extraction.
* [Kaitai Struct](http://kaitai.io/) - File formats and network protocols dissection language and web IDE, generating parsers in C++, C#, Java, JavaScript, Perl, PHP, Python, Ruby.
* [Veles](https://codisec.com/veles/) - Binary data visualization and analysis tool.

## GNU/Linux Utilities

* [Hwacha](https://github.com/n00py/Hwacha) - Post-exploitation tool to quickly execute payloads via SSH on one or more Linux systems simultaneously.
* [LinEnum](https://github.com/rebootuser/LinEnum) - Scripted local Linux enumeration and privilege escalation checker useful for auditing a host and during CTF gaming.
* [Linux Exploit Suggester](https://github.com/PenturaLabs/Linux_Exploit_Suggester) - Heuristic reporting on potentially viable exploits for a given GNU/Linux system.
* [Lynis](https://cisofy.com/lynis/) - Auditing tool for UNIX-based systems.
* [checksec.sh](https://www.trapkit.de/tools/checksec.html) - Shell script designed to test what standard Linux OS and PaX security features are being used.
* [unix-privesc-check](https://github.com/pentestmonkey/unix-privesc-check) - Shell script to check for simple privilege escalation vectors on UNIX systems.

## Hash Cracking Tools

* [BruteForce Wallet](https://github.com/glv2/bruteforce-wallet) - Find the password of an encrypted wallet file (i.e. `wallet.dat`).
* [CeWL](https://digi.ninja/projects/cewl.php) - Generates custom wordlists by spidering a target's website and collecting unique words.
* [Hashcat](http://hashcat.net/hashcat/) - The more fast hash cracker.
* [hate_crack](https://github.com/trustedsec/hate_crack) - Tool for automating cracking methodologies through Hashcat.
* [JWT Cracker](https://github.com/lmammino/jwt-cracker) - Simple HS256 JSON Web Token (JWT) token brute force cracker.
* [John the Ripper](http://www.openwall.com/john/) - Fast password cracker.
* [Rar Crack](http://rarcrack.sourceforge.net) - RAR bruteforce cracker.
* [StegCracker](https://github.com/Paradoxis/StegCracker) - Steganography brute-force utility to uncover hidden data inside files.

## Hex Editors

* [0xED](http://www.suavetech.com/0xed/0xed.html) - Native macOS hex editor that supports plug-ins to display custom data types.
* [Bless](https://github.com/bwrsandman/Bless) - High quality, full featured, cross-platform graphical hex editor written in Gtk#.
* [Frhed](http://frhed.sourceforge.net/) - Binary file editor for Windows.
* [Hex Fiend](http://ridiculousfish.com/hexfiend/) - Fast, open source, hex editor for macOS with support for viewing  binary diffs.
* [HexEdit.js](https://hexed.it) - Browser-based hex editing.
* [Hexinator](https://hexinator.com/) - World's finest (proprietary, commercial) Hex Editor.
* [hexedit](https://github.com/pixel/hexedit) - Simple, fast, console-based hex editor.
* [wxHexEditor](http://www.wxhexeditor.org/) - Free GUI hex editor for GNU/Linux, macOS, and Windows.

## Industrial Control and SCADA Systems

See also [awesome-industrial-control-system-security](https://github.com/hslatman/awesome-industrial-control-system-security).

* [Industrial Exploitation Framework (ISF)](https://github.com/dark-lbp/isf) - Metasploit-like exploit framework based on routersploit designed to target Industrial Control Systems (ICS), SCADA devices, PLC firmware, and more. 
* [s7scan](https://github.com/klsecservices/s7scan) - Scanner for enumerating Siemens S7 PLCs on a TCP/IP or LLC network.

## Multi-paradigm Frameworks

* [Armitage](http://fastandeasyhacking.com/) - Java-based GUI front-end for the Metasploit Framework.
* [AutoSploit](https://github.com/NullArray/AutoSploit) - Automated mass exploiter, which collects target by employing the Shodan.io API and programmatically chooses Metasploit exploit modules based on the Shodan query.
* [Decker](https://github.com/stevenaldinger/decker) - Penetration testing orchestration and automation framework, which allows writing declarative, reusable configurations capable of ingesting variables and using outputs of tools it has run as inputs to others.
* [Faraday](https://github.com/infobyte/faraday) - Multiuser integrated pentesting environment for red teams performing cooperative penetration tests, security audits, and risk assessments.
* [Metasploit](https://www.metasploit.com/) - Software for offensive security teams to help verify vulnerabilities and manage security assessments.
* [Pupy](https://github.com/n1nj4sec/pupy) - Cross-platform (Windows, Linux, macOS, Android) remote administration and post-exploitation tool.

## Network Tools

* [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) - Swiss army knife for pentesting networks.
* [IKEForce](https://github.com/SpiderLabs/ikeforce) - Command line IPSEC VPN brute forcing tool for Linux that allows group name/ID enumeration and XAUTH brute forcing capabilities.
* [Intercepter-NG](http://sniff.su/) - Multifunctional network toolkit.
* [Legion](https://github.com/GoVanguard/legion) - Graphical semi-automated discovery and reconnaissance framework based on Python 3  and forked from SPARTA.
* [Network-Tools.com](http://network-tools.com/) - Website offering an interface to numerous basic network utilities like `ping`, `traceroute`, `whois`, and more.
* [Praeda](http://h.foofus.net/?page_id=218) - Automated multi-function printer data harvester for gathering usable data during security assessments.
* [Printer Exploitation Toolkit (PRET)](https://github.com/RUB-NDS/PRET) - Tool for printer security testing capable of IP and USB connectivity, fuzzing, and exploitation of PostScript, PJL, and PCL printer language features.
* [SPARTA](https://sparta.secforce.com/) - Graphical interface offering scriptable, configurable access to existing network infrastructure scanning and enumeration tools.
* [THC Hydra](https://github.com/vanhauser-thc/thc-hydra) - Online password cracking tool with built-in support for many network protocols, including HTTP, SMB, FTP, telnet, ICQ, MySQL, LDAP, IMAP, VNC, and more.
* [Zarp](https://github.com/hatRiot/zarp) - Network attack tool centered around the exploitation of local networks.
* [dnstwist](https://github.com/elceef/dnstwist) - Domain name permutation engine for detecting typo squatting, phishing and corporate espionage.
* [dsniff](https://www.monkey.org/~dugsong/dsniff/) - Collection of tools for network auditing and pentesting.
* [impacket](https://github.com/CoreSecurity/impacket) - Collection of Python classes for working with network protocols.
* [pivotsuite](https://github.com/RedTeamOperations/PivotSuite) - Portable, platform independent and powerful network pivoting toolkit.
* [routersploit](https://github.com/reverse-shell/routersploit) - Open source exploitation framework similar to Metasploit but dedicated to embedded devices.
* [rshijack](https://github.com/kpcyrd/rshijack) - TCP connection hijacker, Rust rewrite of `shijack`.

### DDoS Tools

* [Anevicon](https://github.com/Gymmasssorla/anevicon) - Powerful UDP-based load generator, written in Rust.
* [HOIC](https://sourceforge.net/projects/high-orbit-ion-cannon/) - Updated version of Low Orbit Ion Cannon, has 'boosters' to get around common counter measures.
* [JS LOIC](http://metacortexsecurity.com/tools/anon/LOIC/LOICv1.html) - JavaScript in-browser version of LOIC.
* [LOIC](https://github.com/NewEraCracker/LOIC/) - Open source network stress tool for Windows.
* [Memcrashed](https://github.com/649/Memcrashed-DDoS-Exploit) - DDoS attack tool for sending forged UDP packets to vulnerable Memcached servers obtained using Shodan API.
* [SlowLoris](https://github.com/gkbrk/slowloris) - DoS tool that uses low bandwidth on the attacking side.
* [T50](https://gitlab.com/fredericopissarra/t50/) - Faster network stress tool.
* [UFONet](https://github.com/epsylon/ufonet) - Abuses OSI layer 7 HTTP to create/manage 'zombies' and to conduct different attacks using; `GET`/`POST`, multithreading, proxies, origin spoofing methods, cache evasion techniques, etc.

### Exfiltration Tools

* [Cloakify](https://github.com/TryCatchHCF/Cloakify) - Textual steganography toolkit that converts any filetype into lists of everyday strings.
* [DET](https://github.com/sensepost/DET) - Proof of concept to perform data exfiltration using either single or multiple channel(s) at the same time.
* [Iodine](https://code.kryo.se/iodine/) - Tunnel IPv4 data through a DNS server; useful for exfiltration from networks where Internet access is firewalled, but DNS queries are allowed.
* [TrevorC2](https://github.com/trustedsec/trevorc2) - Client/server tool for masking command and control and data exfiltration through a normally browsable website, not typical HTTP POST requests.
* [dnscat2](https://github.com/iagox86/dnscat2) - Tool designed to create an encrypted command and control channel over the DNS protocol, which is an effective tunnel out of almost every network.
* [pwnat](https://github.com/samyk/pwnat) - Punches holes in firewalls and NATs.
* [tgcd](http://tgcd.sourceforge.net/) - Simple Unix network utility to extend the accessibility of TCP/IP based network services beyond firewalls.

### Network Reconnaissance Tools

* [ACLight](https://github.com/cyberark/ACLight) - Script for advanced discovery of sensitive Privileged Accounts - includes Shadow Admins.
* [CloudFail](https://github.com/m0rtem/CloudFail) - Unmask server IP addresses hidden behind Cloudflare by searching old database records and detecting misconfigured DNS.
* [DNSDumpster](https://dnsdumpster.com/) - Online DNS recon and search service.
* [Mass Scan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
* [ScanCannon](https://github.com/johnnyxmas/ScanCannon) - Python script to quickly enumerate large networks by calling `masscan` to quickly identify open ports and then `nmap` to gain details on the systems/services on those ports.
* [XRay](https://github.com/evilsocket/xray) - Network (sub)domain discovery and reconnaissance automation tool.
* [dnsenum](https://github.com/fwaeytens/dnsenum/) - Perl script that enumerates DNS information from a domain, attempts zone transfers, performs a brute force dictionary style attack, and then performs reverse look-ups on the results.
* [dnsmap](https://github.com/makefu/dnsmap/) - Passive DNS network mapper.
* [dnsrecon](https://github.com/darkoperator/dnsrecon/) - DNS enumeration script.
* [dnstracer](http://www.mavetju.org/unix/dnstracer.php) - Determines where a given DNS server gets its information from, and follows the chain of DNS servers.
* [fierce](https://github.com/mschwager/fierce) - Python3 port of the original `fierce.pl` DNS reconnaissance tool for locating non-contiguous IP space.
* [nmap](https://nmap.org/) - Free security scanner for network exploration & security audits.
* [passivedns-client](https://github.com/chrislee35/passivedns-client) - Library and query tool for querying several passive DNS providers.
* [passivedns](https://github.com/gamelinux/passivedns) - Network sniffer that logs all DNS server replies for use in a passive DNS setup.
* [scanless](https://github.com/vesche/scanless) - Utility for using websites to perform port scans on your behalf so as not to reveal your own IP.
* [smbmap](https://github.com/ShawnDEvans/smbmap) - Handy SMB enumeration tool.
* [zmap](https://zmap.io/) - Open source network scanner that enables researchers to easily perform Internet-wide network studies.

### Protocol Analyzers and Sniffers

* [Debookee](http://www.iwaxx.com/debookee/) - Simple and powerful network traffic analyzer for macOS.
* [Dripcap](https://github.com/dripcap/dripcap) - Caffeinated packet analyzer.
* [Dshell](https://github.com/USArmyResearchLab/Dshell) - Network forensic analysis framework.
* [Netzob](https://github.com/netzob/netzob) - Reverse engineering, traffic generation and fuzzing of communication protocols.
* [Wireshark](https://www.wireshark.org/) - Widely-used graphical, cross-platform network protocol analyzer.
* [netsniff-ng](https://github.com/netsniff-ng/netsniff-ng) - Swiss army knife for for network sniffing.
* [sniffglue](https://github.com/kpcyrd/sniffglue) - Secure multithreaded packet sniffer.
* [tcpdump/libpcap](http://www.tcpdump.org/) - Common packet analyzer that runs under the command line.

### Network Traffic Replay and Editing Tools

* [TraceWrangler](https://www.tracewrangler.com/) - Network capture file toolkit that can edit and merge `pcap` or `pcapng` files with batch editing features.
* [WireEdit](https://wireedit.com/) - Full stack WYSIWYG pcap editor (requires a free license to edit packets).
* [bittwist](http://bittwist.sourceforge.net/) - Simple yet powerful libpcap-based Ethernet packet generator useful in simulating networking traffic or scenario, testing firewall, IDS, and IPS, and troubleshooting various network problems.
* [hping3](https://github.com/antirez/hping) - Network tool able to send custom TCP/IP packets.
* [pig](https://github.com/rafael-santiago/pig) - GNU/Linux packet crafting tool.
* [scapy](https://github.com/secdev/scapy) - Python-based interactive packet manipulation program and library.
* [tcpreplay](https://tcpreplay.appneta.com/) - Suite of free Open Source utilities for editing and replaying previously captured network traffic.

### Proxies and Machine-in-the-Middle (MITM) Tools

* [BetterCAP](https://www.bettercap.org/) - Modular, portable and easily extensible MITM framework.
* [Ettercap](http://www.ettercap-project.org) - Comprehensive, mature suite for machine-in-the-middle attacks.
* [Habu](https://github.com/portantier/habu) - Python utility implementing a variety of network attacks, such as ARP poisoning, DHCP starvation, and more.
* [Lambda-Proxy](https://github.com/puresec/lambda-proxy) - Utility for testing SQL Injection vulnerabilities on AWS Lambda serverless functions.
* [MITMf](https://github.com/byt3bl33d3r/MITMf) - Framework for Man-In-The-Middle attacks.
* [Morpheus](https://github.com/r00t-3xp10it/morpheus) - Automated ettercap TCP/IP Hijacking tool.
* [SSH MITM](https://github.com/jtesta/ssh-mitm) - Intercept SSH connections with a proxy; all plaintext passwords and sessions are logged to disk.
* [dnschef](https://github.com/iphelix/dnschef) - Highly configurable DNS proxy for pentesters.
* [evilgrade](https://github.com/infobyte/evilgrade) - Modular framework to take advantage of poor upgrade implementations by injecting fake updates.
* [mallory](https://github.com/justmao945/mallory) - HTTP/HTTPS proxy over SSH.
* [mitmproxy](https://mitmproxy.org/) - Interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [oregano](https://github.com/nametoolong/oregano) - Python module that runs as a machine-in-the-middle (MITM) accepting Tor client requests.
* [sylkie](https://dlrobertson.github.io/sylkie/) - Command line tool and library for testing networks for common address spoofing security vulnerabilities in IPv6 networks using the Neighbor Discovery Protocol.

### Transport Layer Security Tools

* [SSLyze](https://github.com/nabla-c0d3/sslyze) - Fast and comprehensive TLS/SSL configuration analyzer to help identify security mis-configurations.
* [crackpkcs12](https://github.com/crackpkcs12/crackpkcs12) - Multithreaded program to crack PKCS#12 files (`.p12` and `.pfx` extensions), such as TLS/SSL certificates.
* [testssl.sh](https://github.com/drwetter/testssl.sh) - Command line tool which checks a server's service on any port for the support of TLS/SSL ciphers, protocols as well as some cryptographic flaws.
* [tls_prober](https://github.com/WestpointLtd/tls_prober) - Fingerprint a server's SSL/TLS implementation.

### Wireless Network Tools

* [Aircrack-ng](http://www.aircrack-ng.org/) - Set of tools for auditing wireless networks.
* [Airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon) - Multi-use bash script for Linux systems to audit wireless networks.
* [BoopSuite](https://github.com/MisterBianco/BoopSuite) - Suite of tools written in Python for wireless auditing.
* [Bully](http://git.kali.org/gitweb/?p=packages/bully.git;a=summary) - Implementation of the WPS brute force attack, written in C.
* [Cowpatty](https://github.com/joswr1ght/cowpatty) - Brute-force dictionary attack against WPA-PSK.
* [Fluxion](https://github.com/FluxionNetwork/fluxion) - Suite of automated social engineering based WPA attacks.
* [KRACK Detector](https://github.com/securingsam/krackdetector) - Detect and prevent KRACK attacks in your network.
* [Kismet](https://kismetwireless.net/) - Wireless network detector, sniffer, and IDS.
* [pwnagotchi](https://github.com/evilsocket/pwnagotchi) - Deep reinforcement learning based AI that learns from the Wi-Fi environment and instruments BetterCAP in order to maximize the WPA key material captured.
* [Reaver](https://code.google.com/archive/p/reaver-wps) - Brute force attack against WiFi Protected Setup.
* [WiFi-Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin) - Framework for rogue Wi-Fi access point attack.
* [Wifite](https://github.com/derv82/wifite) - Automated wireless attack tool.
* [infernal-twin](https://github.com/entropy1337/infernal-twin) - Automated wireless hacking tool.
* [krackattacks-scripts](https://github.com/vanhoefm/krackattacks-scripts) - WPA2 Krack attack scripts.
* [wifi-arsenal](https://github.com/0x90/wifi-arsenal) - Resources for Wi-Fi Pentesting.

## Network Vulnerability Scanners

* [celerystalk](https://github.com/sethsec/celerystalk) - Asynchronous enumeration and vulnerability scanner that "runs all the tools on all the hosts" in a configurable manner.
* [Nessus](https://www.tenable.com/products/nessus-vulnerability-scanner) - Commercial vulnerability management, configuration, and compliance assessment platform, sold by Tenable.
* [Netsparker Application Security Scanner](https://www.netsparker.com/) - Application security scanner to automatically find security flaws.
* [Nexpose](https://www.rapid7.com/products/nexpose/) - Commercial vulnerability and risk management assessment engine that integrates with Metasploit, sold by Rapid7.
* [OpenVAS](http://www.openvas.org/) - Free software implementation of the popular Nessus vulnerability assessment system.
* [Vuls](https://github.com/future-architect/vuls) - Agentless vulnerability scanner for GNU/Linux and FreeBSD, written in Go.

### Web Vulnerability Scanners

* [ACSTIS](https://github.com/tijme/angularjs-csti-scanner) - Automated client-side template injection (sandbox escape/bypass) detection for AngularJS.
* [Arachni](http://www.arachni-scanner.com/) - Scriptable framework for evaluating the security of web applications.
* [JCS](https://github.com/TheM4hd1/JCS) - Joomla Vulnerability Component Scanner with automatic database updater from exploitdb and packetstorm.
* [Netsparker Application Security Scanner](https://www.netsparker.com/) - Application security scanner to automatically find security flaws.
* [Nikto](https://cirt.net/nikto2) - Noisy but fast black box web server and web application vulnerability scanner.
* [SQLmate](https://github.com/UltimateHackers/sqlmate) - Friend of `sqlmap` that identifies SQLi vulnerabilities based on a given dork and (optional) website.
* [SecApps](https://secapps.com/) - In-browser web application security testing suite.
* [WPScan](https://wpscan.org/) - Black box WordPress vulnerability scanner.
* [Wapiti](http://wapiti.sourceforge.net/) - Black box web application vulnerability scanner with built-in fuzzer.
* [WebReaver](https://www.webreaver.com/) - Commercial, graphical web application vulnerability scanner designed for macOS.
* [cms-explorer](https://code.google.com/archive/p/cms-explorer/) - Reveal the specific modules, plugins, components and themes that various websites powered by content management systems are running.
* [joomscan](https://www.owasp.org/index.php/Category:OWASP_Joomla_Vulnerability_Scanner_Project) - Joomla vulnerability scanner.
* [w3af](https://github.com/andresriancho/w3af) - Web application attack and audit framework.

## OSINT Tools

* [AQUATONE](https://github.com/michenriksen/aquatone) - Subdomain discovery tool utilizing various open sources producing a report that can be used as input to other tools.
* [BinGoo](https://github.com/Hood3dRob1n/BinGoo) - GNU/Linux bash based Bing and Google Dorking Tool.
* [Censys](https://www.censys.io/) - Collects data on hosts and websites through daily ZMap and ZGrab scans.
* [DataSploit](https://github.com/upgoingstar/datasploit) - OSINT visualizer utilizing Shodan, Censys, Clearbit, EmailHunter, FullContact, and Zoomeye behind the scenes.
* [dorkbot](https://github.com/utiso/dorkbot) - Command-line tool to scan Google (or other) search results for vulnerabilities.
* [FOCA (Fingerprinting Organizations with Collected Archives)](https://www.elevenpaths.com/labstools/foca/) - Automated document harvester that searches Google, Bing, and DuckDuckGo to find and extrapolate internal company organizational structures.
* [GooDork](https://github.com/k3170makan/GooDork) - Command line Google dorking tool.
* [Google Hacking Database](https://www.exploit-db.com/google-hacking-database/) - Database of Google dorks; can be used for recon.
* [GyoiThon](https://github.com/gyoisamurai/GyoiThon) - GyoiThon is an Intelligence Gathering tool using Machine Learning.
* [Hunter.io](https://hunter.io/) - Data broker providing a Web search interface for discovering the email addresses and other organizational details of a company.
* [Intrigue](http://intrigue.io) - Automated OSINT & Attack Surface discovery framework with powerful API, UI and CLI.
* [Maltego](http://www.paterva.com/web7/) - Proprietary software for open source intelligence and forensics, from Paterva.
* [OWASP Amass](https://github.com/OWASP/Amass) - Subdomain enumeration via scraping, web archives, brute forcing, permutations, reverse DNS sweeping, TLS certificates, passive DNS data sources, etc.
* [PacketTotal](https://packettotal.com/) - Simple, free, high-quality packet capture file analysis facilitating the quick detection of network-borne malware (using Bro and Suricata IDS signatures under the hood).
* [Shodan](https://www.shodan.io/) - World's first search engine for Internet-connected devices.
* [SimplyEmail](https://github.com/SimplySecurity/SimplyEmail) - Email recon made fast and easy.
* [Sn1per](https://github.com/1N3/Sn1per) - Automated Pentest Recon Scanner.
* [Spiderfoot](http://www.spiderfoot.net/) - Multi-source OSINT automation tool with a Web UI and report visualizations.
* [Threat Crowd](https://www.threatcrowd.org/) - Search engine for threats.
* [Virus Total](https://www.virustotal.com/) - Free service that analyzes suspicious files and URLs and facilitates the quick detection of viruses, worms, trojans, and all kinds of malware.
* [ZoomEye](https://www.zoomeye.org/) - Search engine for cyberspace that lets the user find specific network components.
* [creepy](https://github.com/ilektrojohn/creepy) - Geolocation OSINT tool.
* [dork-cli](https://github.com/jgor/dork-cli) - Command line Google dork tool.
* [dorks](https://github.com/USSCltd/dorks) - Google hack database automation tool.
* [fast-recon](https://github.com/DanMcInerney/fast-recon) - Perform Google dorks against a domain.
* [gOSINT](https://github.com/Nhoya/gOSINT) - OSINT tool with multiple modules and a telegram scraper.
* [github-dorks](https://github.com/techgaun/github-dorks) - CLI tool to scan GitHub repos/organizations for potential sensitive information leaks.
* [image-match](https://github.com/ascribe/image-match) - Quickly search over billions of images.
* [metagoofil](https://github.com/laramies/metagoofil) - Metadata harvester.
* [pagodo](https://github.com/opsdisk/pagodo) - Automate Google Hacking Database scraping.
* [recon-ng](https://github.com/lanmaster53/recon-ng) - Full-featured Web Reconnaissance framework written in Python.
* [sn0int](https://github.com/kpcyrd/sn0int) - Semi-automatic OSINT framework and package manager.
* [snitch](https://github.com/Smaash/snitch) - Information gathering via dorks.
* [surfraw](https://github.com/kisom/surfraw) - Fast UNIX command line interface to a variety of popular WWW search engines.
* [theHarvester](https://github.com/laramies/theHarvester) - E-mail, subdomain and people names harvester.
* [vcsmap](https://github.com/melvinsh/vcsmap) - Plugin-based tool to scan public version control systems for sensitive information.
* [WhatBreach](https://github.com/Ekultek/WhatBreach) - Search email addresses and discover all known breaches that this email has been seen in, and download the breached database if it is publicly available.

## Online Resources

### Online Code Samples and Examples

* [goHackTools](https://github.com/dreddsa5dies/goHackTools) - Hacker tools on Go (Golang).

### Online Exploit Development Resources

* [Exploit Writing Tutorials](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/) - Tutorials on how to develop exploits.
* [Shellcode Examples](http://shell-storm.org/shellcode/) - Shellcodes database.
* [Shellcode Tutorial](http://www.vividmachines.com/shellcode/shellcode.html) - Tutorial on how to write shellcode.

### Online Lock Picking Resources

* [/r/lockpicking](https://www.reddit.com/r/lockpicking) - Resources for learning lockpicking, equipment recommendations.
* [Schuyler Towne channel](https://www.youtube.com/user/SchuylerTowne/) - Lockpicking videos and security talks.
* [bosnianbill](https://www.youtube.com/user/bosnianbill) - Instructional lockpicking videos made by an expert.

### Online Open Sources Intelligence (OSINT) Resources

* [CertGraph](https://github.com/lanrat/certgraph) - Crawls a domain's SSL/TLS certificates for its certificate alternative names.
* [GhostProject](https://ghostproject.fr/) - Searchable database of billions of cleartext passwords, partially visible for free.
* [Intel Techniques](https://inteltechniques.com/menu.html) - Collection of OSINT tools. Menu on the left can be used to navigate through the categories.
* [NetBootcamp OSINT Tools](http://netbootcamp.org/osinttools/) - Collection of OSINT links and custom Web interfaces to other services.
* [OSINT Framework](http://osintframework.com/) - Collection of various OSINT tools broken out by category.
* [WiGLE.net](https://wigle.net/) - Information about wireless networks world-wide, with user-friendly desktop and web applications.

### Online Operating Systems Resources

* [DistroWatch.com's Security Category](https://distrowatch.com/search.php?category=Security) - Website dedicated to talking about, reviewing, and keeping up to date with open source operating systems.

### Online Penetration Testing Resources

* [InfoSec Institute](https://resources.infosecinstitute.com) - IT and security articles.
* [MITRE's Adversarial Tactics, Techniques & Common Knowledge (ATT&CK)](https://attack.mitre.org/) - Curated knowledge base and model for cyber adversary behavior.
* [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/) - Free Offensive Security Metasploit course.
* [Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - Worldwide not-for-profit charitable organization focused on improving the security of especially Web-based and Application-layer software.
* [PENTEST-WIKI](https://github.com/nixawk/pentest-wiki) - Free online security knowledge library for pentesters and researchers.
* [Penetration Testing Execution Standard (PTES)](http://www.pentest-standard.org/) - Documentation designed to provide a common language and scope for performing and reporting the results of a penetration test.
* [Penetration Testing Framework (PTF)](http://www.vulnerabilityassessment.co.uk/Penetration%20Test.html) - Outline for performing penetration tests compiled as a general framework usable by vulnerability analysts and penetration testers alike.
* [XSS-Payloads](http://www.xss-payloads.com) - Resource dedicated to all things XSS (cross-site), including payloads, tools, games, and documentation.

### Social Engineering Resources

* [Social Engineering Framework](http://www.social-engineer.org/framework/general-discussion/) - Information resource for social engineers.

### Other Lists Online

* [.NET Programming](https://github.com/quozd/awesome-dotnet) - Software framework for Microsoft Windows platform development.
* [Android Exploits](https://github.com/sundaysec/Android-Exploits) - Guide on Android Exploitation and Hacks.
* [Android Security](https://github.com/ashishb/android-security-awesome) - Collection of Android security related resources.
* [AppSec](https://github.com/paragonie/awesome-appsec) - Resources for learning about application security.
* [Awesome Awesomness](https://github.com/bayandin/awesome-awesomeness) - The List of the Lists.
* [Awesome Lockpicking](https://github.com/meitar/awesome-lockpicking) - Awesome guides, tools, and other resources about the security and compromise of locks, safes, and keys.
* [Awesome Shodan Queries](https://github.com/jakejarvis/awesome-shodan-queries) - Awesome list of useful, funny, and depressing search queries for Shodan.
* [Blue Team](https://github.com/meitar/awesome-cybersecurity-blueteam) - Awesome resources, tools, and other shiny things for cybersecurity blue teams.
* [C/C++ Programming](https://github.com/fffaraz/awesome-cpp) - One of the main language for open source security tools.
* [CTFs](https://github.com/apsdehal/awesome-ctf) - Capture The Flag frameworks, libraries, etc.
* [Forensics](https://github.com/Cugu/awesome-forensics) - Free (mostly open source) forensic analysis tools and resources.
* [Hacking](https://github.com/carpedm20/awesome-hacking) - Tutorials, tools, and resources.
* [Honeypots](https://github.com/paralax/awesome-honeypots) - Honeypots, tools, components, and more.
* [InfoSec § Hacking challenges](https://github.com/AnarchoTechNYC/meta/wiki/InfoSec#hacking-challenges) - Comprehensive directory of CTFs, wargames, hacking challenge websites, pentest practice lab exercises, and more.
* [Infosec](https://github.com/onlurking/awesome-infosec) - Information security resources for pentesting, forensics, and more.
* [Security-related Operating Systems](https://list.rawsec.ml/operating_systems.html) - List of security related operating systems.
* [JavaScript Programming](https://github.com/sorrycc/awesome-javascript) - In-browser development and scripting.
* [Kali Linux Tools](http://tools.kali.org/tools-listing) - List of tools present in Kali Linux.
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) - Tools and resources for analysts.
* [Node.js Programming by @sindresorhus](https://github.com/sindresorhus/awesome-nodejs) - Curated list of delightful Node.js packages and resources.
* [OSINT](https://github.com/jivoi/awesome-osint) - Awesome OSINT list containing great resources.
* [PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) - Tools for processing network traffic.
* [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - Awesome Pentest Cheat Sheets.
* [Python Programming by @svaksha](https://github.com/svaksha/pythonidae) - General Python programming.
* [Python Programming by @vinta](https://github.com/vinta/awesome-python) - General Python programming.
* [Python tools for penetration testers](https://github.com/dloss/python-pentest-tools) - Lots of pentesting tools are written in Python.
* [Ruby Programming by @Sdogruyol](https://github.com/Sdogruyol/awesome-ruby) - The de-facto language for writing exploits.
* [Ruby Programming by @dreikanter](https://github.com/dreikanter/ruby-bookmarks) - The de-facto language for writing exploits.
* [Ruby Programming by @markets](https://github.com/markets/awesome-ruby) - The de-facto language for writing exploits.
* [SecLists](https://github.com/danielmiessler/SecLists) - Collection of multiple types of lists used during security assessments.
* [SecTools](http://sectools.org/) - Top 125 Network Security Tools.
* [Security Talks](https://github.com/PaulSec/awesome-sec-talks) - Curated list of security conferences.
* [Security](https://github.com/sbilly/awesome-security) - Software, libraries, documents, and other resources.
* [Serverless Security](https://github.com/puresec/awesome-serverless-security/) - Curated list of awesome serverless security resources such as (e)books, articles, whitepapers, blogs and research papers.
* [Shell Scripting](https://github.com/alebcay/awesome-shell) - Command line frameworks, toolkits, guides and gizmos.
* [YARA](https://github.com/InQuest/awesome-yara) - YARA rules, tools, and people.

### Penetration Testing Report Templates

* [Public Pentesting Reports](https://github.com/juliocesarfort/public-pentesting-reports) - Curated list of public penetration test reports released by several consulting firms and academic security groups.
* [T&VS Pentesting Report Template](https://www.testandverification.com/wp-content/uploads/template-penetration-testing-report-v03.pdf) - Pentest report template provided by Test and Verification Services, Ltd.
* [Web Application Security Assessment Report Template](http://lucideus.com/pdf/stw.pdf) - Sample Web application security assessment reporting template provided by Lucideus.

## Operating System Distributions

* [Android Tamer](https://androidtamer.com/) - Distribution built for Android security professionals that includes tools required for Android security testing.
* [ArchStrike](https://archstrike.org/) - Arch GNU/Linux repository for security professionals and enthusiasts.
* [AttifyOS](https://github.com/adi0x90/attifyos) - GNU/Linux distribution focused on tools useful during Internet of Things (IoT) security assessments.
* [BackBox](https://backbox.org/) - Ubuntu-based distribution for penetration tests and security assessments.
* [BlackArch](https://www.blackarch.org/) - Arch GNU/Linux-based distribution for penetration testers and security researchers.
* [Buscador](https://inteltechniques.com/buscador/) - GNU/Linux virtual machine that is pre-configured for online investigators.
* [Kali](https://www.kali.org/) - Rolling Debian-based GNU/Linux distribution designed for penetration testing and digital forensics.
* [Network Security Toolkit (NST)](http://networksecuritytoolkit.org/) - Fedora-based GNU/Linux bootable live Operating System designed to provide easy access to best-of-breed open source network security applications.
* [Parrot](https://www.parrotsec.org/) - Distribution similar to Kali, with support for multiple hardware architectures.
* [PentestBox](https://pentestbox.org/) - Open source pre-configured portable penetration testing environment for the Windows Operating System.
* [The Pentesters Framework](https://github.com/trustedsec/ptf) - Distro organized around the Penetration Testing Execution Standard (PTES), providing a curated collection of utilities that omits less frequently used utilities.

## Periodicals

* [2600: The Hacker Quarterly](https://www.2600.com/Magazine/DigitalEditions) - American publication about technology and computer "underground" culture.
* [Phrack Magazine](http://www.phrack.org/) - By far the longest running hacker zine.

## Physical Access Tools

* [AT Commands](https://atcommands.org/) - Use AT commands over an Android device's USB port to rewrite device firmware, bypass security mechanisms, exfiltrate sensitive information, perform screen unlocks, and inject touch events.
* [Bash Bunny](https://www.hak5.org/gear/bash-bunny) - Local exploit delivery tool in the form of a USB thumbdrive in which you write payloads in a DSL called BunnyScript.
* [LAN Turtle](https://lanturtle.com/) - Covert "USB Ethernet Adapter" that provides remote access, network intelligence gathering, and MITM capabilities when installed in a local network.
* [PCILeech](https://github.com/ufrisk/pcileech) - Uses PCIe hardware devices to read and write from the target system memory via Direct Memory Access (DMA) over PCIe.
* [Packet Squirrel](https://www.hak5.org/gear/packet-squirrel) - Ethernet multi-tool designed to enable covert remote access, painless packet captures, and secure VPN connections with the flip of a switch.
* [Poisontap](https://samy.pl/poisontap/) - Siphons cookies, exposes internal (LAN-side) router and installs web backdoor on locked computers.
* [Proxmark3](https://proxmark3.com/) - RFID/NFC cloning, replay, and spoofing toolkit often used for analyzing and attacking proximity cards/readers, wireless keys/keyfobs, and more.
* [USB Rubber Ducky](http://usbrubberducky.com/) - Customizable keystroke injection attack platform masquerading as a USB thumbdrive.
* [WiFi Pineapple](https://www.wifipineapple.com/) - Wireless auditing and penetration testing platform.

## Reverse Engineering Tools

See also [awesome-reversing](https://github.com/tylerha97/awesome-reversing).

* [Capstone](http://www.capstone-engine.org/) - Lightweight multi-platform, multi-architecture disassembly framework.
* [Evan's Debugger](http://www.codef00.com/projects#debugger) - OllyDbg-like debugger for GNU/Linux.
* [Frida](https://www.frida.re/) - Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
* [Ghidra](https://www.ghidra-sre.org/) - Suite of free software reverse engineering tools developed by NSA's Research Directorate originally exposed in WikiLeaks's "Vault 7" publication and now maintained as open source software.
* [Immunity Debugger](https://immunityinc.com/products/debugger/) - Powerful way to write exploits and analyze malware.
* [Interactive Disassembler (IDA Pro)](https://www.hex-rays.com/products/ida/) - Proprietary multi-processor disassembler and debugger for Windows, GNU/Linux, or macOS; also has a free version, [IDA Free](https://www.hex-rays.com/products/ida/support/download_freeware.shtml).
* [Medusa](https://github.com/wisk/medusa) - Open source, cross-platform interactive disassembler.
* [OllyDbg](http://www.ollydbg.de/) - x86 debugger for Windows binaries that emphasizes binary code analysis.
* [PyREBox](https://github.com/Cisco-Talos/pyrebox) - Python scriptable Reverse Engineering sandbox by Cisco-Talos.
* [Radare2](http://rada.re/r/index.html) - Open source, crossplatform reverse engineering framework.
* [UEFITool](https://github.com/LongSoft/UEFITool) - UEFI firmware image viewer and editor.
* [Voltron](https://github.com/snare/voltron) - Extensible debugger UI toolkit written in Python.
* [WDK/WinDbg](https://msdn.microsoft.com/en-us/windows/hardware/hh852365.aspx) - Windows Driver Kit and WinDbg.
* [binwalk](https://github.com/devttys0/binwalk) - Fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.
* [boxxy](https://github.com/kpcyrd/boxxy-rs) - Linkable sandbox explorer.
* [dnSpy](https://github.com/0xd4d/dnSpy) - Tool to reverse engineer .NET assemblies.
* [peda](https://github.com/longld/peda) - Python Exploit Development Assistance for GDB.
* [plasma](https://github.com/joelpx/plasma) - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code.
* [pwndbg](https://github.com/pwndbg/pwndbg) - GDB plug-in that eases debugging with GDB, with a focus on features needed by low-level software developers, hardware hackers, reverse-engineers, and exploit developers.
* [rVMI](https://github.com/fireeye/rVMI) - Debugger on steroids; inspect userspace processes, kernel drivers, and preboot environments in a single tool.
* [x64dbg](http://x64dbg.com/) - Open source x64/x32 debugger for windows.

## Security Education Courses

* [ARIZONA CYBER WARFARE RANGE](http://azcwr.org/) - 24x7 live fire exercises for beginners through real world operations; capability for upward progression into the real world of cyber warfare.
* [CTF Field Guide](https://trailofbits.github.io/ctf/) - Everything you need to win your next CTF competition.
* [Cybrary](http://cybrary.it) - Free courses in ethical hacking and advanced penetration testing. Advanced penetration testing courses are based on the book 'Penetration Testing for Highly Secured Environments'.
* [European Union Agency for Network and Information Security](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material) - ENISA Cyber Security Training material.
* [Offensive Security Training](https://www.offensive-security.com/information-security-training/) - Training from BackTrack/Kali developers.
* [Open Security Training](http://opensecuritytraining.info/) - Training material for computer security classes.
* [SANS Security Training](http://www.sans.org/) - Computer Security Training & Certification.

## Side-channel Tools

* [ChipWhisperer](http://chipwhisperer.com) - Complete open-source toolchain for side-channel power analysis and glitching attacks.

## Social Engineering Tools

* [Beelogger](https://github.com/4w4k3/BeeLogger) - Tool for generating keylooger.
* [Catphish](https://github.com/ring0lab/catphish) - Tool for phishing and corporate espionage written in Ruby.
* [Evilginx2](https://github.com/kgretzky/evilginx2) - Standalone man-in-the-middle attack framework.
* [Evilginx](https://github.com/kgretzky/evilginx) - MITM attack framework used for phishing credentials and session cookies from any Web service.
* [FiercePhish](https://github.com/Raikia/FiercePhish) - Full-fledged phishing framework to manage all phishing engagements.
* [Gophish](https://getgophish.com) - Open-source phishing framework.
* [King Phisher](https://github.com/securestate/king-phisher) - Phishing campaign toolkit used for creating and managing multiple simultaneous phishing attacks with custom email and server content.
* [Modlishka](https://github.com/drk1wi/Modlishka) - Flexible and powerful reverse proxy with real-time two-factor authentication.
* [ReelPhish](https://github.com/fireeye/ReelPhish) - Real-time two-factor phishing tool.
* [ShellPhish](https://github.com/thelinuxchoice/shellphish) - Social media site cloner and phishing tool built atop SocialFish.
* [Social Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit) - Open source pentesting framework designed for social engineering featuring a number of custom attack vectors to make believable attacks quickly.
* [SocialFish](https://github.com/UndeadSec/SocialFish) - Social media phishing framework that can run on an Android phone or in a Docker container.
* [phishery](https://github.com/ryhanson/phishery) - TLS/SSL enabled Basic Auth credential harvester.
* [wifiphisher](https://github.com/sophron/wifiphisher) - Automated phishing attacks against WiFi networks.

## Static Analyzers

* [Brakeman](https://github.com/presidentbeef/brakeman) - Static analysis security vulnerability scanner for Ruby on Rails applications.
* [FindBugs](http://findbugs.sourceforge.net/) - Free software static analyzer to look for bugs in Java code.
* [Progpilot](https://github.com/designsecurity/progpilot) - Static security analysis tool for PHP code.
* [RegEx-DoS](https://github.com/jagracey/RegEx-DoS) - Analyzes source code for Regular Expressions susceptible to Denial of Service attacks.
* [bandit](https://pypi.python.org/pypi/bandit/) - Security oriented static analyser for Python code.
* [cppcheck](http://cppcheck.sourceforge.net/) - Extensible C/C++ static analyzer focused on finding bugs.
* [sobelow](https://github.com/nccgroup/sobelow) - Security-focused static analysis for the Phoenix Framework.
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) - Suite of tools built atop the Binary Analysis Platform (BAP) to heuristically detect CWEs in compiled binaries and firmware.

## Vulnerability Databases

* [Bugtraq (BID)](http://www.securityfocus.com/bid/) - Software security bug identification database compiled from submissions to the SecurityFocus mailing list and other sources, operated by Symantec, Inc.
* [CXSecurity](https://cxsecurity.com/) - Archive of published CVE and Bugtraq software vulnerabilities cross-referenced with a Google dork database for discovering the listed vulnerability.
* [China National Vulnerability Database (CNNVD)](http://www.cnnvd.org.cn/) - Chinese government-run vulnerability database analoguous to the United States's CVE database hosted by Mitre Corporation.
* [Common Vulnerabilities and Exposures (CVE)](https://cve.mitre.org/) - Dictionary of common names (i.e., CVE Identifiers) for publicly known security vulnerabilities.
* [Distributed Weakness Filing (DWF)](https://distributedweaknessfiling.org/) - Federated CNA (CVE Number Authority) mirroring MITRE's CVE database and offering additional CVE-equivalent numbers to otherwise out-of-scope vulnerability disclosures.
* [Exploit-DB](https://www.exploit-db.com/) - Non-profit project hosting exploits for software vulnerabilities, provided as a public service by Offensive Security.
* [Full-Disclosure](http://seclists.org/fulldisclosure/) - Public, vendor-neutral forum for detailed discussion of vulnerabilities, often publishes details before many other sources.
* [HPI-VDB](https://hpi-vdb.de/) - Aggregator of cross-referenced software vulnerabilities offering free-of-charge API access, provided by the Hasso-Plattner Institute, Potsdam.
* [Inj3ct0r](https://www.0day.today/) - Exploit marketplace and vulnerability information aggregator. ([Onion service](http://mvfjfugdwgc5uwho.onion/).)
* [Microsoft Security Advisories](https://technet.microsoft.com/en-us/security/advisories#APUMA) - Archive of security advisories impacting Microsoft software.
* [Microsoft Security Bulletins](https://technet.microsoft.com/en-us/security/bulletins#sec_search) - Announcements of security issues discovered in Microsoft software, published by the Microsoft Security Response Center (MSRC).
* [Mozilla Foundation Security Advisories](https://www.mozilla.org/security/advisories/) - Archive of security advisories impacting Mozilla software, including the Firefox Web Browser.
* [National Vulnerability Database (NVD)](https://nvd.nist.gov/) - United States government's National Vulnerability Database provides additional meta-data (CPE, CVSS scoring) of the standard CVE List along with a fine-grained search engine.
* [Packet Storm](https://packetstormsecurity.com/files/) - Compendium of exploits, advisories, tools, and other security-related resources aggregated from across the industry.
* [SecuriTeam](http://www.securiteam.com/) - Independent source of software vulnerability information.
* [US-CERT Vulnerability Notes Database](https://www.kb.cert.org/vuls/) - Summaries, technical details, remediation information, and lists of vendors affected by software vulnerabilities, aggregated by the United States Computer Emergency Response Team (US-CERT).
* [Vulnerability Lab](https://www.vulnerability-lab.com/) - Open forum for security advisories organized by category of exploit target.
* [Vulners](https://vulners.com/) - Security database of software vulnerabilities.
* [Vulmon](https://vulmon.com/) - Vulnerability search engine with vulnerability intelligence features that conducts full text searches in its database.
* [Zero Day Initiative](http://zerodayinitiative.com/advisories/published/) - Bug bounty program with publicly accessible archive of published security advisories, operated by TippingPoint.

## Web Exploitation

* [BlindElephant](http://blindelephant.sourceforge.net/) - Web application fingerprinter.
* [Browser Exploitation Framework (BeEF)](https://github.com/beefproject/beef) - Command and control server for delivering exploits to commandeered Web browsers.
* [Burp Suite](https://portswigger.net/burp/) - Integrated platform for performing security testing of web applications.
* [Commix](https://github.com/commixproject/commix) - Automated all-in-one operating system command injection and exploitation tool.
* [DVCS Ripper](https://github.com/kost/dvcs-ripper) - Rip web accessible (distributed) version control systems: SVN/GIT/HG/BZR.
* [EyeWitness](https://github.com/ChrisTruncer/EyeWitness) - Tool to take screenshots of websites, provide some server header info, and identify default credentials if possible.
* [Fiddler](https://www.telerik.com/fiddler) - Free cross-platform web debugging proxy with user-friendly companion tools.
* [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - Dictionary of attack patterns and primitives for black-box application fault injection and resource discovery.
* [GitTools](https://github.com/internetwache/GitTools) - Automatically find and download Web-accessible `.git` repositories.
* [Kadabra](https://github.com/D35m0nd142/Kadabra) - Automatic LFI exploiter and scanner.
* [Kadimus](https://github.com/P0cL4bs/Kadimus) - LFI scan and exploit tool.
* [NoSQLmap](https://github.com/codingo/NoSQLMap) - Automatic NoSQL injection and database takeover tool.
* [OWASP Zed Attack Proxy (ZAP)](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - Feature-rich, scriptable HTTP intercepting proxy and fuzzer for penetration testing web applications.
* [Offensive Web Testing Framework (OWTF)](https://www.owasp.org/index.php/OWASP_OWTF) - Python-based framework for pentesting Web applications based on the OWASP Testing Guide.
* [Raccoon](https://github.com/evyatarmeged/Raccoon) - High performance offensive security tool for reconnaissance and vulnerability scanning.
* [SQLmap](http://sqlmap.org/) - Automatic SQL injection and database takeover tool.
* [VHostScan](https://github.com/codingo/VHostScan) - Virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages.
* [WPSploit](https://github.com/espreto/wpsploit) - Exploit WordPress-powered websites with Metasploit.
* [Wappalyzer](https://www.wappalyzer.com/) - Wappalyzer uncovers the technologies used on websites.
* [WhatWaf](https://github.com/Ekultek/WhatWaf) - Detect and bypass web application firewalls and protection systems.
* [WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Website fingerprinter.
* [Wordpress Exploit Framework](https://github.com/rastating/wordpress-exploit-framework) - Ruby framework for developing and using modules which aid in the penetration testing of WordPress powered websites and systems.
* [autochrome](https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2017/march/autochrome/) - Easy to install a test browser with all the appropriate setting needed for web application testing with native Burp support, from NCCGroup.
* [badtouch](https://github.com/kpcyrd/badtouch) - Scriptable network authentication cracker.
* [fimap](https://github.com/kurobeats/fimap) - Find, prepare, audit, exploit and even Google automatically for LFI/RFI bugs.
* [liffy](https://github.com/hvqzao/liffy) - LFI exploitation tool.
* [recursebuster](https://github.com/c-sto/recursebuster) - Content discovery tool to perform directory and file bruteforcing.
* [sslstrip2](https://github.com/LeonardoNve/sslstrip2) - SSLStrip version to defeat HSTS.
* [sslstrip](https://www.thoughtcrime.org/software/sslstrip/) - Demonstration of the HTTPS stripping attacks.
* [tplmap](https://github.com/epinna/tplmap) - Automatic server-side template injection and Web server takeover tool.
* [wafw00f](https://github.com/EnableSecurity/wafw00f) - Identifies and fingerprints Web Application Firewall (WAF) products.
* [webscreenshot](https://github.com/maaaaz/webscreenshot) - Simple script to take screenshots of websites from a list of sites.
* [weevely3](https://github.com/epinna/weevely3) - Weaponized PHP-based web shell.

## Android Utilities

* [Android Open Pwn Project (AOPP)](https://www.pwnieexpress.com/aopp) - Variant of the Android Open Source Project (AOSP), called Pwnix, is built from the ground up for network hacking and pentesting.
* [cSploit](https://www.csploit.org/) - Advanced IT security professional toolkit on Android featuring an integrated Metasploit daemon and MITM capabilities.
* [Fing](https://www.fing.com/products/fing-app/) - Network scanning and host enumeration app that performs NetBIOS, UPnP, Bonjour, SNMP, and various other advanced device fingerprinting techniques.

## Windows Utilities

* [Active Directory and Privilege Escalation (ADAPE)](https://github.com/hausec/ADAPE-Script) - Umbrella script that automates numerous useful PowerShell modules to discover security misconfigurations and attempt privilege escalation against Active Directory.
* [Bloodhound](https://github.com/adaptivethreat/Bloodhound/wiki) - Graphical Active Directory trust relationship explorer.
* [Commando VM](https://github.com/fireeye/commando-vm) - Automated installation of over 140 Windows software packages for penetration testing and red teaming.
* [Covenant](https://github.com/cobbr/Covenant) - ASP.NET Core application that serves as a collaborative command and control platform for red teamers.
* [DeathStar](https://github.com/byt3bl33d3r/DeathStar) - Python script that uses Empire's RESTful API to automate gaining Domain Admin rights in Active Directory environments.
* [Empire](https://www.powershellempire.com/) - Pure PowerShell post-exploitation agent.
* [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel.
* [LaZagne](https://github.com/AlessandroZ/LaZagne) - Credentials recovery project.
* [Magic Unicorn](https://github.com/trustedsec/unicorn) - Shellcode generator for numerous attack vectors, including Microsoft Office macros, PowerShell, HTML applications (HTA), or `certutil` (using fake certificates).
* [MailSniper](https://github.com/dafthack/MailSniper) - Modular tool for searching through email in a Microsoft Exchange environment, gathering the Global Address List from Outlook Web Access (OWA) and Exchange Web Services (EWS), and more.
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - PowerShell Post-Exploitation Framework.
* [RID_ENUM](https://github.com/trustedsec/ridenum) - Python script that can enumerate all users from a Windows Domain Controller and crack those user's passwords using brute-force.
* [Responder](https://github.com/SpiderLabs/Responder) - Link-Local Multicast Name Resolution (LLMNR), NBT-NS, and mDNS poisoner.
* [Ruler](https://github.com/sensepost/ruler) - Abuses client-side Outlook features to gain a remote shell on a Microsoft Exchange server.
* [SCOMDecrypt](https://github.com/nccgroup/SCOMDecrypt) - Retrieve and decrypt RunAs credentials stored within Microsoft System Center Operations Manager (SCOM) databases.
* [Sysinternals Suite](https://technet.microsoft.com/en-us/sysinternals/bb842062) - The Sysinternals Troubleshooting Utilities.
* [Windows Credentials Editor](https://www.ampliasecurity.com/research/windows-credentials-editor/) - Inspect logon sessions and add, change, list, and delete associated credentials, including Kerberos tickets.
* [Windows Exploit Suggester](https://github.com/GDSSecurity/Windows-Exploit-Suggester) - Detects potential missing patches on the target.
* [mimikatz](http://blog.gentilkiwi.com/mimikatz) - Credentials extraction tool for Windows operating system.
* [redsnarf](https://github.com/nccgroup/redsnarf) - Post-exploitation tool for retrieving password hashes and credentials from Windows workstations, servers, and domain controllers.
* [wePWNise](https://labs.mwrinfosecurity.com/tools/wepwnise/) - Generates architecture independent VBA code to be used in Office documents or templates and automates bypassing application control and exploit mitigation software.
* [WinPwn](https://github.com/SecureThisShit/WinPwn) - Internal penetration test script to perform local and domain reconnaissance, privilege escalation and exploitation.

## macOS Utilities

* [Bella](https://github.com/kdaoudieh/Bella) - Pure Python post-exploitation data mining and remote administration tool for macOS.
* [EvilOSX](https://github.com/Marten4n6/EvilOSX) - Modular RAT that uses numerous evasion and exfiltration techniques out-of-the-box.

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
