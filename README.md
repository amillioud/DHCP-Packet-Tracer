# DHCP Packet Tracer Lab

**Author:** Millioud NetLab  
**Date:** [06-04-2025] 

## Objectives

1. Configure the following DHCP pools on R2:
POOL1: 192.168.1.0/24 (reserve .1 to .10)
     DNS 8.8.8.8
     Domain: jeremysitlab.com
     Default Gateway: R1
POOL2: 192.168.2.0/24 (reserve .1 to .10)
     DNS 8.8.8.8
     Domain: jeremysitlab.com
     Default Gateway: R2
POOL3: 203.0.113.0/30 (reserve .1)

2. Configure R1's G0/0 interface as a DHCP client.
    What IP address did it configure?

3. Configure R1 as a DHCP relay agent for the 192.168.1.0/24 subnet.
 
4. Use the CLI of PC1 and PC2 to make them request an IP address 
    from their DHCP server.

## Topology

<img width="591" alt="Captura de Pantalla 2025-04-06 a la(s) 13 16 15" src="https://github.com/user-attachments/assets/3244058d-e763-41a8-949d-7f125bfc96de" />
