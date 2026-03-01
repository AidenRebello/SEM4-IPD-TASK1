# SEM4-IPD-TASK1

A custom-designed standalone development board based on the ATmega328P microcontroller, developed as part of IPD Task 1 submission.
This project includes schematic design, PCB layout, power system design, clock circuitry, reset circuitry, and ISP programming interface implementation.

---

## Project Overview

The objective of this project was to design and fabricate a minimal yet fully functional AVR development board capable of operating independently without external development hardware.

The board is intended for:

- Embedded systems prototyping  
- Sensor and actuator interfacing  
- Serial communication experiments  
- Academic and hobby projects  

This project emphasizes practical understanding of microcontroller hardware design and PCB implementation.

---

##  Microcontroller Specifications

- Microcontroller: ATmega328P  
- Architecture: 8-bit AVR RISC  
- Operating Voltage: 5V  
- Clock Frequency: 16 MHz (External Crystal)  
- Flash Memory: 32 KB  
- SRAM: 2 KB  
- EEPROM: 1 KB  
- GPIO Pins: 23 Programmable I/O Pins  

---

##  Hardware Features

- 16 MHz Crystal Oscillator with Load Capacitors  
- Reset Circuit (Pull-up Resistor + Push Button)  
- 5V Voltage Regulation Circuit  
- Input Filtering Capacitors  
- Decoupling Capacitors near VCC and AVCC  
- 6-Pin ISP Programming Header  
- Power Indicator LED  
- Broken-out GPIO Headers  
- External Power Input Support  
- Ground Plane Implementation for Noise Reduction  

---

##  Power System

The board includes a regulated 5V power supply section with:

- Input voltage filtering  
- Proper decoupling near power pins  
- Stable VCC and AVCC routing  
- Ground plane for improved signal integrity  

---

##  Design Tools

- PCB Design Software: KiCAD

---

##  Repository Structure

```text
├── Schematics/
├── PCB_Layout/
├── Gerber_Files/
├── Images/
├── Datasheets/
└── README.md
```

---

## Programming Instructions

1. Connect an ISP programmer to the 6-pin header.
2. Select ATmega328P in the programming IDE.
3. Configure clock settings for 16 MHz external crystal.
4. Burn bootloader (if required).
5. Upload firmware via ISP.

---

## Board Images



```markdown
![Top View](<img width="625" height="581" alt="image" src="https://github.com/user-attachments/assets/44237a23-9b0f-4b50-a84e-91c0177f63dc" />
)
![Bottom View](<img width="590" height="557" alt="image" src="https://github.com/user-attachments/assets/bd40d8e8-acc7-40c5-b0ad-604a2e044214" />
)
```

---

## Learning Outcomes

- Designing minimum system for AVR microcontroller  
- PCB layout planning and ground plane usage  
- Power supply and decoupling design  
- Clock circuit implementation  
- Hardware debugging and validation  

---

## Future Improvements

- On-board USB-to-Serial Interface  
- 3.3V Output Option  
- Reverse Polarity Protection  
- I2C / SPI Expansion Headers  
- On-board USB Programming  

---

## Author

Name: Aiden Rebello 
Branch: Electronics & Telecommunication (EXTC)  
Year: Second Year  
Course: IPD Task 1  

