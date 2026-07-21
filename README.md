# Course-Portfolio-ITAI-4370-AI-5-6G-Comm-ORAN-Net 
## AI, 5G/6G Communications, and Open RAN

**Student:** Brian Martinez  
**Course:** ITAI 4370 – AI, 5G/6G Communications & Open RAN  

Welcome to my course portfolio. This repository documents my work, progress, and learning throughout ITAI 4370. The course started with basic telecommunications concepts and moved into 5G core networks, Open RAN, AI/ML applications, network analysis, and Python based simulations.

The purpose of this portfolio is to show both my completed work and how my understanding developed over the semester.

## Portfolio Navigation

- [Selected Works](#selected-works)
- [Project Documentation](#project-documentation)
- [Assessment Artifacts](#assessment-artifacts)
- [Skills and Growth](#skills-and-growth)
- [Reflections](#reflections)
- [Tools Used](#tools-used)

## Selected Works

### 1. Telecommunications Fundamentals

**Artifact:** [Assignment 01](assignments/Assignment_01_BrianMartinez.docx)

This assignment covered the foundation of telecommunications systems. Topics included:

- The purpose and scope of telecommunications systems
- Transmitters, channels, and receivers
- Analog versus digital communication
- Performance measures such as bandwidth, noise, latency, and signal quality
- Network topologies including star, mesh, ring, and bus

One important thing I learned early in the course was that a communication system is more than just sending data from one place to another. The transmitter, channel, and receiver all have different jobs, and the design of the network affects how reliable and scalable it can be.

### 2. Wireshark and Signal Analysis Lab

**Artifact:** [Laboratory 2 Evidence](labs/laboratory2_BrianMartinez.pdf)

This lab gave me experience looking at real network traffic in Wireshark. I used protocol filters such as HTTP, IP, and TCP to narrow down traffic and inspect packets.

The lab also included a Python free space path loss calculation at 2.4 GHz. The graph showed that path loss rises as distance increases, which helped connect a wireless networking formula to a visual result.

**Lab screenshots:**

- HTTP filtering in Wireshark
- IP filtering in Wireshark
- TCP filtering in Wireshark
- Free space path loss graph

### 3. 4G EPC and 5G Core Concepts

**Artifact:** [Assignment 02](assignments/Assignment_02_BrianMartinez.pdf)

This assignment focused on the move from 4G to 5G. I covered:

- EPC versus 5G Core
- Service Based Architecture
- Network slicing
- Multi access Edge Computing (MEC)
- AI for dynamic resource allocation
- The Network Repository Function (NRF)

A key takeaway for me was that 5G is designed to be more flexible than earlier networks. Network slicing can support different needs at the same time, such as low latency for autonomous vehicles and low bandwidth connections for IoT devices.

### 4. Open RAN and AI/ML Applications

**Artifact:** [Assignment 03](assignments/Assignment_03_BrianMartinez.pdf)

This assignment covered AI/ML in Radio Access Networks and Open RAN. Topics included:

- AI/ML for radio resource management
- Fault detection and network reliability
- Self Organizing Networks (SON)
- Predictive maintenance
- Traditional RAN versus Open RAN
- Near Real Time RIC and Non Real Time RIC

This work helped me understand how AI can support network operations. For example, AI can monitor traffic demand and adjust resources, while predictive maintenance can identify equipment issues before they cause major service problems.

## Project Documentation

### Midterm Project: Network Traffic Prediction and Network Simulation

**Files:**

- [Midterm Project Notebook](projects/midterm_project.ipynb)
- [Midterm Code and Notes](projects/Mid_Term.txt)
- [Project Documentation](projects/MIDTERM_PROJECT_DOCUMENTATION.md)

The midterm work included three connected activities:

1. Simulating packets moving through routers using SimPy  
2. Modeling router behavior and overload conditions with agent based concepts  
3. Using linear regression to predict network traffic from prior traffic values  

The traffic prediction notebook produced a mean squared error of approximately **7.444**. This project showed me how AI and data analysis can be connected to telecommunications problems such as congestion, routing decisions, traffic forecasting, and resource allocation.

## Assessment Artifacts
