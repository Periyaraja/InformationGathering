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

### Finding Hosting Company :
<img width="1177" height="996" alt="Screenshot 2025-08-30 121504" src="https://github.com/user-attachments/assets/da564b08-c201-4658-90b9-b48dc470d4ec" />

### History of the website :
<img width="1665" height="988" alt="Screenshot 2025-08-30 122609" src="https://github.com/user-attachments/assets/fd925ac1-dc27-46cb-8a3e-c7cf4532eef0" />

### ping command :
<img width="1562" height="1097" alt="Screenshot 2025-08-30 122749" src="https://github.com/user-attachments/assets/154b6818-3836-4a16-b685-9dea11df06e8" />

### whois :
<img width="570" height="381" alt="Screenshot 2025-08-30 130349" src="https://github.com/user-attachments/assets/c6986fad-c500-4b28-bee3-a15eb0b7b621" />

### netcat :
<img width="744" height="99" alt="image" src="https://github.com/user-attachments/assets/7fe51d0d-9ba2-42c3-a6fb-d2929f23d1d1" />

### nmap :
<img width="875" height="334" alt="image" src="https://github.com/user-attachments/assets/1c94f3e1-6762-42c9-8b23-228bccdca379" />

### whatweb :
<img width="924" height="144" alt="image" src="https://github.com/user-attachments/assets/3602d5f4-c55d-40ed-9280-dc2f48fea05c" />

### httprint :
<img width="499" height="196" alt="image" src="https://github.com/user-attachments/assets/602d76d1-4705-41fb-bccb-46f8efa3e4bd" />

### TCP traceroute :
<img width="826" height="81" alt="image" src="https://github.com/user-attachments/assets/aa14c229-5e0e-4b5b-806f-028207ba438c" />

### UDP traceroute :
<img width="769" height="536" alt="image" src="https://github.com/user-attachments/assets/7790fbeb-156b-41a6-b2d3-4ba5f4a10856" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
