# ResortNet --- Multi-Floor Hotel Network Design

A Cisco Packet Tracer networking project that models the network
infrastructure of a multi-floor hotel or resort. The topology brings
together departmental LANs, VLAN-based segmentation, router
interconnections, wired endpoints, printers, and wireless access points.

## Project Overview

ResortNet is a practice project focused on designing and documenting a
structured network for a hotel environment. The topology is organized by
floors and departments to make the layout easier to understand and
maintain.

## Network Design

The current topology diagram includes:

-   Three routers connected through point-to-point serial links using
    `/30` subnets.
-   Multiple Cisco 2960 access switches distributed across the floors.
-   Departmental VLANs labelled in the topology:
    -   VLAN 10 --- `192.168.1.0/24`
    -   VLAN 20 --- `192.168.2.0/24`
    -   VLAN 30 --- `192.168.3.0/24`
    -   VLAN 40 --- `192.168.4.0/24`
    -   VLAN 50 --- `192.168.5.0/24`
    -   VLAN 60 --- `192.168.6.0/24`
    -   VLAN 70 --- `192.168.7.0/24`
    -   VLAN 80 --- `192.168.8.0/24`
-   Wired end devices, including PCs and printers.
-   Wireless access points with laptop and smartphone clients.
-   Floor- and department-based logical grouping to help visualize the
    hotel network.

> **Note:** VLAN IDs and subnet labels above are transcribed from the
> topology diagram. Verify that the Packet Tracer configuration matches
> these labels before presenting the project as fully configured.
> Inter-VLAN routing, routing protocol operation, DHCP, and end-to-end
> connectivity should only be listed as completed after testing them in
> Packet Tracer.

## Objectives

-   Design a network topology for a multi-floor hotel/resort.
-   Organize devices into departmental VLANs.
-   Plan IPv4 subnets for the different network segments.
-   Connect routers using point-to-point links.
-   Include wired and wireless client connectivity.
-   Practice network documentation and troubleshooting.

## Tools and Technologies

-   Cisco Packet Tracer
-   Cisco routers and 2960 switches
-   VLANs and IPv4 addressing
-   Serial point-to-point links
-   Wireless access points
-   PCs, printers, laptops, and smartphones

## Repository Structure

``` text
resortnet-hotel-network-design/
├── README.md
├── packet-tracer/
│   └── resortnet-hotel-network.pkt
└── screenshots/
    ├── full-topology.png
    ├── floor-1.png
    ├── floor-2.png
    └── floor-3.png
```

Replace the example `.pkt` filename with the actual Packet Tracer file
name. Add screenshots to the `screenshots/` folder if you want to use
the suggested structure.

## How to Open the Project

1.  Install Cisco Packet Tracer.
2.  Download or clone this repository.
3.  Open the `.pkt` file in Cisco Packet Tracer.
4.  Inspect the topology, device interfaces, VLAN assignments, IP
    addressing, and router configurations.
5.  Test connectivity with `ping` and relevant device CLI commands.

## Validation Checklist

Before marking the project complete, verify the following in Packet
Tracer:

-   [ ] VLANs exist on the required switches.
-   [ ] End-device switch ports are assigned to the intended VLANs.
-   [ ] Trunks are configured where VLAN traffic must cross switch
    links.
-   [ ] Router serial interfaces have the intended IP addresses and are
    up.
-   [ ] Routing is configured so the required networks can reach one
    another.
-   [ ] Inter-VLAN routing is configured if communication between VLANs
    is required.
-   [ ] Wireless clients associate with the intended access point and
    receive valid IP settings.
-   [ ] Required PC-to-PC, PC-to-printer, and cross-floor connectivity
    tests pass.

## Learning Outcomes

This project provides practice with network topology design, VLAN
planning, IPv4 subnetting, router and switch interfaces, wireless
access, and systematic connectivity troubleshooting.

## Project Status

**Status:** Network design / Packet Tracer lab.

Update this status to **Configured and tested** only after validating
the relevant VLANs, routing, wireless connectivity, and end-to-end
communication.

## Author

**Prem Lawand**\
Cybersecurity and networking learner

------------------------------------------------------------------------

This project is intended for educational and lab practice.
