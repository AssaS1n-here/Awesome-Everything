# Awesome Everything [![Static Badge](https://img.shields.io/badge/Version_1.0-8A2BE2?style=plastic&logo=github)](https://github.com/AssaS1n-here/Awesome-Everything)
The `Awesome Everything` repo for the `Open Source` tools collection for `Linux` and `Windows`
------
# Index
Pentesting Tools [ [Network Pentesting Tools](#network-pentesting-tools) [ [scanners](#network--port-scanners) | [ftp](#ftp-pentesting-tools) | [tftp](#tftp-pentesting-tools) | [ssh](#ssh-pentesting-tools) | [smtp](#smtp-pentest-tools) | [TACACS+](#tacacs-pentest-tools) | [dns](#dns-pentest-tools) | [finger](#finger-pentest-tools) | [kerberos](#kerberos-pentest-tools) | [ident](#ident-pentest-tools) | [ntp](#ntp-pentest-tools)[msrpc](#msrpc-pentest-tools) | [netbios](#netbios-pentest-tools) | [smb](#smb-pentest-tools) ] ]

# Pentesting Tools
## Network Pentesting Tools
- #### **network & port scanners**
  - [Smap](https://github.com/s0md3v/Smap) A drop-in replacement for Nmap.
  - [sandmap](https://github.com/trimstray/sandmap) Sandmap is a tool supporting network and system reconnaissance using the massive Nmap engine.
  - [RustScan](https://github.com/RustScan/RustScan) RustScan is a modern take on the port scanner. Sleek & fast. All while providing extensive extendability to you. Not to mention RustScan uses Adaptive Learning to 
    improve itself over time, making it the best port scanner for you.
  - [naabu](https://github.com/projectdiscovery/naabu) Naabu is a port scanning tool written in Go that allows you to enumerate valid ports for hosts in a fast and reliable manner. It is a really simple tool that does 
    fast SYN/CONNECT/UDP scans on the host/list of hosts and lists all ports that return a reply.
  - [scanless](https://github.com/vesche/scanless) This is a Python command-line utility and library for using websites that can perform port scans on your behalf.
  - [Silver](https://github.com/s0md3v/Silver) masscan is fast, nmap can fingerprint software and vulners is a huge vulnerability database. Silver is a front-end that allows complete utilization of these programs by 
     parsing data, spawning parallel processes, caching vulnerability data for faster scanning over time and much more.
  - [masscan](https://github.com/robertdavidgraham/masscan) This is an Internet-scale port scanner. It can scan the entire Internet in under 5 minutes, transmitting 10 million packets per second, from a single machine.
  - [furious](https://github.com/liamg/furious) Furious is a fast, lightweight, portable network scanner.
  - [Angry IP Scanner](https://github.com/angryip/ipscan) Angry IP scanner is a very fast IP address and port scanner.
  - [evilscan](https://github.com/eviltik/evilscan) Nodejs Simple Network Scanner.
  - [NimScan](https://github.com/elddy/NimScan) Really fast port scanner (With filtered option - Windows support only).
  - [armanda](https://github.com/resyncgg/armada) Armada is a high performance TCP SYN scanner. This is equivalent to the type of scanning that nmap might perform when you use the -sS scan type. Armada's main goal is to 
    answer the basic question "Is this port open?". It is then up to you, or your tooling, to dig further to identify what an open port is for.
  - [nmap](https://github.com/nmap/nmap) Nmap - the Network Mapper.
  - [scapy](https://github.com/secdev/scapy) Scapy is a powerful Python-based interactive packet manipulation program and library.
  - [hping](https://github.com/antirez/hping) hping3 is a network tool able to send custom TCP/IP packets and to display target replies like ping do with ICMP replies. hping3 can handle fragmentation, and almost 
    arbitrary packet size and content, using the command line interface.
  - [pycurity](https://github.com/ninijay/pycurity) A list of python hacking scripts.
  - [PortScanner](https://github.com/vinitshahdeo/PortScanner) A go-to tool for scanning network. Scan all the open ports for a given host with just one click.
  - [astsu](https://github.com/ReddyyZ/astsu) A network scanner tool, developed in Python 3 using scapy.
  - [unicornscan](https://github.com/dneufeld/unicornscan) archive of code from http://www.unicornscan.org/.
  - [zmap](https://github.com/zmap/zmap) ZMap is a fast single packet network scanner designed for Internet-wide network surveys.
  - [opscan](https://github.com/sigoden/opscan) A open port scanner.
  - [NetProbe](https://github.com/HalilDeniz/NetProbe) NetProbe is a tool you can use to scan for devices on your network. The program sends ARP requests to any IP address on your network and lists the IP addresses, MAC 
    addresses, manufacturers, and device models of the responding devices.
  - [sx](https://github.com/v-byte-cpu/sx) Fast, modern, easy-to-use network scanner.
  - [xmap](https://github.com/idealeer/xmap) XMap is a fast network scanner designed for performing Internet-wide IPv6 & IPv4 network research scanning.
  - [goscan](https://github.com/marco-lancini/goscan) GoScan is an interactive network scanner client, featuring auto-completion, which provides abstraction and automation over nmap.
  - [liwasc](https://github.com/pojntfx/liwasc) List, wake and scan nodes in a network.
  - [Network-Scanner](https://github.com/dharmil18/Network-Scanner) A Python script that scans for the devices connected to a network.
  - [WatchYourLAN](https://github.com/aceberg/WatchYourLAN) Lightweight network IP scanner with web GUI.
  - [tsunami-security-scanner](https://github.com/google/tsunami-security-scanner) Tsunami is a general purpose network security scanner with an extensible plugin system for detecting high severity vulnerabilities with 
    high confidence.
  - [webscan](https://github.com/samyk/webscan) Browser-based network scanner & local-IP detection.
  - [NetworkSherlock](https://github.com/HalilDeniz/NetworkSherlock) NetworkSherlock: powerful and flexible port scanning tool With Shodan.
  - [network-scanner](https://github.com/ivopetiz/network-scanner) TCP Network Port Scanner written in Go, nmap style.
  
- #### **ftp pentesting tools**
  - [ftp-fuzz](https://nullsecurity.net/tools/fuzzer.html) The master of all master fuzzing scripts specifically targeted towards FTP server software.
  - [ftp-spider](https://packetstormsecurity.com/files/35120/ftp-spider.pl.html) FTP investigation tool - Scans ftp server for the following: reveal entire directory tree structures, detect anonymous access, detect 
    directories with 
    write permissions, find user specified data within repository.
  - [ftpscout](https://github.com/RubenRocha/ftpscout) Scans ftps for anonymous access.
  - [ppscan](https://packetstormsecurity.com/files/82897/PPScan-Portscanner.3.html) Yet another port scanner with HTTP and FTP tunneling support.
  - [responder](https://github.com/lgandx/Responder) A LLMNR and NBT-NS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2 (multirelay version).
  - [dark-fantasy-hack-tool](https://github.com/ritvikb99/dark-fantasy-hack-tool) DDOS Tool: To take down small websites with HTTP FLOOD. Port scanner: To know the open ports of a site. FTP Password Cracker: To hack 
    file system of  websites.Banner Grabber: To get the service or software running on a port. (After knowing the software running google for its vulnerabilities.)
  - [Cyber-Sploit](https://github.com/Cyber-Dioxide/Cyber-Sploit) A framework like a metasploit containg a variety of modules for pentesting or ethical hacking. This repo willl be updated and new modules will be added 
    time to time.
  - [FTPDumper](https://github.com/MatrixTM/FTPDumper) FTPDumper is an easy-to-use yet advanced FTP server file stealer. It can be utilized in massive FTP brute-force attacks, supporting various formats such as combo, 
    pipe input, CIDR, 
    files, and even a single IP address.
  - [strongarm](https://github.com/whiterabb17/strongarm) Simple tool to bruteforce (spray actually) different network protocols.
  - [FTPSSH_Killer](https://github.com/usethisname1419/FTPSSH_Killer) Introducing FSK – your sophisticated brute-forcing tool tailored for SSH and FTP services. Unlike conventional brute-forcing, FSK emulates the 
   "password spraying" 
    approach by attempting three passwords per user. Once it exhausts the user list, it resumes by cycling through the next set of three passwords. This reduces the chance of lockouts and lost connections.
  - [FTP-Bruteforcer](https://github.com/calc1f4r/FTP-Bruteforcer) This is a Python script that implements an asynchronous FTP (File Transfer Protocol) bruteforcer. It utilizes asynchronous programming techniques to 
    efficiently perform 
    password guessing attacks on FTP servers.
  - [brutus](https://github.com/shehzade/brutus) Brutus is a fast and simple way to bruteforce authentication on network services such as SSH, FTP, IMAP, and more.
  - [redfox-ftp-brute-force](https://github.com/foxzinnx/redfox-ftp-brute-force) Red Fox FTP Brute Force Script.
  - [Ftp User enumeration script](https://raw.githubusercontent.com/pentestmonkey/ftp-user-enum/master/ftp-user-enum.pl) Ftp User enumeration with github script.
  - [TheSmartool](https://github.com/Coroxx/TheSmartool) The Smartool tool is a hacking script developed by me, your hacking courses will be easier.
  - [ftpbrute](https://github.com/machine1337/ftpbrute) A simple script for checking anonymous login as well as bruteforcing ftp accounts.
  - [Q-FTPBREAKER](https://github.com/secleGhost/Q-FTPBREAKER) Brute force for multithreaded FTP capable of analyzing thousands of ftp in a few seconds and finding their passwords.
  - [Q-FTPBREAKER-GUI](https://github.com/secleGhost/Q-FTPBREAKER-GUI) Brute force for multithreaded FTP capable of analyzing thousands of ftp in a few seconds and finding their passwords. It breaks Ftp in a few seconds 
    and performs a 
    bulk scan randomly or by defining a range.
  - [FTPBruteForce](https://github.com/rix4uni/FTPBruteForce) FTPBruteForce - A faster & simpler way to bruteforce FTP server.
  - [Q-VISION](https://github.com/secleGhost/Q-VISION) Port Scanner And break FTP.
  - [FTP-exploits](https://github.com/tfwcodes/FTP-exploits) FTP-exploits is a tool which is used for Penetration Testing that can run many kinds of exploits on port 21(FTP).
  - [BruteX](https://github.com/1N3/BruteX) Automatically brute force all services running on a target.

- #### **tftp pentesting tools**
  - [tftp-fuzz](https://nullsecurity.net/tools/fuzzer.html) Master TFTP fuzzing script as part of the ftools series of fuzzers.
  - [tftptheft](https://github.com/EnableSecurity/tftptheft) TFTP Theft is a tool which allows one to quickly scan/bruteforce a tftp server for files and download them instantly.

- #### **ssh pentesting tools**
  - [ssh-audit](https://github.com/jtesta/ssh-audit) SSH server & client security auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc).
  - [ssh-audit](https://github.com/arthepsy/ssh-audit/) SSH server auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc).
  - [against](https://nullsecurity.net/tools/cracker.html) A very fast ssh attacking script which includes a multithreaded port scanning module (tcp connect) for discovering possible targets and a multithreaded brute- 
     forcing module  
    which attacks parallel all discovered hosts or given ip addresses from a list.
  - [beleth](https://github.com/chokepoint/Beleth) Multi-threaded SSH Password Auditor.
  - [check-weak-dh-ssh](https://packetstormsecurity.com/files/66683/check_weak_dh_ssh.pl.bz2.html) 	Debian OpenSSL weak client Diffie-Hellman Exchange checker.
  - [Shreder](https://github.com/EntySec/Shreder) Shreder is a powerful multi-threaded SSH protocol password brute-force tool.
  - [ssh-privkey-crack](https://code.google.com/archive/p/lusas/) A SSH private key cracker.
  - [sshatter](http://www.nth-dimension.org.uk/downloads.php?id=34) Password bruteforcer for SSH.
  - [sshfuzz](https://packetstormsecurity.com/fuzzer/sshfuzz.txt) shfuzz is a SSH Fuzzing utility written in Perl that uses Net::SSH2.
  - [sshscan](https://github.com/phxbandit/scripts-and-tools/blob/master/sshscan.py) 	A horizontal SSH scanner that scans large swaths of IPv4 space for a single SSH user and pass.
  - [crowbar](https://github.com/galkan/crowbar) Crowbar is brute forcing tool that can be used during penetration tests. It is developed to support protocols that are not currently supported by thc-hydra and other 
    popular brute forcing 
    tools.
  - [ssh-snake](https://github.com/MegaManSec/SSH-Snake) SSH-Snake is a self-propagating, self-replicating, file-less script that automates the post-exploitation task of SSH private key and host discovery.
  - [SSHScan](https://github.com/evict/SSHScan) SSHScan is a testing tool that enumerates SSH Ciphers. Using SSHScan, weak ciphers can be easily detected.
 
- #### **smtp pentest tools**
  - [smtp-test](https://github.com/isaudits/smtp-test) Automated testing of SMTP servers for penetration testing.
  - [MailRipV2](https://github.com/DrPython3/MailRipV2) Improved SMTP Checker / SMTP Cracker with proxy-support, inbox test and many more features.
  - [Smtp-Craker](https://github.com/Aron-Tn/Smtp-cracker) Simple Mail Transfer Protocol (SMTP) CHECKER - CRACKER Tool V2.
  - [mailtools](https://github.com/aels/mailtools) Perfect scripts for all the hustle we have with mailing.
  - [Mass-Mailer-toolkit](https://github.com/alianse777/Mass-Mailer-toolkit) All-in-one mailing tool.
  - [Mess-SMTP-Checker](https://github.com/Tux-MacG1v/Mess-SMTP-Checker) MASS SMTP VALID INVALID CHECKER.
  - [SMTP-CHECKER](https://github.com/esfelurm/SMTP-CHECKER) A tool to check the correctness of email and password.
  - [BrokenSMTP](https://github.com/mrlew1s/BrokenSMTP) Small python script to look for common vulnerabilities on SMTP server.
  - [swaks](https://github.com/blackhatethicalhacking/swaks) Swaks - Swiss Army Knife for SMTP.

- #### **TACACS+ pentest tools**
   - [Loki](https://c0decafe.de/svn/codename_loki/trunk/) This is a special tool designed to analyze the security of L2/L3 protocols.

- #### **dns pentest tools**
  - [DNSrecon-gui](https://github.com/micro-joan/DNSrecon-gui) DNSrecon tool with GUI for Kali Linux.
  - [dnsx](https://github.com/projectdiscovery/dnsx) dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers.
  - [massdns](https://github.com/blechschmidt/massdns) A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration).
  - [dnscan](https://github.com/rbsec/dnscan) dnscan is a python wordlist-based DNS subdomain scanner.
  - [dig](https://packages.debian.org/buster/dnsutils) query the DNS in various ways.
  - [dnsenum](https://www.kali.org/tools/dnsenum) Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks.
  - [dnsrecon](https://github.com/darkoperator/dnsrecon) handy python script to perform DNS reconnaissance over remote hosts.
  - [fierce](https://github.com/mschwager/fierce) Fierce is a DNS reconnaissance tool for locating non-contiguous IP space.
  - [dnsrevenum6](https://github.com/vanhauser-thc/thc-ipv6/blob/master/dnsrevenum6.c) Simple and fast Reverse DNS Enumerator for IPv6.
  - [dnsscope](https://github.com/WhiteOakSecurity/dnsscope) Takes a list of IPs and TLDs in scope and automates DNS enumeration.
  - [dnsdumpster](https://github.com/nmmapper/dnsdumpster) A tool to perform DNS reconnaissance on target networks. Among the DNS information got from include subdomains, mx records, web application firewall detection 
    and more fingerprinting and lookups.
  - [dnsdumpster.com](https://dnsdumpster.com/) dns recon & research, find & lookup dns records.

- #### **finger pentest tools**
  - [finger-user-enum](https://pentestmonkey.net/tools/user-enumeration/finger-user-enum) Username guessing tool primarily for use against the default Solaris finger service.

- #### **kerberos pentest tools**
    - [rubeus](https://github.com/GhostPack/Rubeus) Rubeus is a C# toolset for raw Kerberos interaction and abuses.
    - [kerbrute](https://github.com/ropnop/kerbrute) A tool to quickly bruteforce and enumerate valid Active Directory accounts through Kerberos Pre-Authentication.
    - [PowershellKerberos](https://github.com/MzHmO/PowershellKerberos) Some scripts to abuse kerberos using Powershell.
    - [Ticket Injector](https://github.com/MzHmO/articles/tree/main/Ticket%20Injector) Manual tickets injection tool.
    - [Cerbere](https://github.com/OtterHacker/Cerbere) A project to play a little bit with Kerberos on Windows.

- #### **ident pentest tools**
  - [ident-user-enum](https://github.com/pentestmonkey/ident-user-enum) ident-user-enum is a simple PERL script to query the ident service (113/TCP) in order to determine the owner of the process listening on each TCP 
    port of a target system.

- #### **ntp pentest tools**
  - [ntp-dos-script](https://github.com/codeshold/ddos-dos-tools/blob/master/ntp-dos.py) ntp dos script in python.
 
- #### **msrpc pentest tools**
  - [rpctools](https://resources.oreilly.com/examples/9780596510305/tree/master/tools/rpctools) They are demostration programs for the Null Session and MSRPC concepts discussed at BlackHat Windows 2000.

- #### **netbios pentest tools**
  - [nbtscan](https://github.com/lifenjoiner/nbtscan) The NBTscan mod for Windows without dependency of cygwin.
  - [inbtscan](https://github.com/iiilin/inbtscan) Python nbtstat + smb_version without third party packages.

- #### **smb pentest tools**
  - [enum4linux](https://github.com/CiscoCXSecurity/enum4linux) enum4Linux is a Linux alternative to enum.exe for enumerating data from Windows and Samba hosts
  - [smbmap](https://github.com/ShawnDEvans/smbmap) SMBMap is a handy SMB enumeration tool.
  - [Nim-SMBExec](https://github.com/elddy/Nim-SMBExec) SMBExec implementation in Nim - SMBv2 using NTLM Authentication with Pass-The-Hash technique.
  - [SMBetray](https://github.com/quickbreach/SMBetray) SMB MiTM tool with a focus on attacking clients through file content swapping, lnk swapping, as well as compromising any data passed over the wire in cleartext.
  - [nullinux](https://github.com/m8sec/nullinux) Internal penetration testing tool for Linux that can be used to enumerate OS information, domain information, shares, directories, and users through SMB.
  - [SharpSMBSpray](https://github.com/rvrsh3ll/SharpSMBSpray) Spray a hash via smb to check for local administrator access.
  - [NetExec](https://github.com/Pennyw0rth/NetExec) The Network Execution Tool.
  - [MANSPIDER](https://github.com/blacklanternsecurity/MANSPIDER) Spider entire networks for juicy files sitting on SMB shares. Search filenames or file content - regex supported.
  - [enum4linux-ng](https://github.com/cddmp/enum4linux-ng) A next generation version of enum4linux (a Windows/Samba enumeration tool) with additional features like JSON/YAML export. Aimed for security professionals and 
    CTF players.

> [!NOTE]
> Tools are getting added daily.

