# Module II: Prototyping Embedded Devices

## 1. Electronics Fundamentals
- **Description**: This section covers the fundamental principles of electronics that are essential for building IoT devices. It includes understanding basic components like resistors, capacitors, diodes, and transistors, as well as learning how to read schematics and use a breadboard for prototyping.
- **Key Concepts**:
    - **Ohm's Law**: The relationship between voltage, current, and resistance (V = IR).
    - **Kirchhoff's Laws**: Rules for analyzing current and voltage in circuits.
    - **Analog vs. Digital Signals**: Understanding the difference between continuous analog signals and discrete digital signals.

## 2. Embedded Computing Basics
- **Description**: This introduces the core concepts of embedded systems, which are specialized computing systems designed for specific tasks within a larger system. It covers the architecture of microcontrollers and microprocessors, memory types (RAM, ROM, Flash), and input/output (I/O) peripherals.
- **Key Concepts**:
    - **Microcontroller (MCU)**: A small computer on a single integrated circuit containing a processor core, memory, and programmable I/O peripherals.
    - **Microprocessor (MPU)**: A central processing unit (CPU) on a single integrated circuit that requires external components like memory and I/O devices.
    - **GPIO (General-Purpose Input/Output)**: Pins on an MCU that can be configured as either inputs or outputs to interact with other components.

## 3. Arduino Platform
- **Description**: An open-source electronics platform based on easy-to-use hardware and software. It's popular for beginners and rapid prototyping due to its simple programming environment (Arduino IDE) and extensive community support.

### 3.1. Arduino Uno R3 Specifications
- **Microcontroller**: ATmega328P
- **Operating Voltage**: 5V
- **Input Voltage (recommended)**: 7-12V
- **Input Voltage (limits)**: 6-20V
- **Digital I/O Pins**: 14 (of which 6 provide PWM output)
- **Analog Input Pins**: 6
- **DC Current per I/O Pin**: 20 mA
- **DC Current for 3.3V Pin**: 50 mA
- **Flash Memory**: 32 KB (of which 0.5 KB used by bootloader)
- **SRAM**: 2 KB
- **EEPROM**: 1 KB
- **Clock Speed**: 16 MHz

### 3.2. Arduino Programming
- **Language**: C/C++
- **IDE**: Arduino IDE
- **Core Libraries**: Provides a set of standard functions for interacting with the hardware.
- **Third-Party Libraries**: A vast collection of libraries for a wide range of sensors, actuators, and communication protocols.

## 4. Raspberry Pi Platform
- **Description**: A series of small single-board computers (SBCs) that run a full-fledged operating system, typically a Linux distribution. It's more powerful than an Arduino and is suitable for more complex applications that require networking, multimedia, or significant data processing.

### 4.1. Raspberry Pi 4 Model B Specifications
- **Processor**: Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.5GHz
- **RAM**: 1GB, 2GB, 4GB, or 8GB LPDDR4-3200 SDRAM (depending on model)
- **Connectivity**:
    - 2.4 GHz and 5.0 GHz IEEE 802.11ac wireless, Bluetooth 5.0, BLE
    - Gigabit Ethernet
    - 2 USB 3.0 ports; 2 USB 2.0 ports.
- **GPIO**: Standard 40-pin GPIO header
- **Video & Sound**:
    - 2 × micro-HDMI ports (up to 4kp60 supported)
    - 2-lane MIPI DSI display port
    - 2-lane MIPI CSI camera port
    - 4-pole stereo audio and composite video port
- **Multimedia**: H.265 (4kp60 decode), H264 (1080p60 decode, 1080p30 encode), OpenGL ES 3.0 graphics
- **SD card support**: Micro SD card slot for loading operating system and data storage
- **Power**: 5V DC via USB-C connector (minimum 3A)

### 4.2. Raspberry Pi Operating Systems
- **Raspberry Pi OS (formerly Raspbian)**: The official Debian-based OS.
- **Other Supported OSs**: Ubuntu, Windows 10 IoT Core, and others.

## 5. BeagleBone Black
- **Description**: Another popular single-board computer that is known for its extensive I/O capabilities. It's often used in robotics and industrial applications where a large number of sensors and actuators need to be connected.
- **Key Features**:
    - **Processor**: AM335x 1GHz ARM® Cortex-A8
    - **I/O**: 2x 46-pin headers with a large number of GPIOs, ADCs, and other peripherals.
    - **"Capes"**: Add-on boards similar to Arduino shields.

## 6. Electric Imp
- **Description**: A platform that provides an easy way to connect devices to the internet. It consists of a small Wi-Fi module (the "Imp") and a cloud service for managing and programming the device.
- **Key Features**:
    - **Cloud-Based**: Devices are programmed and managed through the Electric Imp cloud.
    - **Squirrel**: Uses a C-like scripting language called Squirrel.
    - **Security**: Offers a secure and managed environment for IoT devices.

## 7. Other Notable Platforms
- **Description**: This category includes other platforms and technologies used in IoT prototyping.
- **Examples**:
    - **ESP8266/ESP32**: Low-cost Wi-Fi microchips with a full TCP/IP stack and microcontroller capability.
    - **Particle (formerly Spark)**: A platform similar to Electric Imp that provides hardware modules and a cloud platform for IoT development.
    - **Tessel**: A hardware platform that uses JavaScript for programming.