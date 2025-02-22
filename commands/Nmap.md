# NMAP

`nmap =h`

`nmap -A -vv -T4 <IP>` or `nmap -O -sV -vv -T4 <IP>`

- `nmap`: runs nmap scanner
- `-A`: enables OS detection, version detection, script scanning, and traceroute. It is a shorthand for `-O -sV -sC --traceroute`
- `-O`: enables OS detection
- `-sV`: enables version detection, version of services
- `-vv`: increases verbosity, detailed info about scan
- `T4`: timing template set to 4, balances speed and stealth
