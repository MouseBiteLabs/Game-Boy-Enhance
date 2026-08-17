# AGBM-02

[**Reference the Wiki for more information on how to use this circuit board!**](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/How-to-Use-this-Wiki)

![image](https://github.com/user-attachments/assets/b00309fc-8c59-45a5-9b41-6c6c1231f48c)

## Board Characteristics

The zipped folder contains all the gerber files for this board. The following options must be chosen when ordering boards for yourself.

- Thickness: 1.0mm
- Layers: 4
- Surface Finish: ENIG (HASL is acceptable **ONLY IF** you are using tactile switches for the buttons)

You can use the zipped folder at any board fabricator you like. You may also buy the board from PCBWay using this link (disclosure: I receive 10% of the sale value to go towards future PCB orders of my own):

<a href="https://www.pcbway.com/project/shareproject/Game_Boy_Enhance_AGBM_02_06435d43.html"><img src="https://www.pcbway.com/project/img/images/frompcbway-1220.png" alt="PCB from PCBWay" /></a>

### Purchase from My Website

You can purchase this circuit board at my website, [https://mousebitelabs.store](https://mousebitelabs.store). Click the following image to be directed to the specific item listing:

<a href="https://mousebitelabs.store/products/game-boy-enhance-circuit-board"><img width="1070" height="182" alt="PCB from MouseBiteLabs" src="https://github.com/user-attachments/assets/14072b8c-4d47-434b-9c31-6d4ec74a28bc" /></a>

### Purchase from Etsy

I also offer the board on Etsy, if you would rather purchase through there - click the banner to be redirected.

<a href="https://mousebitelabs.etsy.com/listing/4520511265"><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/97127539/239718536-5c9aefe3-0628-4434-b8d8-55ff80ac3bbc.png" alt="PCB from Etsy" /></a> 

## Assembly and Testing Instructions

[View the wiki for more information!](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/AGBM-02-%28AA%29-Build-Test-Order)

## Battery Life Estimation

In short, when using eneloop pro NiMH batteries, you can expect anywhere from 5 hours to 15 hours - this is heavily dependent on the type of screen kit you select. Note that these times are estimated from the AGBM-01; the total playtime should be similar.

| Screen Kit     | Max Time | Min Time |
| -------------- | -------- | -------- |
| FP IPS Max     | 10h15m   | 6h       |
| FP ITA         | 15h30m   | 8h       |
| Hispeedido IPS | 11h      | 5h20m    |

[View this wiki page for more information.](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Power-Draw-and-Battery-Curves#agbm-01-agbm-02)

## Bill of Materials (BOM)

**[Here's a pre-made Digikey shopping cart.](https://www.digikey.com/short/0mjv40tv)**

In this shopping cart, I provided *some* extra parts just in case you lose/damage one of the lesser expensive parts. Also, please note that the RAM listed is *only* if your donor console's RAM is suspected to be damaged in some way.

| Reference | Value/Part Number   | Package       | Description                       | Salvagable from GBA? | Source                                                                           |
| --------- | ------------------- | ------------- | --------------------------------- | -------------------- | -------------------------------------------------------------------------------- |
| BT1       |                     |               | AA Battery Terminals              | Yes                  | [https://tinyurl.com/yrnsncnj](https://tinyurl.com/yrnsncnj)                     |
| C1        | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/nqdjrz7d                                           |
| C2        | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C3        | 27p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3dr3j004                                           |
| C4        | 33p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/q8jbrfqj                                           |
| C5        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C6        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C7        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C8        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C9        | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C10       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C11       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C12       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C13       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C14       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C15       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C16       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C17       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C18       | 100p                | 0603          | Capacitor (MLCC)                  |                      | [https://www.digikey.com/short/h34j0h9q](https://www.digikey.com/short/h34j0h9q) |
| C19       | 100p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/h34j0h9q                                           |
| C20       | 100p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/h34j0h9q                                           |
| C21       | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/nqdjrz7d                                           |
| C22       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C23       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C24       | 1000p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/377h8558                                           |
| C25       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C26       | 680p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/jm5qjr7w                                           |
| C27       | 330p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/5ptw22qq                                           |
| C28       | 3300p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3p3jj3wt                                           |
| C29       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C30       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C31       | 680p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/jm5qjr7w                                           |
| C32       | 1000p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/377h8558                                           |
| C33       | 330p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/5ptw22qq                                           |
| C34       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C35       | 3300p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3p3jj3wt                                           |
| C36       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C37       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C38       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C39       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C42       | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/nqdjrz7d                                           |
| C43       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C44       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C45       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C46       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C47       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C48       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C49       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C50       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C51       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C52       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C53       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C54       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C55       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C56       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C57       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C58       | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/nqdjrz7d                                           |
| C59       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C60       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C61       | 3300p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3p3jj3wt                                           |
| C62       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C63       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C64       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C68       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/90j37vwp                                           |
| C69       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C72       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C73       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C74       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C75       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C76       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C77       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C78       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C79       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C80       | 3300p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3p3jj3wt                                           |
| CP1       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/w5p7f0nd                                           |
| CP2       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/w5p7f0nd                                           |
| CP3       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/w5p7f0nd                                           |
| D1        | 1SS355VMTE-17       | SOD-323       | Diode                             |                      | https://www.digikey.com/short/b42wmndz                                           |
| D2        | 1SS355VMTE-17       | SOD-323       | Diode                             |                      | https://www.digikey.com/short/b42wmndz                                           |
| DL1       | 150060VS75000       | 0603          | LED (Green)                       |                      | https://www.digikey.com/short/ttf7q4w7                                           |
| DL2       | 150060RS75000       | 0603          | LED (Red)                         |                      | https://www.digikey.com/short/83vdcfv3                                           |
| EM1       | ACM2520-801-3P-T002 | 6 PC Pad      | Common Mode Choke                 |                      | https://www.digikey.com/short/771087dh                                           |
| EM2       | ACM2520-801-3P-T002 | 6 PC Pad      | Common Mode Choke                 |                      | https://www.digikey.com/short/771087dh                                           |
| EM3       | MH1608-601Y         | 0603          | Ferrite Bead                      |                      | https://www.digikey.com/short/c329ffdd                                           |
| EM7       | MH1608-601Y         | 0603          | Ferrite Bead                      |                      | https://www.digikey.com/short/c329ffdd                                           |
| F1        | F0805B2R00FSTR      | 0805          | Fuse, 2A                          |                      | https://www.digikey.com/short/98cdp3tv                                           |
| L1        | 0.47uH              | 0806          | Inductor (CIGT201610EHR47MNE)     |                      | https://www.digikey.com/short/54dnztr9                                           |
| L2        | 0.47uH              | 0806          | Inductor (CIGT201610EHR47MNE)     |                      | https://www.digikey.com/short/54dnztr9                                           |
| P1        | CART SLOT           |               | GBA Cartridge Slot                | Yes                  | https://tinyurl.com/4uwbr8er                                                     |
| P2        | 62684-402100ALF     | 40-pin, 0.5mm | FFC Connector, Top Contact        |                      | https://www.digikey.com/short/13cnr9vq                                           |
| P3        | SJ-3524-SMT         |               | 3.5mm TRS Audio Jack              |                      | https://www.digikey.com/short/r4b2bq43                                           |
| P4        | AGB-LINK            |               | GBA Link Port                     | Yes                  | https://tinyurl.com/253x94mn                                                     |
| PTC1      | 0805L075SLYR        | 0805          | PTC, Resettable Fuse              |                      | https://www.digikey.com/short/43nq0332                                           |
| Q1        | 2N3904              | SOT-23        | NPN BJT                           |                      | https://www.digikey.com/short/5j230h4f                                           |
| Q2        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q3        | 2N3906              | SOT-23        | PNP BJT                           |                      | https://www.digikey.com/short/hhdhqzd8                                           |
| Q5        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q6        | 2N7002              | SOT-23        | N-Channel MOSFET                  |                      | https://www.digikey.com/short/vbm0z4md                                           |
| Q7        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q8        | 2N7002              | SOT-23        | N-Channel MOSFET                  |                      | https://www.digikey.com/short/vbm0z4md                                           |
| Q9        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q10       | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| R1        | 1.5M                | 0603          | Resistor                          |                      | https://www.digikey.com/short/pd49zr2b                                           |
| R2        | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R3        | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R4        | 33k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/wn8fhvz4                                           |
| R5        | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R6        | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R7        | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R8        | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R9        | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R10       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R11       | 1k                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/nwddb5fm                                           |
| R12       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R13       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R14       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R15       | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R16       | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R17       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R18       | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R19       | 1k                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/nwddb5fm                                           |
| R20       | 1k                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/nwddb5fm                                           |
| R24       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R25       | 3.3k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/b8bf03mm                                           |
| R26       | 33k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/wn8fhvz4                                           |
| R29       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/qv7nrc97                                           |
| R30       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R31       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R34       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R35       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R36       | 270                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/85p4bp5h                                           |
| R37       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R38       | 47                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/qb81zfh9                                           |
| R39       | 47                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/qb81zfh9                                           |
| R40       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R41       | 2.2k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/89v4f1wn                                           |
| R42       | 7.5k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/vn4221jt                                           |
| R43       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R44       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R45       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R46       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R47       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R48       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/qv7nrc97                                           |
| R49       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R50       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R51       | 7.5k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/vn4221jt                                           |
| R52       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R53       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R54       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/qv7nrc97                                           |
| R56       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R57       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R58       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R59       | 820k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/dnr2jwf7                                           |
| R60       | 91k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/13v3wz29                                           |
| R63       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R64       | 200k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/3391593q                                           |
| R65       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R66       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R67       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R68       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R70       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R71       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R72       | 510k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/v0jfp0r5                                           |
| R73       | 91k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/13v3wz29                                           |
| RA1       | 330                 | 1206          | Resistor Array                    |                      | https://www.digikey.com/short/m8cr1b0n                                           |
| SP1       | Speaker             |               | 8 Ohm Speaker                     | Yes                  | SEE NOTE!                                                                        |
| SW1       | CSS-1310B           |               | Power Switch                      |                      | https://www.digikey.com/short/0ww37f47                                           |
| SW2       | 1825027-5           |               | SPST-NO                           | Yes                  | https://tinyurl.com/36tap2xj                                                     |
| SW3       | 1825027-5           |               | SPST-NO                           | Yes                  | https://tinyurl.com/36tap2xj                                                     |
| SW4       | SKRRABE010          |               | Tactile Switch x2 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| SW5       | SKRRABE010          |               | Tactile Switch x2 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| SW6       | SKRRABE010          |               | Tactile Switch x4 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| U1        | AGB-CPU             | QFP-128       | GBA CPU                           | Yes                  | Salvage                                                                          |
| U2        | AGB-SRAM            | TSOP-48       | GBA SRAM                          | Yes                  | https://www.digikey.com/short/dwnw5t0h                                           |
| U3        | TPS3840DL20         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/pq9b8pqv                                           |
| U4        | NCV8164ASN250T1G    | SOT-23-5      | 2.5V Linear Regulator             |                      | https://www.digikey.com/short/vzm4m93z                                           |
| U5        | TPS63802            | VSON-10       | Buck-Boost Converter              |                      | https://www.digikey.com/short/3rwd04md                                           |
| U6        | LM4853              | VSSOP-10      | Class AB Audio Amplifier          |                      | https://www.digikey.com/short/r3rqdzt8                                           |
| U7        | TLV9364             | TSSOP-14      | Quad Op-amp                       |                      | https://www.digikey.com/short/jhr04t1t                                           |
| U8        | NCV8164ASN250T1G    | SOT-23-5      | 2.5V Linear Regulator             |                      | https://www.digikey.com/short/vzm4m93z                                           |
| U9        | SN74LVC2G34DBVR     | SOT-23-6      | Buffer                            |                      | https://www.digikey.com/short/tzhnmjv0                                           |
| U10       | TPS3840DL20         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/pq9b8pqv                                           |
| U11       | TPS22917DBV         | SOT-23-6      | Load Switch                       |                      | https://www.digikey.com/short/b880z8t8                                           |
| U12       | TPS22917DBV         | SOT-23-6      | Load Switch                       |                      | https://www.digikey.com/short/b880z8t8                                           |
| U13       | TPS63802            | VSON-10       | Buck-Boost Converter              |                      | https://www.digikey.com/short/3rwd04md                                           |
| U14       | MIC1557             | SOT-23-5      | 555 Timer                         |                      | https://www.digikey.com/short/58m495mr                                           |
| U15       | SN74LVC1G332        | SOT-23-6      | 3-Input OR Gate                   |                      | https://www.digikey.com/short/734hmb3p                                           |
| U16       | SN74HC02PWR         | TSSOP-14      | Quad 2-Input NOR Gate             |                      | https://www.digikey.com/short/t1r20n2n                                           |
| U17       | TPS3840DL20         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/pq9b8pqv                                           |
| U18       | TPS22917DBV         | SOT-23-6      | Load Switch                       |                      | https://www.digikey.com/short/b880z8t8                                           |
| VR1       | 3313J-2-503E        |               | Trim Pot, 50k                     | Yes                  | [https://www.digikey.com/short/p8zptq5h](https://www.digikey.com/short/p8zptq5h) |
| VR2       | RK10J12R0A0B        |               | Volume Thumbwheel, 10k, Dual      |                      | https://www.digikey.com/short/zh4rmq4h                                           |
| X1        | 4.194304MHz         | HC-49         | Crystal Oscillator                | Yes                  | https://www.digikey.com/short/5t5j99c2                                           |
| Z57       | 100p // 0 ohm       | 0603          | Capacitor (MLCC) // Jumper        |                      | Capacitor: https://www.digikey.com/short/h34j0h9q                                |
| Z58       | 100p // 0 ohm       | 0603          | Capacitor (MLCC) // Jumper        |                      | Jumper: https://www.digikey.com/short/9q3qp9bv                                   |
| Z70       | 47p // 100k         | 0603          | Capacitor (MLCC) // Resistor      |                      | Capacitor: https://www.digikey.com/short/53734bw9                                |
| Z71       | 47p // 100k         | 0603          | Capacitor (MLCC) // Resistor      |                      | Resistor: https://www.digikey.com/short/rpz9t4md                                 |

### Speaker Options

Usually people order speakers from Game Boy aftermarket parts sellers, [like this](https://tinyurl.com/yxxmec4w). But, if you would rather get a speaker from Digikey, there is one that fits perfectly in the system: [CMS-2207-18SP](https://www.digikey.com/short/1q4nr8tm).

## Revision History

### Early July '26

- Added through-hole footprint for the crystal oscillator

### Late June '26

- Release version

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. You are able to copy and redistribute the material in any medium or format, as well as remix, transform, or build upon the material for any purpose (even commercial) - but you **must** give appropriate credit, provide a link to the license, and indicate if any changes were made.

©MouseBiteLabs 2026
