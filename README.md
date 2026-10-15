## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15.10.2026		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1920" height="1080" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/e131301e-4e3f-4559-a99b-69c6b2dce08c" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1920" height="1020" alt="Screenshot 2026-10-15 173922" src="https://github.com/user-attachments/assets/e59c078f-175a-4018-a443-69905b2476dc" />
<img width="1920" height="1020" alt="Screenshot 2026-10-15 174538" src="https://github.com/user-attachments/assets/015132d2-833b-4708-94ef-344c8d08db54" />
<img width="1920" height="1080" alt="Screenshot (225)" src="https://github.com/user-attachments/assets/05677181-9fcc-4985-879e-b2e9b93743e1" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
