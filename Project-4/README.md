# Project 4 - Enterprise OSPF and ROAS Network

## Technologies Used

* VLANs
* Access Ports
* Trunking
* Router-on-a-Stick (ROAS)
* OSPF Dynamic Routing
* DHCP Server
* DHCP Relay (IP Helper Address)
* Inter-VLAN Routing

## Network Overview

This project simulates an enterprise network connecting a Head Office and two Branch Offices.

Each office contains two VLANs and uses Router-on-a-Stick (ROAS) for inter-VLAN routing. The Head Office router acts as a centralized DHCP server, while the branch routers forward DHCP requests using DHCP Relay.

OSPF is configured between all routers to dynamically exchange routing information and provide connectivity between all office networks.

## Features

* Three-site enterprise network.
* Two VLANs per office.
* Router-on-a-Stick configuration.
* OSPF dynamic routing.
* Centralized DHCP services.
* DHCP Relay for branch offices.
* Inter-VLAN communication.
* End-to-end connectivity between all offices.

## Skills Demonstrated

* Enterprise Network Design
* VLAN Configuration
* Trunk Configuration
* Router-on-a-Stick (ROAS)
* OSPF Dynamic Routing
* DHCP Configuration
* DHCP Relay
* Network Troubleshooting
* Cisco Packet Tracer

## Project Outcome

The enterprise network was successfully implemented. All routers established OSPF neighbor relationships, branch offices received IP addresses from the centralized DHCP server, and all hosts were able to communicate across VLANs and office locations.
