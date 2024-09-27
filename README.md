# Microscope Automation Using LabVIEW

This repository contains the project files for the **Microscope Automation Using LabVIEW**, which was developed as part of a B.Tech degree in Instrumentation Technology from Cochin University of Science and Technology (CUSAT). The project integrates several subsystems of a microscope into a single LabVIEW interface to perform data acquisition, motor control, and EMCCD camera interfacing.

## Project Overview

The objective of this project was to develop an automated control system for a microscope using **LabVIEW**, enabling efficient **STORM (Stochastic Optical Reconstruction Microscopy)** imaging. The project involved:

- **Data Acquisition** using the **NI PCIe-6353 DAQ card**.
- **Motor Control** for the microscope stage using **Thorlabs KDC101**.
- **EMCCD Camera Interfacing** with **Andor iXon Ultra 897** camera.
  
The result is a single integrated LabVIEW program that simplifies the operation of the microscope by automating these tasks.

## Components

### 1. Data Acquisition Using NI DAQ
- Utilizes **NI PCIe-6353 DAQ** for high-speed data acquisition.
- Enables real-time collection of data from various sensors and control systems.

### 2. Motor Controller
- **Thorlabs KDC101** controls the movement of the microscope stage.
- Implemented using LabVIEW’s **.NET integration** to control DC Servo motors.
  
### 3. EMCCD Camera Interface
- **Andor iXon Ultra 897** is used for high-sensitivity imaging.
- Controlled through LabVIEW to manage camera settings and data acquisition.

## Features
- Integration of multiple hardware components into a single software platform.
- Real-time control and monitoring of microscope operations.
- Simplified imaging with **STORM** microscopy techniques.

## Installation

1. Install **LabVIEW** (2020 or later) and ensure the **NI DAQmx driver** is installed.
2. Install **Kinesis** software from **Thorlabs** for motor control.
3. Ensure the **Andor SDK** is set up for camera interfacing.

## Usage

- Open the **LabVIEW VI** files provided in the `/src` directory.
- Configure the hardware settings as described in the `UserGuide.md`.
- Run the LabVIEW program to control the microscope system.

## Future Enhancements
- Incorporating laser control and optical modulators.
- Further optimization of motor control for higher precision.
- Extending compatibility with additional microscope hardware.

## References

1. [Using LabVIEW to Build a High-Performance Controller for Atomic Force Microscopes](https://www.ni.com/en-in/innovations/case-studies/19/using-labview-to-build-a-high-performance-controller-for-an-atomic-force-microscope.html)
2. [Stochastic Optical Reconstruction Microscopy (STORM) Imaging](https://www.microscopyu.com/tutorials/stochastic-optical-reconstruction-microscopy-storm)
3. [Thorlabs KDC101 Documentation](https://www.thorlabs.com/thorproduct.cfm?partnumber=KDC101)

## License

This project is licensed under the MIT License.
