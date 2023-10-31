# PLC-based Sorting Station using Node-RED with OPC

![Sorting Station](sorting_station.jpg)

This GitHub repository contains the project files and documentation for a PLC-based Sorting Station using Node-RED with OPC (OLE for Process Control). The project utilizes several software components, including Factory IO, KepserverEx, and Node-RED to create a flexible and efficient sorting system.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

The PLC-based Sorting Station is a simulation of an industrial sorting system where objects are sorted based on certain criteria. In this project, we use Factory IO to simulate the physical sorting process, KepserverEx to communicate with the PLC (Programmable Logic Controller), and Node-RED for logic control and visualization. This repository provides the necessary files and instructions to set up and run this system.

## Features

- Real-time simulation of a sorting station using Factory IO.
- PLC-based control of the sorting process.
- Integration of Factory IO with KepserverEx for communication with the PLC.
- Logic control and visualization of the sorting process using Node-RED.
- Easily configurable for different sorting criteria and object types.

## Requirements

Before you can run this project, make sure you have the following software components installed:

1. **Factory IO**: Factory IO is used for simulating the sorting station. You can download it from [here](https://www.factoryio.com/).

2. **KepserverEx**: KepserverEx is used as an OPC server to communicate with the PLC. You can obtain it from [Kepware](https://www.ptc.com/en/products/industrial-automation/kepware).

3. **Node-RED**: Node-RED is used for logic control and visualization. You can install it using Node.js with the following command:

   ```
   npm install -g --unsafe-perm node-red
   ```

   For more information, visit the [Node-RED website](https://nodered.org/).

4. **PLC**: You need access to a PLC that is compatible with KepserverEx. This PLC should support the required input and output signals for your sorting station.

## Getting Started

Follow these steps to set up and run the PLC-based Sorting Station:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/codewithzahid/Sorting-Station-PLC.git
   ```

2. Configure Factory IO to use the provided simulation profile (if available).

3. Configure KepserverEx to connect to your PLC and expose the necessary tags for communication.

4. Start Node-RED and import the Node-RED flow from the repository (if available).

5. Configure the Node-RED flow to interact with KepserverEx and control the sorting process.

6. Start the Node-RED flow to begin the sorting process.

7. Observe the sorting station in action through Factory IO and Node-RED.

## Project Structure

The repository is organized as follows:

- `/documentation`: Contains documentation and user guides.
- `/node-red-flow`: Contains Node-RED flow configurations.
- `/images`: Contains images and diagrams related to the project.
- `/configs`: Configuration files for Factory IO and KepserverEx.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute to this project, report issues, or suggest improvements. Your feedback and contributions are highly appreciated!