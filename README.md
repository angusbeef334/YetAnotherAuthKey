# YetAnotherAuthKey
A Raspberry Pi RP2354 based PCB that can be flashed with the [pico-fido](https://github.com/polhenarejos/pico-fido) firmware to act as a security key similar to Yubikey, because Yubikeys are expensive and I'm broke.

Made for Hack Club [Blueprint](https://blueprint.hackclub.com)

KiCad 9 format, all of the symbol/footprint libraries should be included in the repo. 

RP2350 and related components symbols/footprints were obtained from [Raspberry Pi](https://datasheets.raspberrypi.com/rp2350/Minimal-KiCAD.zip).

<img width="658" height="726" alt="image" src="https://github.com/user-attachments/assets/32270f84-5563-4fb9-9deb-4a9d82ac9bca" />

<img width="418" height="1065" alt="image" src="https://github.com/user-attachments/assets/9d2e6dc5-45d9-46fd-ab45-907ea9d07aee" />

<img width="1369" height="768" alt="image" src="https://github.com/user-attachments/assets/6065d641-f20e-433b-a860-c28898f01ba7" />

LCSC bom (most of these have MOQs)
| Id | Designator                                 | Footprint                                            | Quantity | Designation      | LCSC Part Number | Ext Price USD |
|----|--------------------------------------------|------------------------------------------------------|----------|------------------|------------------|---------------|
| 1  | C8,C12,C10,C11,C17,C15,C19,C18,C14,C16,C13 | C_0402_1005Metric                                    | 11       | 100n             | C1525            | 0.12          |
| 2  | C1,C2                                      | C_0603_1608Metric                                    | 2        | 10u              | C19702           | 0.29          |
| 3  | SW1                                        | SW_Push_SPST_NO_Alps_SKRK                            | 1        | SW_Push          | C115357          | 0.64          |
| 4  | C6,C9,C7,C5                                | C_0402_1005Metric                                    | 4        | 4.7u             | C368809          | 0.31          |
| 5  | U2                                         | SOT-23                                               | 1        | MCP1700x-330xxTT | C39051           | 1.98          |
| 6  | R3,R2                                      | R_0402_1005Metric                                    | 2        | 27               | C138021          | 0.07          |
| 7  | Y1                                         | Crystal_SMD_3225-4Pin_3.2x2.5mm                      | 1        | ABM8-272-T3      | C20625731        | 1.77          |
| 8  | J1                                         | USB_A_Molex_48037-2200_Horizontal                    | 1        | USB_A            | C2681564         | 0.65          |
| 9  | L1                                         | C_0402_1005Metric                                    | 1        | 3.3u             | C51412           | 0.9           |
| 10 | R4,R5                                      | R_0402_1005Metric                                    | 2        | 1k               | C106235          | 0.06          |
| 11 | R6                                         | R_0402_1005Metric                                    | 1        | 33               | C138002          | 0.07          |
| 12 | U1                                         | RP2350-QFN-60-1EP_7x7_P0.4mm_EP3.4x3.4mm_ThermalVias | 1        | RP2350_60QFN     | C41378174        | 2.49          |
| 13 | C3,C4                                      | C_0402_1005Metric                                    | 2        | 15p              | C86285           | 0.29          |

Total: 9.64 USD
