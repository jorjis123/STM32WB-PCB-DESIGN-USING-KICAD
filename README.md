**STM32 Bluetooth Development Board**

A compact, versatile development platform based on the STM32 architecture, designed for Bluetooth Low Energy (BLE) applications and rapid prototyping. This board integrates power management, USB connectivity, and RF capabilities in a small form factor.


**🚀 Key Features**

Microcontroller: Integrated STM32 MCU with Bluetooth support (QFN package).

Connectivity: * USB-C Port: For power and data communication.

UART Header (J4): Dedicated serial interface for debugging or external modules.

SWD Interface (J2): Tag-Connect or pogo-pin footprint for high-speed programming and debugging.

RF Design: * Onboard RF circuitry with an integrated filter (FLT1).

U.FL Connector (J1): For external antenna connection.

**User Interface:**

BOOT Button (SW1): Easy access to bootloader mode for firmware flashing.

Status LEDs for power and user-defined signals.

Power Management: Onboard LDO regulators (U2, U3) to manage USB power delivery.

**🛠 Hardware Overview**
Component Map
Reference	Description
U1	    STM32 Bluetooth MCU
USB	    USB Type-C Connector
J1	    RF U.FL Antenna Connector
J2	    SWD Programming Header (Footprint)
J4	    UART Communication Header
SW1	    Bootloader / User Switch
X1 / X2	High and Low-speed Crystal Oscillators

Programming:
The board can be programmed via the SWD (Serial Wire Debug) port using an ST-LINK/V2 or V3. To enter the built-in system bootloader for USB programming, hold the BOOT button while powering on or resetting the device.


**3D VIEW**


<img width="837" height="479" alt="image" src="https://github.com/user-attachments/assets/bf277398-a1c3-46b9-b641-bb2f30644345" />


**PCB ROUTING**


<img width="736" height="445" alt="image" src="https://github.com/user-attachments/assets/5335fc97-fea1-48b4-b871-6b84848312aa" />

