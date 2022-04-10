RCOMP 21/22 - Sprint 2 - PLanning document
===========================================
### Sprint master: 1201384


# Sprint 2 backlog


| Task  | Description  |
|---|---|
|  T.2.1 | Development of a layer two and layer three Packet Tracer simulation for building one, encompassing the campus backbone. Integration of every member’s Packet Tracer simulation into a single simulation.  |
| T.2.2  | Development of a layer two and layer three Packet Tracer simulation for building two, encompassing the campus backbone.  |
|  T.2.3 |  Development of a layer two and layer three Packet Tracer simulation for building three, encompassing the campus backbone. |
| T.2.4  |  Development of a layer two and layer three Packet Tracer simulation for building four, encompassing the campus backbone. |

# Subtasks assignment

* **T.2.1**-1201384

* **T.2.2**-1201371

* **T.2.3**-1201381

* **T.2.4**-1201276



# Name of the devices

* **PC/Laptop/Server/IP-Phone:** [Device name][Number of device]_[Number of building]
* **Ap:** AP_[Number of building]
* **Switches(HC/CP):** [Cross-Connect type]_[Floor number]_[Number of building]
* **Switches(Ic):** IC_[Number of building]
* **Switch(MC):** MC
* **Routers:** R[Number of device][Number of Building]


##**Range of VLANS:** 250-280

| Building  | Range |
|---|---|
| 1 + backbone  | 250-255   |
|  2 |  256-260 |
|  3 |  261-265 |
| 4  |  266-270 |


|  Vlan id | Vlan name  |
|---|---|
| 250  | backbone  |
|  251 | wifib1  |
|  252 |  gfb1  |
| 253  |  fob1 |
| 254  | voipb1  |
| 255  |  dmzb1 |
| 256  | wifib2  |
| 257  |  gfb2 |
| 258  | fob2   |
| 259  | voipb2  |
| 260  | dmzb2  |
| 261  | wifib3  |
|  262 | gfb3  |
| 263  | fob3  |
| 264  | voipb3  |
| 265  | dmzb3  |
| 266  | wifib4  |
|267   | fob4  |
| 268  | gfb4  |
| 269  | voipb4  |
| 270  | dmzb4  |


## VTP Domain : rc22deg3


## IPv4 network

####backbone network: 172.16.216.128/25

| Building  |  Nodes | IPv4 Networks  | Mask  |
|---|---|---|---|
| 1  |  520 |  172.16.216.0 | /22  |
| 2  | 219  |  172.16.220.0 | /24  |
|  3 |   188| 172.16.221.0  | /24  |
|  4 |  175 | 172.16.222.0  |  /24 |



#IPv4 address each router use in backbone

|  routers building | IPv4 address  |
|---|---|
|  1 | 172.16.216.129  |
| 2  | 172.16.216.130  |
|  3 |  172.16.216.131 |
| 4  |  172.16.216.132 |



