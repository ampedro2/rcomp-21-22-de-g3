RCOMP 21/22 - Sprint 3 - Planning document
===========================================
### Sprint master: 1201371
# Sprint 3 backlog


| Task  | Description  |
|---|---|
|  T.3.1 | Update the building1.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 1.  |
| T.3.2  | Update the building2.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 2. Final integration of each member’s Packet Tracer simulation into a single simulation (campus.pkt).  |
|  T.3.3 |  Update the building3.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 3. |
| T.3.4  |  Update the building4.pkt layer three Packet Tracer simulation from the previous sprint, to include the described features in this sprint for building 4. |

# Subtasks assignment

* **T.3.1**-1201384

* **T.3.2**-1201371

* **T.3.3**-1201381

* **T.3.4**-1201276

# Name of the devices

* **PC/Laptop/Server/IP-Phone:** [Device name][Number of device]_[Number of building]
* **Ap:** AP_[Number of building]
* **Switches(HC/CP):** [Cross-Connect type]_[Floor number]_[Number of building]
* **Switches(Ic):** IC_[Number of building]
* **Switch(MC):** MC
* **Routers:** R[Number of device][Number of Building]

#Technical decisions

###OSPF area IDs used
Backbone OSPF area id - 0
Building 1 OSPF area id - 1
Building 2 OSPF area id - 2
Building 3 OSPF area id - 3
Building 4 OSPF area id - 4

###VoIP phone numbers

**Building 1**
* VOIP prefix F0 - 1000
* VOIP prefix F1 - 1001

**Building 2**
* VOIP prefix F0 - 2000
* VOIP prefix F1 - 2001

**Building 3**
* VOIP prefix F0 - 3000
* VOIP prefix F1 - 3001

**Building 4**
* VOIP prefix F0 - 4000
* VOIP prefix F1 - 4001

###DNS domain names to be used

**Building 1**
* DNS server name: ns.rcomp-21-22-de-g3

**Building 2**
* DNS server name: ns.building-2.rcomp-21-22-de-g3

**Building 3**
* DNS server name: ns.building-3.rcomp-21-22-de-g3

**Building 4**
* DNS server name: ns.building-4.rcomp-21-22-de-g3

###IPv4 node address of the DNS name server

* Building 1: 172.16.217.2
* Building 2: 172.16.220.242
* Building 3: 172.16.221.226
* Building 4: 172.16.222.242