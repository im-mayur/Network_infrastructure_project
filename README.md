# Enterprise Network Infrastructure Project

## Overview
This is a high-availability 3-tier enterprise network (Access, Core, Edge) design with secure segmentation, redundancy, and controlled inter-VLAN communication.

## Tech Stack
VLAN | Inter-VLAN Routing | HSRP | OSPF | NAT (PAT) | EtherChannel (LACP) | Extended ACLs | DHCP & Static  Addressing

## Key Implementations
- Built segmented network for NOC, Web, and SQL environments  
- Configured Inter-VLAN routing using Layer-3 switches  
- Deployed HSRP for gateway redundancy and failover  
- Used EtherChannel (LACP) for link aggregation and redundancy 
- Implemented OSPF for dynamic routing between core and edge  
- Configured NAT overload for internet access  
- Applied Extended ACLs for restricted inter-VLAN communication (Zero-Trust model)   


## Outcome
Outcomes:
• Designed and implemented a 3-tier enterprise network topology (Access, Core, Edge) supporting isolated Web, SQL, and NOC infrastructure segments.

• Implemented VLAN segmentation and Inter-VLAN routing using Layer-3 switches to enforce logical separation between management, application, and database tiers.

• Deployed HSRP dual-core gateway redundancy, ensuring uninterrupted connectivity through automatic failover.

• Configured OSPF dynamic routing between core switches and edge router for intelligent path selection and rapid convergence.

• Optimized backbone throughput using LACP EtherChannel, aggregating links to increase bandwidth and eliminate single-link failure impact.

• Enforced Zero-Trust traffic policies using Extended ACLs, restricting lateral movement and permitting only service-specific communication.

• Validated high-availability design by simulating core switch failure and confirming seamless HSRP failover with no gateway interruption.



## Project Guide
- Docs/
  This consits the entire documentation of project.
 
- Topology Diagram/
  Logical topology design showcasing the devices, cable connectivity, ip addressing summarizing the outline of project.

- Simulation/
  .pkt file where the project is designed, implemented and tested.

  *Note: requires cisco packet tracer application to open and execute. 

- Device Configurations/
  Configuration files of used devices.

- Results/
  Quick verification of successful implementation of project. 
  For more detailed explanation refer to "Results and Testing" section of dcumentation in "docs/"