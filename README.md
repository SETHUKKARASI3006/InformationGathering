# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="1011" height="812" alt="image" src="https://github.com/user-attachments/assets/db5ea409-16fa-4e14-ac0c-c734a8ba5a87" />

### Finding Hosting Company :

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/b0f73450-e0ee-4286-9fe6-4eab3741fdf7" />

### History of the website :

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/9846723e-d404-4cc1-a67b-dd19efe029ac" />

### ping command :

<img width="646" height="465" alt="image" src="https://github.com/user-attachments/assets/7e80b99a-4925-4308-9d70-219f67cf51b5" />

### netcat :

<img width="632" height="317" alt="image" src="https://github.com/user-attachments/assets/7e618bd5-20f6-429c-a9ef-efccbc46cfb1" />

### nmap :

<img width="540" height="231" alt="image" src="https://github.com/user-attachments/assets/97c0c87a-6fdd-4c9c-9a45-5b7b7103604a" />

### whatweb :

<img width="626" height="302" alt="image" src="https://github.com/user-attachments/assets/ec754db0-6eea-4af4-a740-32bd2ae56056" />

### httprint :

<img width="667" height="103" alt="image" src="https://github.com/user-attachments/assets/27eb07b6-6042-483e-b4f9-19a3ef01e662" />

### TCP traceroute :

<img width="670" height="98" alt="image" src="https://github.com/user-attachments/assets/09d9f980-4594-4d3f-b2d6-394322592e43" />

### UDP traceroute :

<img width="627" height="97" alt="image" src="https://github.com/user-attachments/assets/4f1261c4-d064-4f76-b944-e2db21855d1a" />

### ICMP Traceroute:

<img width="632" height="98" alt="image" src="https://github.com/user-attachments/assets/fe9d2a58-e1da-478d-bde8-d689eaa6a3a9" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
