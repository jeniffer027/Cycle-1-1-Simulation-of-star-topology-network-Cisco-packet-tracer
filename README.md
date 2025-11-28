# Cycle-1-----1-Simulation-of-star-topology-network
# 🖧 Network Simulation using Cisco Packet Tracer

## 🎯 AIM
To simulate a network with topology using Cisco Packet Tracer and verify connectivity between computers using ICMP.

## 🛠️ EQUIPMENTS REQUIRED
- Desktop Computer  
- Cisco Packet Tracer 5.0 Software

## 📍 IP ASSIGNMENT
<img width="657" height="366" alt="Screenshot 2025-11-28 082401" src="https://github.com/user-attachments/assets/2bea79a5-b076-42ad-976f-c657b99d5356" />


## ⚙️ PROCEDURE

1. Open Cisco Packet Tracer software.  
2. Drag a 2950 Switch from the toolbar and drop it into the workspace.  
3. Drag a PC terminal from the toolbar and drop it into the workspace.  
4. Repeat Step 3 to add four more terminals.  
5. Select Copper Straight-Through cable and connect each PC to the 2950 switch using different ports.  
6. Click on each PC, select the Fast Ethernet interface, and assign the IP address and subnet mask.  
7. Repeat Step 6 for all PC terminals.  
8. Open the Terminal tab from the Desktop section of each PC and verify connectivity using the `ping` command.  
9. Use “Add Simple PDU” from the toolbar to test connectivity between source and destination PCs.

## 📊 IP CONNECTIVITY TABLE
<img width="755" height="358" alt="Screenshot 2025-11-28 082445" src="https://github.com/user-attachments/assets/c7ae6647-be76-4860-968a-f378a6a00f30" />


## 🗺️ NETWORK DIAGRAM
---
<img width="1024" height="326" alt="image" src="https://github.com/user-attachments/assets/101f648b-4a63-4b6c-9ad7-a0deab535f0b" />



## 🧾 BASIC NETWORKING COMMANDS

## IP Configuration
## IP Configuration Details: 
## (i)	ipconfig Command(windows OS) (or) ifconfig command(Linux OS) Syntax: C:\> ipconfig 
## (ii)	ipconfig/all Command:
## Syntax:
C:\> ipconfig /all 
## Testing Connectivity: 
## (i)	Self Ping Command:
## Syntax:
## c:\> ping <ipaddress> Example:
## C:\> ping 172.17.80.201
## C:\> ping 127.0.0.1 (ii) Ping to Destination Syntax:
## c:\> ping <destination-ipaddress> Example:
## C:\ping 172.17.80.1
## To Display IP to Physical address Translation Table and trace the route
## i) Arp Command Syntax:
 
## C:\arp –a
## (ii)	To trace the route Syntax:
## C:\tracert <ipaddress (or) specific address> Example: C:\tracert 172.17.80.1
## C:\tracert www.saveetha.ac.in

## OUTPUT
---
<img width="1088" height="796" alt="image" src="https://github.com/user-attachments/assets/ba7621e4-1431-4d59-9bff-34bd1d371e10" />
<img width="1920" height="1021" alt="image" src="https://github.com/user-attachments/assets/f245b354-387e-4de0-84b0-7b7a2bdabf50" />



## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified
