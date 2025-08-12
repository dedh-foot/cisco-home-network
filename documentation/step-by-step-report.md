## Table of Contents

1. [Project Overview](#project-overview)
2. Network Topology
3. Device Configurations
   ###### 3.1 Switch0 Configuration

   ###### 3.2
5. IP Addressing and Ethernet Ports
6. Device Setup and Testing
   ###### 6.1 Configuring PC1
7. Testing Connectivity
8. Summary


#### Project Overview
This project documents the process of building a home network. It involves documentation of the design, configuration and testing of a simulated network using Cisco Packet Tracer. Included are network diagrams, device configurations and reports for reference. All screenshots, config files and diagrams are linked wherever necessary. You can also view these folders independently if you wish to.

#### Network Topology
This network consists of a basic loal area network (LAN) setup with 2 laptops connected to a single switch. The switch acts as a central device that facilitates communication between the two end devices. 

 ##### Devices
 - One unmanaged switch (Switch0)
 - Two Laptops (Laptop1 & Laptop2)

 ##### Connections
  - Each laptop is connected to the switch using Ethernet Cables.
  - The switch provides a common network segment allowing the laptops to communicate directly.

##### Network Topology Screenshot

<img width="857" height="426" alt="image" src="https://github.com/user-attachments/assets/6ec186ee-a27e-4931-81c9-0affe59778b1" />


#### Device Configurations

##### Switch Configuration
The switch used for this project is the 3650-24PS Multilayer switch. 

<img width="162" height="174" alt="image" src="https://github.com/user-attachments/assets/598a9141-ef1e-4550-9dfc-89f31240a688" />

From now on, it is going to be referred to as the Switch0.

To configure Switch0, open the device configuration window & switch it on by dragging an AC-POWER-SUPPLY on to physical device view section.
This is the device configuration window without the AC-POWER-SUPPLY:

<img width="463" height="400" alt="image" src="https://github.com/user-attachments/assets/73e7101f-4100-460e-9559-a03756ff7b49" />

This is the device configuration window after the AC-POWER-SUPPLY is attached:

<img width="464" height="400" alt="image" src="https://github.com/user-attachments/assets/bffa3c36-c750-486b-b7f1-ad37d6954df6" />

> Notice that a blank spot is filled when attaching the power supply.


