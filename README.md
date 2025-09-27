# ESP32-Programmer

![ESP32 Programmer](render.png)

This is a serial bridge for programming custom ESP32 boards, with auto-reset feature, so you shouldn't have to manually push buttons to enter boot mode. The board can also power simple ESP32 boards and has some standard circuit protections. 

**Features:**
- USB-C Connector
- ESD, overcurrent and reverse current protection
- CP2104 enabled USB-to-UART Bridge
- 3.3V ~ 600mA regulator
- Auto-reset circuit
- Boot and Reset buttons.
  
# Building
## PCB BOM

|Parts      |Value           |Package             |Qty|
|-----------|----------------|--------------------|---|
|C1, C2, C5 |10uF            |0603-CAP            |3  |
|C3         |1uF             |0603-CAP            |1  |
|C4         |10uF            |C0805               |1  |
|C6         |1uF             |C0805               |1  |
|D1, D2, D3 |BAT60A          |SOD-323             |3  |
|F1         |1.5A PTC FUSE   |PTC1206             |1  |
|J2         |USB-C-4105_REVA |GCT_USB4105_REVA    |1  |
|PWR        |RED LED         |0805_LED            |1  |
|Q1         |UMH3N           |SOT65P230X110-6N    |1  |
|R3, R4, R10|5.1k            |R0805               |3  |
|R5, R8, R9 |10k             |R0805               |3  |
|R6         |4.7k            |R0805               |1  |
|R7         |100k            |R0805               |1  |
|RX         |YELLOW LED      |0805_LED            |1  |
|S1, S2     |KMR621NG SWITCH |KMR621NG_LFS        |2  |
|TX         |ORANGE LED      |0805_LED            |1  |
|U1         |CP2104-F03-GM   |QFN50P400X400X80-25N|1  |
|U2         |USBLC6-2SC6     |SOT95P280X145-6N    |1  |
|U3         |AP2112M-3.3TRG1 |AP2112M-3.3TRG1_DIO |1  |
|X1         |BM07B-SRSS-TBB  |BM07B-SRSS-TB       |1  |

## Assembly partlist:

### FDM case:
- 4x M2 3mmx3mm threaded inserts
- 4x M2 5mm Hex Socket Cap Screw (or similar)

### Stacked acrylic case:
- 8x M2 3mmx3mm threaded inserts
- 8x M2 5mm Hex Socket Cap Screw (or similar)
