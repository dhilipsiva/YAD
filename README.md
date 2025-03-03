# YAD - Yet Another Device


This is a specification document for the design and functionality of a low-power, peer-to-peer communication device. This document outlines the key features, hardware components, and software architecture required to build a device. A device is designed for secure and efficient proximity scenarios.

In today's interconnected world, there's a growing need for secure and efficient communication that doesn't rely on internet connectivity or traditional cellular networks. A device fills this gap by providing a solution that enables users to exchange data seamlessly and securely in close proximity scenarios. Whether you're a member of an organization looking for a secure way to share sensitive information or an individual seeking a reliable data transfer method between devices, a device offers a versatile and efficient solution.


## Features

- **Low Power Consumption**: A device is designed to operate for weeks on a single battery charge.
- **Close-Proximity Communication**: Utilizes Bluetooth Low Energy (BLE), and NFC for communication.
- **Security**: Implements robust security measures to ensure data privacy.
- **Ease of Use**: Simple and intuitive user interface for efficient data transfer.

## Hardware Components

A device leverages a carefully selected set of hardware components to achieve its low-power and high-efficiency goals:

- **E-ink Display**: The device features an E-ink display, prioritizing efficiency and readability in various lighting conditions.

- **RISC-V Microcontroller**: Powered by a RISC-V microcontroller, the device ensures efficient processing and low power consumption.

- **BLE/NFC Sensor**: A device uses BLE or NFC technology for close proximity communication, offering security and efficiency.

- **Micro-SD Card Slot**: The device employs a micro-SD card slot for storage and booting purposes, ensuring versatility and ease of use.

- **Beeping Speaker**: A beeping speaker is included for audio cues and alerts, enhancing user interaction.

## Software Architecture

A device's software architecture is designed to optimize performance, security, and flexibility:

- **Operating System**: TockOS - An embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers.

- **Communication Protocol**: A device employs a secure communication protocol optimized for proximity data transfer. It prioritizes data privacy and integrity while ensuring efficient data exchange.

- **User Interface**: The software includes a straightforward user interface, optimized for the E-ink display. It enables users to initiate and manage secure data transfers with ease.

- **Security Measures**: The software incorporates robust security measures, including data encryption, authentication, and access control, to protect sensitive information during transfer and storage.
