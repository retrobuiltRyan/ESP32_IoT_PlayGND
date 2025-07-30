# ESP32_IoT_PlayGND
Internet of Things + MQTT, motor drive, and sensor learning board

<img width="651" height="528" alt="IoT PlayGND pic" src="https://github.com/user-attachments/assets/1f1d1eb7-b0e2-413c-a86f-5fc83ce769eb" />

ESP-WROOM-32 ESP32: https://www.amazon.com/gp/product/B0D8Q8XFRK/


BoM
## Bill of Materials (BOM)

### Components

| Notes     | Reference                                       | Value             | Footprint                                                    | Qty | DigiKey P/N                                                |
|-----------|--------------------------------------------------|-------------------|---------------------------------------------------------------|-----|-------------------------------------------------------------|
|           | C3, C4, C7                                       | 0.1uF 50V         | Capacitor_SMD:C_1206_3216Metric                               | 3   | 1276-1068-1-ND                                              |
|           | C10, C11                                         | 0.22uF 50V CER    | Capacitor_SMD:C_1206_3216Metric                               | 2   | 445-2283-1-ND                                               |
|           | C12, C13, C14                                    | 22uF 50V          | Capacitor_SMD:CP_Elec_5x5.3                                   | 3   | 399-11438-1-ND                                              |
|           | D6, D7, D8, D9                                   | WS2812B RGB LED   | 5050                                                          | 4   | [AliExpress Link](https://www.aliexpress.us/item/3256802466699315.html) |
|           | D2                                               | Diode, chonky     | Diode_SMD:D_SMC_Handsoldering                                | 1   | S5AC-FDICT-ND                                               |
|           | D10                                              | LED RED           | LED_THT:LED_D5.0mm                                            | 1   | any 5mm LED                                                 |
|           | D5, D11, D9, D13                                 | LED Green         | LED GREEN DIFFUSED 1206 SMD                                   | 4   | 1080-1419-1-ND                                              |
| *optional*| D12                                              | SMF15A            | Diode_SMD:D_SMF                                               | 1   | SMF15A-E3-08CT-ND                                           |
|           | D14                                              | 1N4148W           | Diode_SMD:D_SOD-123                                           | 1   | 4878-1N4148WCT-ND                                           |
| *optional*| Q1                                               | MOSFET P-CH 30V 25A TO252 | Ryan_Custom_Modules:MOSFET_P-CH_30V_25A_TO252     | 1   | 785-1106-1-ND                                               |
|           | Q2, Q3                                           | MMBT2222A         | Package_TO_SOT_SMD:SOT-23                                     | 2   | MMBT2222ATPMSCT-ND                                          |
|           | R1, R2, R8, R22, R25, R26, R27, R28, R30, R34, R35, R36, R37, R38 | 10K              | Resistor_SMD:R_1206_3216Metric                               | 14  | 311-10.0KFRCT-ND                                            |
|           | R3, R4, R5, R6, R7, R9, R16, R23, R31            | 220               | Resistor_SMD:R_1206_3216Metric                                | 9   | 311-220FRCT-ND                                              |
|           | R17, R21                                         | 330               | Resistor_SMD:R_1206_3216Metric                                | 2   | 311-330FRCT-ND                                              |
|           | R18, R19, R20, R32                               | 1K                | Resistor_SMD:R_1206_3216Metric                                | 4   | 311-1.00KFRCT-ND                                            |
| *jumper*  | R29                                              | 0                 | Resistor_SMD:R_2512_6332Metric_Pad1.40x3.35mm_HandSolder      | 1   | YAG1232CT-ND                                                |
| *optional*| R33                                              | 100k              | Resistor_SMD:R_1206_3216Metric                                | 1   | 311-100KFRCT-ND                                             |
|           | U3                                               | PCA9685PW         | Package_SO:TSSOP-28_4.4x9.7mm_P0.65mm                         | 1   | 568-11925-1-ND                                              |
|           | U14                                              | MAX40200AUK       | Package_TO_SOT_SMD:SOT-23-5                                   | 1   | 175-MAX40203AUK+TCT-ND                                      |
|           | U15                                              | L7805             | Package_TO_SOT_SMD:TO-252-2                                   | 1   | 497-7255-1-ND                                               |


