# Nmap Vulnerability Scan – Hands-On Cybersecurity Project

This project is a real-world demonstration of my growing skills in ethical hacking and cybersecurity using the Nmap tool.

I performed a vulnerability scan against `scanme.nmap.org` using advanced Nmap scripting to identify:
- Open ports
- Running services
- Operating system details
- CVEs (Common Vulnerabilities and Exposures)
- Public exploits for known vulnerabilities

## Tools Used
- **Nmap 7.95**
- **Mac Terminal (zsh)**
- `--script vuln` for vulnerability detection
- `-sV` for service version detection
- `-oN` to output results into a text file

## Key Results
```bash
sudo nmap -sV --script vuln scanme.nmap.org -oN vuln_scan.txt
## Key Results
- Discovered open ports like `22`, `80`, `9929`, and `31337`
- Detected services like `Apache httpd`, `OpenSSH`, and `Nping echo`
- Found multiple CVEs with links to known public exploits
- Exported a clean `.txt` file of the scan results for documentation
## About Me
Hi, I’m Kourtney — a cybersecurity student passionate about ethical hacking, threat analysis, and protecting systems from vulnerabilities. I’m building a hands-on portfolio to showcase my growth in InfoSec.

This is one of many projects I’ll be adding as I work toward a career in cybersecurity.

Let's connect: [LinkedIn](https://www.linkedin.com/in/kourtney-b-a2158b127/)

