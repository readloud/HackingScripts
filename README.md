# HackingScripts 

This repository contains self-made [rhergenreder](https://github.com/rhergenreder/HackingScripts.git) and common scripts for information gathering, enumeration and more.

### Enumeration: Initial Scans
- first_scan.sh: Performs initial nmap scan
- gobuster.sh: Performs gobuster dir scan with raft-large-words-lowercase.txt
- ssh-check-username.py: Check if user enumeration works for ssh
- [git-dumper.py](https://github.com/arthaud/git-dumper)
- subdomainFuzz.sh: Fuzzes subdomains for a given domain

### Enumeration: Privilege Escalation & Pivoting
- [LinEnum.sh](https://github.com/rebootuser/LinEnum)
- [linpeas.sh](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite)
- lse.sh
- unix-privesc-check.sh
- [uptux.py](https://github.com/initstring/uptux)
- [pspy64](https://github.com/DominicBreuker/pspy)
- portscan.py: small python script, which scans open TCP ports natively with multithread support.
Can be deployed on victim machines to scan the intranet.
- pingscan.py: small python script, which can detect internal hosts via ping probes natively.
Can be deployed on victim machines to scan the intranet.
- [deepce.sh](https://github.com/stealthcopter/deepce): Docker Privilege Escalation (e.g. exposed socket)

### Reverse Shell: Payloads
- genRevShell.py: Generates a reverse shell command (e.g. netcat, python, ...)
- [php-reverse-shell.php](https://github.com/pentestmonkey/php-reverse-shell)
- [p0wny-shell.php](https://github.com/flozz/p0wny-shell)
- [aspx-reverse-shell.aspx](https://github.com/borjmz/aspx-reverse-shell)
- jsp-webshell.jsp: webshell for Java servlets

### Miscellaneous
- upload_file.py: Starts a local tcp server, for netcat usage
- xss_handler.py: Starts a local http server and generates xss payload to steal cookies
- [padBuster.pl](https://github.com/AonCyberLabs/PadBuster)
- sql.php: Execute sql queries passed via GET/POST
- util.py: Collection of some small functions
- fileserver.py: Create a temporary http server serving in-memory files
- dnsserver.py: Create a temporary dns server responding dynamically to basic DNS requests (in-memory)

### Windows
 - nc.exe/nc64.exe: netcat standalone binary
 - [mimikatz.exe](https://github.com/gentilkiwi/mimikatz)
 - [plink.exe](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html): command line PuTTY client for port forwarding
 - [powercat.ps1](https://github.com/besimorhino/powercat)
 - [winPEAS.bat](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite)
 - PowerView.ps1
 - [SharpHound.exe](https://github.com/BloodHoundAD/SharpHound3): BloodHound Ingestor
 - [windows-exploit-suggester.py](https://github.com/AonCyberLabs/Windows-Exploit-Suggester)
 - [aspx-reverse-shell.aspx](https://github.com/borjmz/aspx-reverse-shell)
 - [xp_cmdshell.py](https://github.com/0xalwayslucky/pentesting-tools) (thanks to @alwayslucky)
