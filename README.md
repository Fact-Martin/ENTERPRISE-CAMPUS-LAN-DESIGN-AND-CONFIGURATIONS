## ENTERPRISE-CAMPUS-LAN-DESIGN-AND-CONFIGURATIONS
Secure and redundant enterprise network design using Packet Tracer with high availability

## PROJECT DESCRIPTION 
Enterprise Campus LAN Design and Configurations. A secure, highly available campus network implemented in Cisco Packet Tracer with VLANs, HSRP, OSPF, DHCP Snooping, Dynamic ARP Inspection, SSH management and Port Security.

## TABLE OF CONTENTS
-> Overview
-> Topology Diagram
-> Features & Technologies
-> VLAN/IP Plan
-> Configuration Files
-> Testing & Validation
-> How to Use

## TECHNOLOGIES USED
-> VLANs (10,20,30,40)(IT, FINANCE,LEGAL, CUSTOMER-CARE)
-> Inter-VLAN Routing using SVIs
-> HSRP (Standby Version 2)
-> OSPF (Single-area)
-> DHCP Snooping
-> Dynamic ARP Inspection (DAI)
-> PortFast & BPDU Guard
-> SSH (VLAN-restricted management)
-> Port Security.

## NETWORK ARCHITECTURE
-> Core Layer: Dual Routers
-> Distribution Layer: 2 Multilayer Switches
-> Access Layer: 4 Access Switches
-> Dedicated Management VLAN (VLAN 10 for IT).

## HIGH AVAILABILITY
-> HSRP configured on Distribution Switch SVIs
-> Redundant trunk links
-> OSPF routing between Core and Distribution 
-> L3 Etherchannell between Distribution switches.

## SECURITY FEATURES
-> DHCP Snooping enabled on Access switches
-> Trusted ports configured towards Distribution switches
-> Dynamic ARP Inspection using DHCP Snooping bindings
-> PortFast and BPDU Guard on end-user access ports
-> SSH access restricted to VLAN 10 using ACLs
-> Port security on access switches.

## VALIDATION & TESTING
-> Verified HSRP failover
-> Verified DHCP lease assignment across VLANs
-> Verified SSH access from management VLAN only

## AUTHOR
**MARTIN FACT CHUNGA**  
CCNA | Network Engineering 




