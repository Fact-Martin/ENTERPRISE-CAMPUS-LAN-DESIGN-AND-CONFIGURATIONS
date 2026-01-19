## ENTERPRISE-CAMPUS-LAN-DESIGN-AND-CONFIGURATIONS
Secure and redundant enterprise network design using Packet Tracer with high availability

## PROJECT DESCRIPTION 
Enterprise Campus LAN Design and Configurations. A secure, highly available campus network implemented in Cisco Packet Tracer with VLANs, HSRP, OSPF, DHCP Snooping, Dynamic ARP Inspection, SSH management and Port Security.

## **Lab Overview**

The lab demonstrates:

- **Redundant network design** using OSPF, HSRP, and VLANs.
- **High availability** with Layer 3 EtherChannel and gateway redundancy.
- **Network segmentation** for multiple departments (IT, Finance, Legal, Customer Care).
- **Secure access layer** with port security, DHCP snooping, and Dynamic ARP Inspection (DAI).
- **On-site server integration** and support for Windows and Linux servers.


## **Repository Structure / Configuration Files**

| File Name | Device | Description |
|-----------|--------|-------------|
| R1.txt    | Router 1 | OSPF, loopback, Gigabit interfaces, SSH config |
| R2.txt    | Router 2 | OSPF, loopback, Gigabit interfaces, SSH config |
| DSW1.txt  | Distribution Switch 1 | VLANs, HSRP, L3 EtherChannel, trunk ports |
| DSW2.txt  | Distribution Switch 2 | VLANs, HSRP, L3 EtherChannel, trunk ports |
| ASW1.txt  | Access Switch 1 | VLAN assignment, trunk, access ports, port security |
| ASW2.txt  | Access Switch 2 | VLAN assignment, trunk, access ports, port security |
| ASW3.txt  | Access Switch 3 | VLAN assignment, trunk, access ports, port security |
| ASW4.txt  | Access Switch 4 | VLAN assignment, trunk, access ports, DHCP server connection |

## **How to Use**

1. Open the configuration file in a Cisco simulator (Packet Tracer, GNS3,physical devices).  
2. Copy the commands to the respective device.  
3. Verify connectivity, HSRP redundancy, and OSPF routing.  
4. Observe VLAN segmentation, port security, and DHCP/DAI functionality.

## **Links**

- [GitHub Repository](https://github.com/Fact-Martin/ENTERPRISE-CAMPUS-LAN-DESIGN-AND-CONFIGURATIONS)  
- [Video Walkthrough](https://rumble.com/v74fh3g) 


## **Author**

**Martin Fact Chunga**  
  CCNA | Network Engineer




