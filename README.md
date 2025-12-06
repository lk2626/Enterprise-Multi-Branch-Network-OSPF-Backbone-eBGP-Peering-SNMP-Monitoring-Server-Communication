# Enterprise-Multi-Branch-Network-OSPF-Backbone-eBGP-Peering-SNMP-Monitoring-Server-Communication
This project implements an enterprise-grade multi-branch network using OSPF for internal routing, eBGP for inter-branch communication, and SNMP for centralized monitoring. The network includes eight routers, branch LANs, a server network, and secure WAN IP addressing.

Network Architecture Overview
   
OSPF (Area 0) Backbone

Used for internal routing between core routers.

eBGP Peering

Used for exchanging branch prefixes across different autonomous systems.

SNMP Monitoring

Enabled for network device monitoring and management.

Central Server Segment

DNS, HTTP, and SSH services hosted in the main data center.

Branch LANs

Each router contains a dedicated /24 LAN for user devices.

Conclusion

This topology provides a complete enterprise-level multi-branch network setup including dynamic routing, inter-AS communication, SNMP monitoring, and server access. This project can be used for CCNP practice, WAN design study, and real-world branch architecture understanding.
