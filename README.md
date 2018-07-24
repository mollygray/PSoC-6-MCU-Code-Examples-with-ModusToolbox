# Cypress-PSoC-6-MCU-Code-Examples

# Table of Contents

* [Introduction](#introduction)
* [Navigating the Repository](#navigating-the-repository)
* [Required Tools](#required-tools)
* [Kits](#kits)
* [Code Example List](#code-example-list)
* [Technical Resources](#technical-resources)

# Introduction
In general, each code example is in a separate repository. This makes it easy for you to get just what you need. Occasionally two or more examples work with each other. For example, perhaps a SPI Master and SPI Slave. You'll find closely related examples that work with each other in a single repository.

This ReadMe describes the available code examples for PSoC 6 MCU, a single chip solution for the emerging IoT devices. PSoC 6 MCU bridges the gap between expensive, power hungry application processors and low‑performance microcontrollers (MCUs). The ultra‑low‑power, dual-core architecture of PSoC 6 MCU offers the processing performance needed by IoT devices, eliminating the tradeoffs between power and performance.

Feel free to explore the code example source files and let's innovate together!

# Navigating the Repository

The examples provided on this GitHub page helps you to get acquainted with PSoC 6 MCU and how to use PSoC Creator to develop a PSoC 6 MCU based design.
For block level examples please refer to the following GitHub repositories:

#### 1. [Analog Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-Analog-Designs)
#### 2. [Digital Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-Digital-Designs)
#### 3. [BLE Connectivity Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-BLE-Connectivity-Designs)
#### 4. [Audio Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-Audio-Designs)
#### 5. [Device Related Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-Device-Related-Design)
#### 6. [System-Level Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-System-Level-Designs)
#### 7. [PSoC 6 Pioneer Kit Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-Pioneer-Kits)
#### 8. [PSoC 6 MCU based RTOS Designs](https://github.com/cypresssemiconductorco/PSoC-6-MCU-RTOS-Based-Design)

You can use these block level examples to guide you through the development of a system-level design using PSoC 6 MCU. All the code examples in this repository comes with well documented design guidelines to help you understand the design and how to develop it. The code examples and their associated documentation are in the Code Example folder in the repository.

# Required Tools

## Software
### Integrated Development Environment (IDE)
To use the code examples in this repository, please download and install
[PSoC Creator](http://www.cypress.com/products/psoc-creator)

# Kits
### PSoC 6 MCU Development Kits
* [CY8CKIT-062-BLE PSoC 6 BLE Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/psoc-6-ble-pioneer-kit).

* [CY8CKIT-062 PSoC 6 WiFi-BT Pioneer Kit](http://www.cypress.com/documentation/development-kitsboards/psoc-6-wifi-bt-pioneer-kit). 

**Note** Please refer to the code example documentation for selecting the appropriate kit for testing the project

# Code Example List
#### 1. CE221773 - PSoC 6 MCU - Hello World Example
This code example demonstrates the implementation of simple UART communication and LED control using PSoC 6 MCU. The UART and LED control tasks are executed by the Arm Cortex-M4 CPU of PSoC 6 MCU.
#### 2. CE220263 - PSoC 6 MCU GPIO Pins Example
This example demonstrates multiple methods of configuring, reading, writing, and generating interrupts with PSoC 6 General
Purpose Input/Output (GPIO) pins. Both the PSoC Creator schematic Pins Component and PDL GPIO driver methods are
shown.
#### 3. CE216795 - PSoC 6 MCU Dual-Core Basics
These examples demonstrate the two CPU cores in PSoC 6 MCU doing separate independent tasks, and communicating with
each other using shared memory and the inter-processor communication (IPC) block.

# Technical Resources

Cypress provides a wealth of data at [www.cypress.com](http://www.cypress.com/) to help you select the right PSoC device and effectively integrate it into your design. Visit our [PSoC 6 MCU](http://www.cypress.com/products/32-bit-arm-cortex-m4-psoc-6) webpage to explore more about PSoC 6 MCU family of device.

For a comprehensive list of PSoC 6 MCU resources, see [KBA223067](https://community.cypress.com/docs/DOC-14644) in the Cypress community.

#### PSoC 6 MCU Datasheets
Device datasheets list the features and electrical specifications of PSoC 6 families of devices: [PSoC 6 MCU Datasheets](http://www.cypress.com/search/all?f%5B0%5D=meta_type%3Atechnical_documents&f%5B1%5D=resource_meta_type%3A575&f%5B2%5D=field_related_products%3A114026)
#### PSoC 6 MCU Application Notes
Application notes are available on the Cypress website to assist you with designing your PSoC application: [A list of PSoC 6 MCU ANs](http://www.cypress.com/psoc6an)
#### PSoC 6 MCU Component Datasheets
PSoC Creator utilizes "components" as interfaces to functional Hardware (HW). Each component in PSoC Creator has an associated datasheet that describes the functionality, APIs, and electrical specifications for the HW. You can access component datasheets in PSoC Creator by right-clicking a component on the schematic page or by going through the component library listing. You can also access component datasheets from the Cypress website: [PSoC 6 Component Datasheets](http://www.cypress.com/documentation/component-datasheets)
#### PSoC 6 MCU Technical Reference Manuals (TRM)
The TRM provides detailed descriptions of the internal architecture of PSoC 6 devices:[PSoC 6 MCU TRMs](http://www.cypress.com/psoc6trm)

### Cypress Developer Community ##

Need support for your design and development questions? Check out the [PSoC 6 forum](https://community.cypress.com/community/psoc-6) on the [Cypress Developer Community 3.0](https://community.cypress.com/welcome). Interact with technical experts in the embedded design community and receive answers verified by Cypress' very best applications engineers. You'll also have access to robust technical documentation, active conversation threads, and rich multimedia content.

[Community Forums](https://community.cypress.com/welcome) | [Videos](http://www.cypress.com/video-library) | [Blogs](http://www.cypress.com/blog) | [Training](http://www.cypress.com/training) | [Components](http://www.cypress.com/cdc/community-components)

### Technical Support

You can also use the following support resources if you need quick assistance:
##### Self-help: [Technical Support](http://www.cypress.com/support)
##### Local Sales office locations: [Sales Office](http://www.cypress.com/about-us/sales-offices)
