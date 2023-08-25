# DC5V for the Atari STF

> [WARNING] Please read carefully this note before using this project. It contains important facts.

Content

1. What is **DC5V for the Atari STF**, and when to use it ?
2. What should you know before using **DC5V for the Atari STF** ?
3. How to use **DC5V for the Atari STF** ?
4. Known issues
5. Miscellanous

## 1. What is **DC5V for the Atari STF**, and when to use it ?

**DC5V for the Atari STF** is an alternative pcb to replace the integrated power supply of the Atari STf, based on the premise that the original power plug will receive a DC 5V, 3A to 4A supply instead of being plugged to the main grid (110~240V, 50~60Hz, 1A).

**BOM v1**

|Designator|Description|URL (if appliable)|
|---|---|---|
|J1|**Würth Elektronik** 7.00mm Screwless 45° Entry, Serie 4122, 1×3 – #691412220003|[Mouser 710-691412220003](https://www.mouser.com/ProductDetail/710-691412220003) |
|F1|**Würth Elektronik** Shocksafe Fuse Holder – #696310001002|[Mouser 710-696310001002](https://www.mouser.com/ProductDetail/710-696310001002) |
|SW1|Latching Push Button, on-off Switch, DIP 6 pins (row pitch 6mm, pin pitch 2.5mm, 8×8mm body)|[Aliexpress 1005003333312190](https://www.aliexpress.com/item/1005003333312190.html) |
|J2 - contact|**TE connectivity** Connector Contact, Socket, Wire-to-Board / Wire-to-Wire, 26 – 20 AWG Wire Size, .12 – .5 mm² Wire Size, Tin, Strip, Wire & Cable, 2 A, Signal – #170262-1|[Mouser 571-1702621-CT ](https://www.mouser.com/ProductDetail/571-1702621-CT) |
|J2 - housing|**TE connectivity** Housing, Receptacle, Wire-to-Board, 6 Position, .098in/2.5 mm Centerline, Crimp, 1 Row, Natural, Mating Retention, Wire & Cable, Power & Signal – #171822-6|[Mouser 571-171822-6](https://www.mouser.com/ProductDetail/571-171822-6) |
|J3 - pin sockets|Round socket connector strip|[Exxos #0169](https://www.exxosforum.co.uk/atari/store2/#0169) |
|J3 - pins|Round pin connector strip|[Exxos #0132](https://www.exxosforum.co.uk/atari/store2/#0132) |
|J4|Right angled, pitch 2.54mm, 1×4 pins header|—|
|J5|pitch 2.54mm, 1×2 pins header, classic or JST style|—|


### Licence

**DC5V for the Atari STF** is published under the Creative Commons CC0 license. You can find a copy of the licence there : https://creativecommons.org/publicdomain/zero/1.0/legalcode

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**DC5V for the Atari STF** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

### Release notes


## 2. What should you know before using **DC5V for the Atari STF** ?

**DC5V for the Atari STF** is made using Kicad 6.

> Do not use **DC5V for the Atari STF** if this project is not suitable for your project.

## 3. How to use **DC5V for the Atari STF** ?

### From sources

To get the latest available work, one must clone the git repository, build and install the package.

	git clone --recurse-submodules https://github.com/sporniket/dc5v-for-atari-stf.git

Then, open the project with Kicad 6.

## 4. Known issues
See the [project issues](https://github.com/sporniket/dc5v-for-atari-stf/issues) page.

## 5. Miscellanous

### Report issues
Use the [project issues](https://github.com/sporniket/dc5v-for-atari-stf/issues) page.
