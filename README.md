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
<img width="1918" height="973" alt="image" src="https://github.com/user-attachments/assets/09f782a4-e933-4221-b26e-a939b86ebe7a" />

### Finding Hosting Company :
<img width="1122" height="896" alt="image" src="https://github.com/user-attachments/assets/59fa85e6-6871-484b-8991-d9da8cea2475" />

### History of the website :
<img width="1904" height="969" alt="image" src="https://github.com/user-attachments/assets/6c93df32-8b98-4587-bebc-e2ab57c10a0b" />

### ping command :
<img width="1485" height="429" alt="image" src="https://github.com/user-attachments/assets/e4b29c41-a1e6-4125-9343-1c527e3d16f4" />

### netcat :

### nmap :
<img width="938" height="261" alt="image" src="https://github.com/user-attachments/assets/edd9d265-aca9-4e8c-9b7b-898a0f53e12a" />

### whatweb :
<img width="949" height="223" alt="image" src="https://github.com/user-attachments/assets/67efbaa8-f61b-484a-8863-ad6429e4363d" />

### httprint :

### TCP traceroute :
<img width="937" height="102" alt="image" src="https://github.com/user-attachments/assets/42f98814-5781-4365-acf8-926c87a5a035" />

### UDP traceroute :
<img width="942" height="540" alt="image" src="https://github.com/user-attachments/assets/26c7ae04-ae18-4c2d-94aa-3b0fb389ff59" />

### ICMP traceroute :
<img width="941" height="543" alt="image" src="https://github.com/user-attachments/assets/b6db0802-58f9-48f8-8d4b-a17c4e651f6c" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
