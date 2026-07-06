# AGBM-11

[**Reference the Wiki for more information on how to use this circuit board!**](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/How-to-Use-this-Wiki)

<img width="4080" height="3072" alt="image" src="https://github.com/user-attachments/assets/cbc3d955-231f-4109-95c1-8ccbb3809a26" />

<img width="4080" height="3072" alt="image" src="https://github.com/user-attachments/assets/de2dd395-6a55-42f8-8aa2-9a2cecfa1171" />

## Mandatory Reading About Battery Safety

![image](https://github.com/MouseBiteLabs/Pocket-Protector-Power-Board/assets/97127539/e5de26d0-6b67-4bbc-820b-3a5d9aa0e80e)

"Bucket Mouse, all my devices have lithium ion batteries in them, and they're not dangerous. Why are you fear mongering?"

I am but one hobbyist, making things in my room. The batteries and battery management systems you use in devices every day are created by engineering teams and produced by corporations who do rigorous testing on products they sell (or, at least, they are supposed to). 

Therefore, for projects you assemble yourself, it is 100% up to *you* to safely manage these batteries, and know what you are doing, and know what to look out for with the batteries you purchase. This circuit board works for me, but as I am only one person, I have blind spots and I may have missed something (please tell me if I have). Also, I am confident in my soldering abilities - I am inherently *not* confident in yours. So, please, understand these risks and proceed at your own peril.

Read this article before continuing down this path: https://batteryuniversity.com/article/lithium-ion-safety-concerns

Also, I **highly recommend against using unbranded/no-name batteries, or batteries that do not come with a datasheet**. I work with batteries as part of my full-time job, and while I am not a battery expert myself, a few of my co-workers are. It is highly suspected that no-name batteries, especially those from AliExpress, are actually quality control *rejects* from other companies. So there's a high chance you're getting a battery that has failed quality controls when you get them from random sellers, or even reputable ones if they don't provide a datasheet. Stick only to **name-brand batteries** as they are much likelier to be safe.

Or... just make an [AA version](https://github.com/MouseBiteLabs/Game-Boy-Enhance/tree/main/AGBM-01%20(AA%20Batteries)) instead. They will get you longer battery life without the chance for exploding batteries. And also won't require annoying shell cuts.

![image](https://github.com/MouseBiteLabs/Pocket-Protector-Power-Board/assets/97127539/e5de26d0-6b67-4bbc-820b-3a5d9aa0e80e)

## Board Characteristics and Order Information

The zipped folder contains all the gerber files for this board. The following options must be chosen when ordering boards for yourself.

- Thickness: 1.0mm
- Layers: 4
- Surface Finish: ENIG (HASL is acceptable **ONLY IF** you are using tactile switches for the buttons)

**I sell this blank circuit board on Etsy, so you don't have to buy a bunch of multiples if you don't want to.** (Click the banner!)

<a href="https://mousebitelabs.etsy.com/listing/4520511265"><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/97127539/239718536-5c9aefe3-0628-4434-b8d8-55ff80ac3bbc.png" alt="PCB from Etsy" /></a> 

You can use the zipped folder at any board fabricator you like. You may also buy the board from PCBWay using this link (disclosure: I receive 10% of the sale value to go towards future PCB orders of my own):

<a href="https://www.pcbway.com/project/shareproject/Game_Boy_Enhance_AGBM_11_707bfaf5.html"><img src="https://www.pcbway.com/project/img/images/frompcbway-1220.png" alt="PCB from PCBWay" /></a>

## Shell Cutting Requirements

This board requires heavy modification of the GBA shell in order to fit the USB-C charge port and the lithium-ion battery. [Please view the shell cut guide before beginning the project.](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Shell-Cuts-%28for-LiPo%29)

## Assembly and Testing Instructions

[View the wiki for more information!](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/AGBM-11-%28LiPo%29-Build-Test-Order)

## Battery Life Estimation

In short, when using the linked Jauch lithium-ion battery, you can expect anywhere from 5 hours to 13 and a half hours - this is heavily dependent on the type of screen kit you select and the brightness.

| Screen Kit     | Max Time | Min Time |
| -------------- | -------- | -------- |
| FP IPS Max     | 10h      | 5h       |
| FP ITA         | 13h30m   | 7h       |
| Hispeedido IPS | 10h      | 5h       |

[View this wiki page for more information.](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/Power-Draw-and-Battery-Curves#agbm-11)

## Bill of Materials (BOM)

**[Here's a pre-made Digikey shopping cart.](https://www.digikey.com/short/wj532wvh)** Be prepared to have to purchase some parts from other distributors, like Mouser. I tried to pick parts that were plentiful but that was not possible in all situations.

| Reference | Value/Part Number   | Package       | Description                       | Salvagable from GBA? | Source                                                                           |
| --------- | ------------------- | ------------- | --------------------------------- | -------------------- | -------------------------------------------------------------------------------- |
| C1        | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/z1rp0q17                                           |
| C2        | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C3        | 27p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3dr3j004                                           |
| C4        | 33p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/q8jbrfqj                                           |
| C5        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C6        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C7        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C8        | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C9        | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C10       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C11       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C12       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C13       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C14       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C15       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C16       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C17       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C18       | 100p                | 0603          | Capacitor (MLCC)                  |                      | [https://www.digikey.com/short/h34j0h9q](https://www.digikey.com/short/h34j0h9q) |
| C19       | 100p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/h34j0h9q                                           |
| C20       | 100p                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/h34j0h9q                                           |
| C21       | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/z1rp0q17                                           |
| C22       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C23       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
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
| C37       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C38       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C39       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C40       | 15p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/q58vhz49                                           |
| C41       | 15p                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/q58vhz49                                           |
| C42       | 22u                 | 0805          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/z1rp0q17                                           |
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
| C59       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C60       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C61       | 3300p               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/3p3jj3wt                                           |
| C62       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C63       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C64       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C66       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C68       | 10u                 | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/qd4q4f1m                                           |
| C69       | 1u                  | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/2ppmm3vt                                           |
| C72       | 0.1u                | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/m958w3z3                                           |
| C74       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C75       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C76       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C77       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| C78       | 0.01u               | 0603          | Capacitor (MLCC)                  |                      | https://www.digikey.com/short/j50jww8m                                           |
| CP1       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/332b01qh                                           |
| CP2       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/332b01qh                                           |
| CP3       | 100u                | 1210          | Capacitor (Tantalum Electrolytic) |                      | https://www.digikey.com/short/332b01qh                                           |
| D1        | SMF5.0A-T13         | SOD-123       | TVS Diode                         |                      | [https://www.digikey.com/short/rbdmt4p7](https://www.digikey.com/short/rbdmt4p7) |
| D2        | 1SS355VMTE-17       | SOD-323       | Diode                             |                      | https://www.digikey.com/short/b42wmndz                                           |
| DL1       | 150060VS75000       | 0603          | LED (Green)                       |                      | https://www.digikey.com/short/ttf7q4w7                                           |
| DL2       | 150060RS75000       | 0603          | LED (Red)                         |                      | https://www.digikey.com/short/83vdcfv3                                           |
| DL3       | 150060AS75000       | 0603          | LED (Amber)                       |                      | [https://www.digikey.com/short/p7j0tphr](https://www.digikey.com/short/p7j0tphr) |
| EM1       | ACM2520-801-3P-T002 | 6 PC Pad      | Common Mode Choke                 |                      | https://www.digikey.com/short/771087dh                                           |
| EM2       | ACM2520-801-3P-T002 | 6 PC Pad      | Common Mode Choke                 |                      | https://www.digikey.com/short/771087dh                                           |
| EM3       | MH1608-601Y         | 0603          | Ferrite Bead                      |                      | https://www.digikey.com/short/c329ffdd                                           |
| EM7       | MH1608-601Y         | 0603          | Ferrite Bead                      |                      | https://www.digikey.com/short/c329ffdd                                           |
| F1        | F0805B2R00FSTR      | 0805          | Fuse, 2A                          |                      | https://www.digikey.com/short/98cdp3tv                                           |
| F2        | F0805B2R00FSTR      | 0805          | Fuse, 2A                          |                      | https://www.digikey.com/short/98cdp3tv                                           |
| J1        | JST-SH              | 1mm Spacing   | JST SH Connector                  |                      | [https://www.digikey.com/short/j8rp8493](https://www.digikey.com/short/j8rp8493) |
| L1        | 4.7uH               | 1212          | Inductor (LSXND3030QKT4R7MNG)     |                      | https://www.digikey.com/short/m9hwf8cw                                           |
| L2        | 4.7uH               | 1212          | Inductor (LSXND3030QKT4R7MNG)     |                      | https://www.digikey.com/short/m9hwf8cw                                           |
| P1        | CART SLOT           |               | GBA Cartridge Slot                | Yes                  | https://tinyurl.com/4uwbr8er                                                     |
| P2        | FFC CONNECTOR       | 40-pin, 0.5mm | FFC Connector, Top Contact        |                      | https://www.digikey.com/short/13cnr9vq                                           |
| P3        | SJ-3524-SMT         |               | 3.5mm TRS Audio Jack              |                      | https://www.digikey.com/short/r4b2bq43                                           |
| P4        | AGB-LINK            |               | GBA Link Port                     | Yes                  | https://tinyurl.com/253x94mn                                                     |
| P5        | 2171750001          | USB-C         | USB-C 6-pin receptacle            |                      | [https://www.digikey.com/short/jmfqt488](https://www.digikey.com/short/jmfqt488) |
| PTC1      | 0805L075SLYR        | 0805          | PTC, Resettable Fuse              |                      | https://www.digikey.com/short/43nq0332                                           |
| Q1        | 2N3904              | SOT-23        | NPN BJT                           |                      | https://www.digikey.com/short/5j230h4f                                           |
| Q2        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q3        | 2N3906              | SOT-23        | PNP BJT                           |                      | https://www.digikey.com/short/hhdhqzd8                                           |
| Q4*       | EXB-34VR000V        | 2x 0603       | Resistor Array                    |                      | https://www.digikey.com/short/8m2c88mh                                           |
| Q5        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q6        | 2N7002              | SOT-23        | N-Channel MOSFET                  |                      | https://www.digikey.com/short/vbm0z4md                                           |
| Q7        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q8        | 2N7002              | SOT-23        | N-Channel MOSFET                  |                      | https://www.digikey.com/short/vbm0z4md                                           |
| Q9        | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| Q10       | NDC7002N            | SOT-23-6      | Dual N-Channel MOSFETs            |                      | https://www.digikey.com/short/28n9329f                                           |
| R1        | 1.5M                | 0603          | Resistor                          |                      | https://www.digikey.com/short/pd49zr2b                                           |
| R2        | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R3        | 2.49k               | 0603          | Resistor                          |                      | [https://www.digikey.com/short/crrrfpbn](https://www.digikey.com/short/crrrfpbn) |
| R4        | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
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
| R21       | 1.78M               | 0603          | Resistor                          |                      | https://www.digikey.com/short/mt3hp154                                           |
| R22       | 560k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/3t5fhht8                                           |
| R23       | 1.78M               | 0603          | Resistor                          |                      | https://www.digikey.com/short/mt3hp154                                           |
| R24       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R25       | 3.3k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/w0t24jpv                                           |
| R26       | 33k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t0dpzzp1                                           |
| R27       | 3.3k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/w0t24jpv                                           |
| R28       | 2.49k               | 0603          | Resistor                          |                      | [https://www.digikey.com/short/crrrfpbn](https://www.digikey.com/short/crrrfpbn) |
| R29       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/1rfwtcff                                           |
| R30       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R31       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R32       | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R33       | 10k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/t130htj0                                           |
| R34       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R35       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R36       | 270                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/85p4bp5h                                           |
| R37       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R38       | 47                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/2trwn31h                                           |
| R39       | 47                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/2trwn31h                                           |
| R40       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R41       | 2.2k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/89v4f1wn                                           |
| R42       | 7.5k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/vn4221jt                                           |
| R43       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R44       | 15                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/d1537pn3                                           |
| R45       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R46       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R47       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R48       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/1rfwtcff                                           |
| R49       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R50       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R51       | 7.5k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/vn4221jt                                           |
| R52       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R53       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R54       | 18k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/1rfwtcff                                           |
| R55       | 1M                  | 0603          | Resistor                          |                      | https://www.digikey.com/short/pwjt9n2j                                           |
| R56       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R57       | 20k                 | 0603          | Resistor                          |                      | https://www.digikey.com/short/38d0p2b4                                           |
| R58       | 470                 | 0603          | Resistor                          |                      | [https://www.digikey.com/short/qw9vn9hr](https://www.digikey.com/short/qw9vn9hr) |
| R60*      | 0                   | 0603          | Resistor                          |                      | https://www.digikey.com/short/9q3qp9bv                                           |
| R61       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R62       | 5.1k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/qqj3r2v5                                           |
| R63       | 15k                 | 0603          | Resistor                          |                      | [https://www.digikey.com/short/b4mcvwnd](https://www.digikey.com/short/b4mcvwnd) |
| R64       | 200k                | 0603          | Resistor                          |                      | [https://www.digikey.com/short/75914mq4](https://www.digikey.com/short/75914mq4) |
| R65       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R66       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R67       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| R68       | 100k                | 0603          | Resistor                          |                      | https://www.digikey.com/short/rpz9t4md                                           |
| RA1       | 330                 | 1206          | Resistor Array                    |                      | https://www.digikey.com/short/m8cr1b0n                                           |
| SP1       | Speaker             |               | 8 Ohm Speaker                     | Yes                  | https://tinyurl.com/yxxmec4w                                                     |
| SW1       | CSS-1310B           |               | Power Switch                      |                      | https://www.digikey.com/short/0ww37f47                                           |
| SW2       | 1825027-5           |               | SPST-NO                           | Yes                  | https://tinyurl.com/36tap2xj                                                     |
| SW3       | 1825027-5           |               | SPST-NO                           | Yes                  | https://tinyurl.com/36tap2xj                                                     |
| SW4       | SKRRABE010          |               | Tactile Switch x2 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| SW5       | SKRRABE010          |               | Tactile Switch x2 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| SW6       | SKRRABE010          |               | Tactile Switch x4 (Optional)      |                      | https://www.digikey.com/short/2cqndb3b                                           |
| U1        | AGB-CPU             | QFP-128       | GBA CPU                           | Yes                  | Salvage                                                                          |
| U2        | AGB-SRAM            | TSOP-48       | GBA SRAM                          | Yes                  | Salvage                                                                          |
| U3        | TPS3840DL31         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/97pvp234                                           |
| U4        | NCV8164ASN250T1G    | SOT-23-5      | 2.5V Linear Regulator             |                      | https://www.digikey.com/short/vzm4m93z                                           |
| U5        | LTC3527             | QFN-16        | Dual Boost Converter              |                      | SEE NOTE!                                                                        |
| U6        | LM4853              | VSSOP-10      | Class AB Audio Amplifier          |                      | https://www.digikey.com/short/r3rqdzt8                                           |
| U7        | TLV9364             | TSSOP-14      | Quad Op-amp                       |                      | https://www.digikey.com/short/jhr04t1t                                           |
| U8        | NCV8164ASN250T1G    | SOT-23-5      | 2.5V Linear Regulator             |                      | https://www.digikey.com/short/vzm4m93z                                           |
| U9        | SN74LVC2G34DBVR     | SOT-23-6      | Buffer                            |                      | https://www.digikey.com/short/tzhnmjv0                                           |
| U10       | TPS3840DL31         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/97pvp234                                           |
| U11       | TPS22917DBV         | SOT-23-6      | Load Switch                       |                      | https://www.digikey.com/short/w4f9v7ht                                           |
| U12       | TPS22917DBV         | SOT-23-6      | Load Switch                       |                      | https://www.digikey.com/short/w4f9v7ht                                           |
| U14       | MIC1553             | SOT-23-5      | 555 Timer                         |                      | https://www.digikey.com/short/nrrw2pnh                                           |
| U15       | SN74LVC1G332        | SOT-23-6      | 3-Input OR Gate                   |                      | https://www.digikey.com/short/734hmb3p                                           |
| U16       | SN74HC02PWR         | TSSOP-14      | Quad 2-Input NOR Gate             |                      | https://www.digikey.com/short/t1r20n2n                                           |
| U17       | TPS3840DL31         | SOT-23-5      | Voltage Supervisor                |                      | https://www.digikey.com/short/97pvp234                                           |
| U19       | MCP73871-2CAI/ML    | QFN-20        | Battery Charge IC                 |                      | [https://www.digikey.com/short/2fq0m95z](https://www.digikey.com/short/2fq0m95z) |
| VR1       | 3313J-2-503E        |               | Trim Pot, 50k                     | Yes                  | [https://www.digikey.com/short/p8zptq5h](https://www.digikey.com/short/p8zptq5h) |
| VR2       | RK10J12R0A0B        |               | Volume Thumbwheel, 10k, Dual      |                      | https://www.digikey.com/short/zh4rmq4h                                           |
| X1        | 4.194304MHz         | HC-49         | Crystal Oscillator                | Yes (SEE NOTE)       | https://www.digikey.com/short/5t5j99c2                                           |
| Z57       | 100p // 0 ohm       | 0603          | Capacitor (MLCC) // Jumper        |                      | Capacitor: https://www.digikey.com/short/h34j0h9q                                |
| Z58       | 100p // 0 ohm       | 0603          | Capacitor (MLCC) // Jumper        |                      | Resistor: https://www.digikey.com/short/9q3qp9bv                                 |
| Z70       | 27p // 100k         | 0603          | Capacitor (MLCC) // Resistor      |                      | Capacitor: https://www.digikey.com/short/3dr3j004                                |
| Z71       | 27p // 100k         | 0603          | Capacitor (MLCC) // Resistor      |                      | Resistor: https://www.digikey.com/short/rpz9t4md                                 |

### Note about Q4 and R60

These parts are only found on AGBM-11 boards that were produced in mid-May of '26 (that have the following date code). You can ignore them if you have any other version.

<img width="424" height="249" alt="image" src="https://github.com/user-attachments/assets/506f5b07-3798-4394-8dcb-26e2c6b79324" />

### Note about LTC3527

This part has been going in and out of stock at various places for the past few months. It may be annoying to track down. The good news is, you can also use the LTC3527-1. Here are a few links to try out to find stock:

- [Digikey](https://www.digikey.com/en/products/filter/voltage-regulators-dc-dc-switching-regulators/739?s=N4IgTCBcDaIDYBcDGBmArGA7CAugXyA)

- [Mouser](https://www.mouser.com/c/semiconductors/integrated-circuits-ics/power-management-ics/voltage-regulators-voltage-controllers/switching-voltage-regulators/?q=ltc3527)

- [Octopart](https://octopart.com/search?autosugg_idx=test&currency=USD&specs=0&full_query=ltc3527+&q=ltc3527&nq=ltc3527&s=1&inferred_category_id=4305&inference=1) lists a lot of different distributors and their stock levels

As a last resort, AliExpress seems to have a decent bit of them. (Order at your own risk!)

### Crystal Oscillator

You might have an easier time with fitment if you use the donor crystal oscillator instead of the new part.

## Lithium-ion Battery Supplies

**DANGER:** Any lithium-ion battery you select for this mod **MUST** have overcharge/overdischarge protection as part of the pouch cell. **THE AGBM DOES NOT PROVIDE THESE PROTECTIONS**. The cell I link below has the proper safety circuitry.

Use these parts and follow the instructions on the wiki page [LiPo Wire Preparation](https://github.com/MouseBiteLabs/Game-Boy-Enhance/wiki/LiPo-Wire-Preparation).

Battery: [LP103048JU+PCM+2 WIRES 70MM](https://www.digikey.com/short/f205f9n9)

Pre-crimped wire: [ASSHSSH28K152](https://www.digikey.com/short/rwcw75r4)

Connector: [SHR-02V-S-B](https://www.digikey.com/short/0rzqt7nc)

Heatshrink: [V2-1.5-0-SP-SM](https://www.digikey.com/short/p5q77jq0)

## Revision History

### Late June '26
- Removed duplicate battery management components that was interfering with pouch cell protection circuitry

### Early June '26
- Change BATT to VAUD on silkscreen

### Middle May '26
- Initial Release

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. You are able to copy and redistribute the material in any medium or format, as well as remix, transform, or build upon the material for any purpose (even commercial) - but you **must** give appropriate credit, provide a link to the license, and indicate if any changes were made.

©MouseBiteLabs 2026
