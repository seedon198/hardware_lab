# Hardware Security Laboratory Setup Guide

This guide provides a comprehensive overview of essential equipment for establishing a professional hardware security laboratory. The equipment is organized by functional categories with detailed specifications and budget considerations for building capabilities from basic to advanced levels.


This hardware security laboratory setup enables:

- **Device Analysis:** Complete hardware teardown and reverse engineering workflows
- **Firmware Extraction:** Multiple extraction techniques using JTAG, UART, and chip-off methods
- **Side-Channel Analysis:** Power analysis and fault injection for cryptographic testing
- **Protocol Analysis:** RF, serial, and bus protocol reverse engineering
- **Physical Security Testing:** RFID cloning, lock picking, and access control bypass
- **IoT Security Assessment:** Comprehensive evaluation of connected devices

## Additional Resources

For detailed implementation guides and best practices, consider these reference materials:

- Hardware Hacking Handbook by Jasper van Woudenberg and Colin O'Flynn
- The Hardware Hacker by Andrew "bunnie" Huang
- Side-Channel Attacks: Ten Years After Its Publication and the Impacts on Cryptographic Module Security Testing
- IoT Penetration Testing Cookbook by Aaron Guzman and Aditya Gupta


## Equipment Categories

| Category | Description | Budget Range |
|----------|-------------|--------------|
| **Wireless Analysis** | RF analysis and signal capture tools | $500 - $3000+ |
| **Red Team Tools** | Physical security testing equipment | $200 - $1500 |
| **Reverse Engineering** | Hardware debugging and analysis | $300 - $2000+ |
| **Lab Infrastructure** | Essential bench and measurement equipment | $1000 - $5000+ |

# Essential Lab Infrastructure

## Lab Setup Planning

### Foundation Level ($500-1,200)
Essential equipment for basic hardware analysis:
- Digital multimeter (Fluke 115 or Keysight U1232A) - $200-300
- Temperature-controlled soldering station - $80-150
- USB-UART adapter (FTDI FT232H-based) - $25-40
- 8-channel logic analyzer (Saleae clone) - $15-100
- Breadboard kit with premium jumper wires - $30-50
- ESD-safe precision hand tools - $50-100
- Anti-static workstation mat and wrist strap - $30-60
- Component storage and organization system - $40-80

### Intermediate Level ($1,200-3,500)
Enhanced analysis and debugging capabilities:
- Entry-level oscilloscope (Rigol DS1054Z) - $400-500
- Bus Pirate v4 or similar multi-protocol tool - $30-60
- Hot air rework station with temperature/airflow control - $150-300
- RTL-SDR bundle with antenna kit - $50-100
- Benchtop power supply (0-30V, current limiting) - $200-400
- Digital microscope (USB, 10-200x magnification) - $100-300
- Frequency counter (1Hz-3GHz range) - $150-250
- RF signal generator (1MHz-1GHz basic) - $200-500

### Professional Level ($3,500+)
Advanced analysis and specialized research tools:
- Professional oscilloscope (100MHz+, 4-channel) - $1500-5000
- Vector network analyzer (VNA, 1MHz-6GHz) - $800-3000
- High-end SDR platform (bladeRF 2.0, USRP B200) - $600-2000
- ChipWhisperer or similar side-channel platform - $300-800
- Precision power analyzer with logging - $500-1500
- Shielded RF test enclosure - $300-800
- High-resolution thermal imaging camera - $1000-5000
- X-ray inspection system (optional, advanced) - $10000+

## Safety Guidelines

### Electrical Safety
- GFCI protection on all AC outlets
- Isolation transformers for unknown devices
- Current-limited supplies for initial testing
- Proper fusing and overcurrent protection

### ESD Protection
- Conductive work surface with proper grounding
- ESD-safe tools and storage containers
- Humidity control (30-70% relative humidity)
- Personnel grounding via wrist straps

### RF Safety
- Power level awareness and documentation
- Antenna near-field safety distances
- Shielded enclosures for high-power testing
- RF exposure calculation tools

### Chemical Safety
- Adequate ventilation for soldering fumes
- Lead-free solder for reduced toxicity
- Proper flux cleaning procedures
- Material Safety Data Sheet (MSDS) library

## Equipment Selection Strategy

### Budget Optimization
| Investment Level | Priority Equipment |
|------------------|-------------------|
| Essential ($500) | Multimeter, soldering iron, logic analyzer |
| Intermediate ($2K) | Oscilloscope, power supply, microscope |
| Advanced ($5K+) | VNA, high-end SDR, thermal imaging |
| Professional ($10K+) | X-ray, electron microscopy, specialized test equipment |

### Vendor Categories
| Vendor Type | Examples | Best For |
|------------|----------|----------|
| Test Equipment | Keysight, Tektronix, Rigol | Precision instruments, calibrated tools |
| Security Tools | Hacker Warehouse, Lab401 | Specialized penetration testing hardware |
| Components | Digikey, Mouser, Arrow | Electronic components, development boards |
| Used Equipment | eBay, University Surplus | Budget-conscious professional equipment |

## Maintenance and Calibration

### Regular Maintenance Schedule
| Equipment Type | Frequency | Procedure |
|---------------|-----------|-----------|
| Multimeters | 12 months | Professional calibration service |
| Oscilloscopes | 12 months | Self-cal + annual professional verification |
| Power Supplies | 6 months | Output verification, safety checks |
| RF Equipment | 6 months | Return loss, power output verification |

### Equipment Documentation
Maintain comprehensive records including:
- Purchase date and warranty information
- Calibration certificates and schedules
- Operating manuals and software versions
- Modification history and configuration notes
- Performance specifications and tolerances

## Featured Basic Lab Equipment
### 1. Digital Multimeter

![Digital Multimeter](res/20.png)

**Basic multimeter for voltage, current, and resistance measurements.**

**Features:**
- DC/AC voltage measurement
- Current measurement
- Continuity tester
- Diode tester
- Transistor tester
- 9V battery powered (included)
- High quality test probes

**Price:** Rs. 589  
**Source:** [Protocentral](https://protocentral.com/product/digital-multimeter/)

### 2. KPH Hakko FX888D-23BY Digital Soldering Station

![Digital Soldering Station](res/21.png)

**Specifications:**
- Brand: KPH
- Weight: 2.6 pounds
- Dimensions: 24.4 x 24.4 x 18.5 cm
- Voltage: 120V
- Power: 70W

**Price:** ₹13,399  
**Source:** [Amazon India](https://www.amazon.in/Hakko-FX888D-23BY-Digital-Soldering-Station/dp/B00ANZRT4M/)

### 3. Smiledrive Digital HD Microscope

![Digital HD Microscope](res/22.png)

**Specifications:**
- Magnification: 50X-1000X
- Screen: 4.3" LCD
- Battery: 2600mAh built-in rechargeable
- LED lights: 8 adjustable LEDs
- Weight: 680 grams
- Package dimensions: 9.7 x 7.6 x 5.3 inches

**Price:** ₹5,899  
**Source:** [Amazon India](https://www.amazon.in/Smiledrive-Microscope-50-1000x-Magnification-Connects/dp/B07T3D6JWN/)

### 4. Hantek DSO2C15 Digital Storage Oscilloscope

![Digital Storage Oscilloscope](res/23.png)

**Key Specifications:**
- Channels: 2 (independently controlled)
- Bandwidth: 150MHz analog
- Sampling rate: Up to 1 GSa/s
- Memory depth: 8M
- Vertical range: 2mV/div ~ 10V/div
- Vertical resolution: 8-bit

**Advanced Features:**
- Multiple trigger types: Edge, Pulse, Video, Slope, Overtime, Window, Pattern, Interval, Under Amp, UART, LIN, CAN, SPI, IIC
- Bus decode and protocol analysis: RS232/UART, I2C, SPI, CAN, LIN
- 32 automatic measurements with statistics
- 2 sets of digital voltmeters
- SCPI remote command control
- USB Host/Device support

**Price:** ₹30,000  
**Source:** [Amazon India](https://www.amazon.in/Hantek-DSO2C15-Digital-Oscilloscope-Bandwidth/dp/B08Y6M9TML/)


# Wireless Analysis Equipment

## 1. 700~5800 MHz Antenna

![700~5800 MHz Antenna](res/01.png)

**Frequency Coverage:** 698-960 MHz, 1575.42 MHz, 1710-2700 MHz, 5150-5850 MHz  
**Applications:** Cellular, ISM and Wi-Fi frequency analysis  
**Price:** $40.00 (SKU: TG-358113)  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/700-5800-mhz-antenna/)

## 2. 20-6000 MHz Near Field Antenna

![Near Field Antenna](res/02.png)

**Specifications:** 25mm diameter H-Loop antenna  
**Frequency Range:** 20-6000 MHz  
**Applications:** Near-field RF measurement and analysis  
**Price:** $35.00 (SKU: S-H25)  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/20-6000-mhz-near-field-antenna/)

## 3. Flipper Zero

![Flipper Zero](res/03.png)

**Key Features:**
- Sub 1-GHz transceiver
- 125kHz RFID reader/writer
- 13.56 MHz NFC support
- Bluetooth connectivity
- Infrared transceiver
- 1-Wire iButton interface
- GPIO expansion headers

**Price:** $200.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/flipper-zero/)

## 4. bladeRF 2.0 xA4 Kit

![bladeRF Kit](res/04.png)

![bladeRF Specs](res/05.png)

**Kit Contents:**
- bladeRF 2.0 micro xA4
- bladeRF micro case
- BT-100 Bias-tee Power Amplifier (TX)
- BT-200 Bias-tee Low Noise Amplifier (RX)

**RF Specifications:**
- ADC/DAC Sample Rate: 0.521 – 61.44 MSPS
- ADC/DAC Resolution: 12 bits
- RF Tuning Range (RX): 70 – 6000 MHz
- RF Tuning Range (TX): 47 – 6000 MHz
- CW Output Power: +8 dBm

**Price:** $600.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/bladerf-2-xa4-kit/)

## 5. Ubertooth One
![Ubertooth One](res/06.png)

**Key Features:**
- 2.4 GHz transmit and receive capability
- Transmit power and receive sensitivity comparable to Class 1 Bluetooth device
- Standard Cortex Debug Connector (10-pin 50-mil JTAG)
- In-System Programming (ISP) serial connector
- Expansion connector for inter-Ubertooth communication
- Six indicator LEDs

**Components:**
- RP-SMA RF connector
- CC2591 RF front end
- CC2400 wireless transceiver
- LPC175x ARM Cortex-M3 microcontroller with Full-Speed USB 2.0
- USB A plug

**Applications:** Open source 2.4 GHz wireless development platform for Bluetooth experimentation and monitoring. Cost-effective alternative to commercial Bluetooth monitoring equipment (which can cost $10,000+).

**Price:** $125.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/ubertooth-one/)

## 6. Proxmark3 RDV4

![Proxmark3 RDV4](res/07.png)

**Core Capabilities:**
- Read virtually any RFID tag
- Emulate reader or tag operations
- Sniff communications between reader and tag
- Standalone operation without PC (requires USB battery)

**RDV4 Improvements:**
- Enhanced LF and HF antenna design for portability
- Improved enclosure
- Multi-function expansion port
- 4 mode LEDs, 4 power LEDs, user button

**Price:** $340.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/proxmark3-rdv4-kit/)

### Bluetooth + Battery Module for Proxmark3 RDV4

![Proxmark3 Bluetooth Module](res/08.png)

**Features:**
- 400 mAh battery for standalone operation
- Bluetooth 2.0 with EDR (default baud rate 115200)
- Complete lithium charging management with overcharge/overdischarge protection
- Independent Bluetooth power switch
- Temperature stability with heat dissipating fins
- Easy clamp installation structure

**Specifications:**
- Battery capacity: 400 mAh
- Operating time: 3.5h standby, 2.9h LF-On, 50min HF-On
- Charging current: 200mA
- Charging time: 2.5h
- Bluetooth power: 4dBm, -85 dBm@2Mbps
- Bluetooth range: 6m (environment dependent)
- Dimensions: 54.4mm × 29.4mm × 13.5mm, 24g

**Price:** $100.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/proxmark3-rdv4-bluetooth-battery-module/)

### Proxmark3 RDV4 LF Antenna Set

![Proxmark3 LF Antennas](res/09.png)

**Contents:** LF medium antenna and LF long range antenna  
**Design:** 6-layer PCB with 6 overlapping coils  
**Switch Options:**
- Q 7: Better accuracy for card data dumping
- Q 14: Better range distance  
- F 125: Improved 125kHz tag range
- F 134: Improved 134kHz tag range

**Read Distance Comparison:**
| Antenna Type | Read Distance |
|--------------|---------------|
| LF/HF Standard (fits in case) | 40 – 85mm |
| LF Medium (fits in case) | 66 – 98mm |
| LF Long Range | 66 – 133mm |

**Price:** $90.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/proxmark3-rdv4-lf-antenna-set/)

### Proxmark3 RDV4 HF Antenna Set

![Proxmark3 HF Antennas](res/10.png)

**Contents:** HF medium antenna and HF long range antenna  
**Modular Design:** Antennas can be swapped based on engagement requirements

**Read Distance Comparison:**
| Antenna Type | Read Distance |
|--------------|---------------|
| LF/HF Standard (fits in case) | 40 – 85mm |
| HF Medium (fits in case) | 90mm |
| HF Long Range | 100 – 120mm |

**Price:** $90.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/proxmark3-rdv4-hf-antenna-set/)

### T5557 Read/Write 125kHz Cards (10 Pack)

![T5557 Cards](res/11.png)

**Specifications:**
- Frequency: 125kHz
- Compatibility: EM4100, HID, and Indala formats
- Quantity: 10 cards per pack
- Read/write capability

**Price:** $30.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/t5557-readwrite-125khz-card/)

# Red Team Tools

## 1. KeyGrabber

![KeyGrabber](res/12.png)

**Description:** Physical hardware keyloggers that operate transparently without requiring software or drivers. Supports international keyboard layouts.

**Available Models:**
| Model | Connection | Length | Memory | Timestamp | Wireless | Mac Support |
|-------|------------|--------|---------|-----------|----------|-------------|
| PS/2 | PS/2 | 1.9" | 4MB | No | No | No |
| USB Pico | USB | 0.8" | 16MB | No | No | No |
| USB WiFi Premium | USB | 1.0" | 16MB | Yes | Yes | Yes |

**Features:**
- USB Mass Storage mode for data retrieval
- Wireless models support TCP streaming and email delivery
- Battery/clock for timestamping (WiFi Premium model)

**Price:** $55.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/keygrabber/)

## 2. USB Ninja Cable

![USB Ninja Cable](res/13.png)

**Description:** Appears and functions as a regular USB cable (power and data) until remotely triggered to deliver a customized attack payload.

**Key Features:**
- Emulates keyboard and mouse actions
- Customizable payload targeting
- Wireless remote control activation
- Undetectable by visual inspection
- Functions normally as USB cable when not triggered

**Applications:** Penetration testing, physical security assessments

**Price:** $75.00 (includes 1 cable and 1 trigger/programming ring)  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/usb-ninja-cable/)

### USB Ninja Bluetooth Remote

![USB Ninja Remote](res/14.png)

**Features:**
- Wireless trigger for USB Ninja cables
- Dual payload capability via toggle buttons
- RP-SMA antenna connector for extended range

**Price:** $50.00 (was $60.00)  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/usb-ninja-bluetooth-remote/)

## 3. Rainbow Tables HDD

![Rainbow Tables HDD](res/15.png)

![Rainbow Tables Contents](res/16.png)

**Specifications:**
- Capacity: 2TB USB 3.0 external drive
- Pre-loaded with comprehensive rainbow tables

**Contents:**
- A51 tables
- LM: alpha-numeric-symbol32-space
- WPA-PSK: 1 million words × 1000 SSIDs
- MD5: loweralpha-numeric 1-8 characters
- MD5: mixalpha-numeric 1-7 characters

**Price:** $150.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/rainbow-tables-hdd/)

# Reverse Engineering Tools

## 1. ChipWhisperer-Lite Bundle

![ChipWhisperer-Lite](res/17.png)

**Core Platform:**
- Embedded hardware security research tool
- Side-channel power analysis capabilities
- Glitching capabilities for fault injection
- Open-source toolchain (GPL licensed)

**Bundle Includes:**
- ChipWhisperer-Lite main unit
- Breaker addon with additional cables
- NOTDuino target board (Atmel AVR-based target for side-channel analysis and glitching)

**Applications:** Hardware security research, side-channel analysis, fault injection testing

**Price:** $370.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/chipwhisperer-lite-bundle/)

## 2. JTAGulator Kit

![JTAGulator](res/18.png)

**Description:** Open source hardware tool for identifying On-Chip Debug (OCD) connections from test points, vias, or component pads on target devices.

**Key Features:**
- 24 I/O channels with input protection circuitry
- Adjustable target voltage: 1.2V to 3.3V
- Supported interfaces: JTAG/IEEE 1149.1, UART/asynchronous serial
- USB interface for direct computer connection
- Simple logic analyzer capability
- Propeller development board functionality

**Includes:** JTAGulator device and one set of data probes

**Price:** $195.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/jtagulator/)

## 3. Bus Pirate Kit

![Bus Pirate](res/19.png)

**Description:** Universal electronic tool for programming and interfacing with communication buses and programming various chips.

**Supported Protocols (0-5.5V line levels):**
- 1-Wire, I²C, SPI, JTAG
- Asynchronous serial, MIDI, PC keyboard
- HD44780 LCD
- 2- and 3-wire libraries with bitwise pin control

**Additional Capabilities:**
- 0-6V measurement probe
- 1Hz-40MHz frequency measurement
- 1kHz-4MHz pulse-width modulator and frequency generator
- On-board 3.3V and 5V power supplies with software reset
- Bus traffic sniffers (SPI, I²C)
- 10Hz-1MHz SUMP compatible logic analyzer
- AVR STK500 v2 programmer clone
- Scriptable operation (Perl, Python, etc.)

**Includes:** Bus Pirate, acrylic case, data probes

**Price:** $50.00  
**Source:** [Hacker Warehouse](https://hackerwarehouse.com/product/bus-pirate/)

## 4. Low Voltage eMMC Adapter

![Low Voltage eMMC Adapter](res/24.png)

**Description:** Interface adapter for low voltage eMMC storage devices with standard SD/MMC adapters.

**Key Features:**
- TI TXS02612-based logic level translation
- Input voltage range: 1.1V to 3.6V
- SD card form factor for easy connection
- Mobile device storage forensics capability

**Applications:**
- Mobile device data recovery
- eMMC chip forensic analysis
- Storage device reverse engineering
- Low-voltage embedded system interfacing

**Price:** $12.00  
**Source:** [Exploitee.rs](https://shop.exploitee.rs/)
