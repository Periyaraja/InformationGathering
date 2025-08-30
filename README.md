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
<img width="1177" height="996" alt="Screenshot 2025-08-30 121504" src="https://github.com/user-attachments/assets/679b6425-168c-46e6-a85a-db1229db87d9" />

### Finding Hosting Company :
<img width="1665" height="988" alt="Screenshot 2025-08-30 122609" src="https://github.com/user-attachments/assets/256337e9-bf73-411d-aea6-ab818b411782" />

### History of the website :
<img width="1562" height="1097" alt="Screenshot 2025-08-30 122749" src="https://github.com/user-attachments/assets/c93827cc-8780-4584-a617-59b10a6b0498" />

### ping command :
<img width="570" height="381" alt="Screenshot 2025-08-30 130349" src="https://github.com/user-attachments/assets/84541bdd-a70a-453c-b818-b7a6d1805239" />

### whois :
<img width="914" height="764" alt="image" src="https://github.com/user-attachments/assets/064d8bdf-e421-4b03-aac5-c9e5eb52994d" />

### netcat :
<img width="744" height="99" alt="Screenshot 2025-08-30 203357" src="https://github.com/user-attachments/assets/59d766cf-bf69-4be9-bc15-b990eb405a00" />

### nmap :
<img width="875" height="334" alt="Screenshot 2025-08-30 201604" src="https://github.com/user-attachments/assets/0cf63c92-c90b-4e88-85e0-3db7bccc0dc1" />

### whatweb :
<img width="924" height="144" alt="Screenshot 2025-08-30 201708" src="https://github.com/user-attachments/assets/010e522b-c5c5-45d3-aa3a-24f846ddda02" />

### httprint :
<img width="499" height="196" alt="Screenshot 2025-08-30 202013" src="https://github.com/user-attachments/assets/4342bc66-87bc-4ed1-9e30-afc29461fe4f" />

### TCP traceroute :
<img width="826" height="81" alt="Screenshot 2025-08-30 202129" src="https://github.com/user-attachments/assets/2055ad34-c5c7-4e5d-93b3-267697d299d3" />

### UDP traceroute :

<img width="769" height="536" alt="Screenshot 2025-08-30 202258" src="https://github.com/user-attachments/assets/04c4be79-978b-4a85-8d43-6519b9564ded" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
