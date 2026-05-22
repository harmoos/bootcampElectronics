# Bootcamp Electronics PCB Design


## Bill of Materials (BOM)

| Qty | Reference | Component | Package / Footprint |
| :--- | :--- | :--- | :--- |
| 1 | U1 | Microcontroller ATmega328P-A | TQFP-32 |
| 1 | Y1 | Crystal Oscillator 16MHz |  |
| 2 | C1, C2 | Capacitors 12pF | SMD 0603 |
| 1 | C3, C4, C7 | Capacitor 100nF | SMD 0603 |
| 1 | C6 | Capacitor 1uF | SMD 0603 |
| 1 | R1 | Resistor 330 | SMD 0603 |
| 2 | R2, R3 | Resistor 10K | SMD 0603 |
| 1 | D1 | Indicator LED Green | SMD 0603 |
| 1 | D2 | Indicator LED Red | SMD 0603 |
| 1 | SW1 | Switch Push | SMD |
| 2 | J1, J2 | Connector 1x12 | Through-hole |
| 1 | J3 | Connector 1x6 | Through-hole |

---

## Connector J1

| Pin | Name | Description |
| :---: | :--- | :--- |
| **1** | D9 | Digital Input/Output Pin 9 |
| **2** | D8 | Digital Input/Output Pin 8 |
| **3** | D7 | Digital Input/Output Pin 7 |
| **4** | D6 | Digital Input/Output Pin 6 |
| **5** | D5 | Digital Input/Output Pin 5 |
| **6** | D4 | Digital Input/Output Pin 4 |
| **7** | D3 | Digital Input/Output Pin 3 |
| **8** | D2 | Digital Input/Output Pin 2 |
| **9** | **GND** |  Circuit Ground |
| **10** | RST | System Reset |
| **11** | RXI | UART Serial Receive Input |
| **12** | TXO | UART Serial Transmit Output |

## Connector J2

| Pin | Name | Description |
| :---: | :--- | :--- |
| **1** | **RAW** | Raw Power Input |
| **2** | **GND** | Circuit Ground |
| **3** | RST | System Reset |
| **4** | VCC | Internal Power |
| **5** | A3 | Analog Input Pin 3 |
| **6** | A2 | Analog Input Pin 2 |
| **7** | A1 | Analog Input Pin 1 |
| **8** | A0 | Analog Input Pin 0 |
| **9** | SCK | SPI Bus Clock |
| **10** | MISO | Master Input Slave Output (SPI) |
| **11** | MOSI | Master Output Slave Input (SPI) |
| **12** | D10 | Digital Input/Output Pin 10 |

## Connector J3

| Pin | Name | Description |
| :---: | :--- | :--- |
| **1** | **GND** | Circuit Ground |
| **2** | **GND** | Circuit Ground |
| **3** | VCC | Internal Power |
| **4** | RXI | UART Serial Receive Input |
| **5** | TXO | UART Serial Transmit Output |
| **6** | DTR |  Data Termnal Ready |



