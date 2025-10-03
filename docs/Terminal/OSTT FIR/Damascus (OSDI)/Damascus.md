---
  title: Damascus TMA (Damascus Approach)
---

--8<-- "includes/abbreviations.md"

## Positions

| Name | Callsign | Frequency | Login ID | Remarks |
| ---- | -------- | ---------	| -------- | ------- |
| **Damascus APP**	| **Damascus Approach** | **121.000**	| **OSDI_APP**	|Procedural|

## Airspace - Class B
**OSDI_APP** is responsible for the entire Baghdad TMA airspace from `A010` and `A030` to `FL150`.

!!! info   
    ILS and VOR in Damascus have been out of use since 2019.   
    RNP and Visual approaches only shall be assigned.       

![Damascus TMA](img/OSDI_AOR.png)

## Departure Procedures

| Runway | Direction | SID | Routing |
| ------ | --------- | --- | ------- |
| 23L | East  | ABBAS2 | **LT** intercept R083 DAM to ABBAS |
|     |       | SLF2 | **LT** intercept R083 **DAM** to SULAF | 
|     |       | TAN2 | **LT** intercept R083 **DAM** to **TAN** | 
|     | South | BUSRA1 | direct **DAM** - climb in holding - MNM **5000** intercept R170 **DAM** TO RDIMA - SWIDA - BUSRA |
|     | North | LEBOR1 | direct **DAM** - climb in holding - at MNM **5000** intercept R003 **DAM** - ADRAA - MALOULA - LEBOR |
|     | West  | N/A | N/A |

| Runway | Direction | SID | Routing |
| ------ | --------- | --- | ------- |
| 05L | East  | ABBAS22 | **RT** HDG 150° - intercept R083 **DAM** to ABBAS |
|     |       | SLF22 | **RT** HDG 150° - intercept R083 **DAM** to SULAF |
|     |       | TAN22 | **RT** HDG 150° - intercept R083 **DAM** to **TAN** |
|     | South | BUSRA2  | **RT** direct **DAM** - climb in holding - at MNM **5000** intercept R170 **DAM** to RDIMA - SWIDA - BUSRA |
|     | North | LEBOR2  | direct **DAL** - at MNM **5000** (but before **DAL**) **LT** direct ADRAA **RT** to MALOULA - LEBOR |
|     | West  | N/A | N/A

!!! warning     
    Even though the departure procedure instructs pilots to hold at **DAM**, the VOR is out of service and therefore a hold cannot be performed.   
    Pilots should have their FMC to route from **DAM** to the next waypoint thereafter. It is advised that the controller after departure gives a direct to the next waypoint along with    the climb clearance.

### Controller Actions

Aircraft will contact OSDI_APP after departure from TWR with an initial climb of 5000 feet. The controller (if conditions allow) shall climb the departure up to `FL150`. Directs are not permitted when the aircraft is more than **20NM** from the vicinity of the aerodrome as the radar becomes unreliable past those distances, which means that the controller must provide procedural services (see procedural tab on the left).


## Arrival Procedures

| Runway | Coming from | STAR | Routing |
| ------ | ----------- | ---- | ------- |
| 23/05 | South | BRAVO1C | BUSRA - SWIDA - RDIMA - DAM |
|     | North-East | KILO1C | KTN - BASEM - ABBAS - SOFIA |
|     | North | LIMA1C | LEBOR - MALLA - ADRAA - DAM | 
|     | East | SEIRA1C | SULAF - ABBAS - SOFIA | 
|     |      | TANGO1C | TAN - SULAF - ABBAS - SOFIA | 

!!! warning   
    Final segment of KILO and TANGO arrivals will be directed by ATC to either **DAL**, **DAM** or **ABD** depending on the current runway configuration.   
    FMS coding example:   
    - KILO 1C to **DAL** K 1CDAL   
    - TANGO 1C to **DAL** T 1CDAL   

### Controller Actions
Aircraft will be handed off from OSTT_CTR already given an arrival clearance, however a runway will not be assigned. The standard approach to assign is depending on the runway configuration and weather conditions. If: 
 - Visibility is at or greater than 5000 meters with runway 23R in use, then an RNAV approach shall be assigned with an appropriate transition.
 - Visibility is at or lower than 5000 meters with runway 23R in use, then a hold shall be offered over DAL until visibility improves as published (inbound radial 297, left turns, 1 minute legs).

05R however does not have an RNAV approach, instead, a visual approach must be given, which is selected as RNVX 05R in the pilots FMS. (reference Visual chart below).

![Damascus Visual 05L](img/OSDI_VIS.png)

!!! phraseology "O5R"  
    **OSDI_APP**: UAE913 expect visual runway 05R from SOFIA, descend and maintain 8000 feet QNH 1013.   

!!! phraseology "23L"   
    **OSDI_APP**: UAE913 expect RNAV runway 23L from SOFIA, DAL transition, descend and maintain 8000 feet QNH 1013.

!!! phraseology "DAL Hold"   
    **OSDI_APP**: UAE913 cleared direct DAL, enter hold over DAL as published.   

Aircraft must be cleared to 3600 feet before being given an approach clearance. However, 3600 feet may not be given until they are within **3NM** of the intercept point as the MSA is 5000 feet in the south and 9000 in the north.
