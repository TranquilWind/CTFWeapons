# Samba

Examples: [Kioptrix Level 1](https://github.com/TranquilWind/Kioptrix-Solutions/blob/main/Kioptrix-1.md)

### Metasploit
- If no version is found, use metasploit's aucillary scanner
- not just versions, there are other scanners that can be tried
- smbclient - L \\\\<target ip\\ can also be used to enumerate users (or just login if password)
- After finding version, search again in metasploit for exploits
- Refer here if any issues: [Link](https://github.com/TranquilWind/Kioptrix-Solutions/blob/main/Kioptrix-1.md#method-1-metasploit)
- The above link says to change payloads, which I think is an issue of metasploit, applicable for most services if any issue

### Manual Exploitation
- ExploitDB, in my example it was [Samba < 2.2.8 (Linux/BSD) - Remote Code Execution ](https://www.exploit-db.com/exploits/10)
- `gcc file.c -o file`
- `./file` for details
- `./file -b 0 <IP>` normal exploit
