# Attack Taxonomy for Autonomous Vehicles

This document summarises the attack taxonomy presented in the study:

Cybersecurity for Autonomous Vehicles: Review of Attacks and Defense  
Computers & Security, Volume 103, 2021, Article 102150.

The taxonomy was developed through a review of research on autonomous vehicle
cybersecurity published between 2008 and 2019.

## Overview

Attack research was organised into four major categories:

1. Automotive Control System
2. Autonomous Driving System Components
3. V2X Communication
4. Risk Assessment and Review

## 1. Automotive Control System

Attacks targeting the internal control and communication infrastructure
of vehicles were classified into three areas.

### 1.1 ECU Attacks

Research in this category focuses on attacks against Electronic Control Units
(ECUs), including vulnerabilities that may allow attackers to manipulate
vehicle functions or inject malicious messages into vehicle networks.

### 1.2 In-Vehicle Network Attacks

This category covers attacks against internal vehicle communication networks,
particularly technologies such as the Controller Area Network (CAN).

Examples discussed in the reviewed literature include:

- Sniffing
- Replay attacks
- Message injection
- Spoofing
- Denial-of-Service attacks
- Fuzzing
- Reverse engineering

### 1.3 Automotive Key-Related Attacks

This category includes attacks against vehicle authentication and key systems,
such as passive keyless entry and remote keyless entry mechanisms.

Examples include:

- Relay attacks
- Cryptographic attacks
- Key recovery
- Wireless signal manipulation

## 2. Autonomous Driving System Components

This category covers attacks against components that directly support
autonomous driving functionality.

### 2.1 Sensor Attacks

Research examined attacks against sensors used by autonomous vehicles,
including:

- LIDAR
- RADAR
- Cameras
- Ultrasonic sensors
- GPS

The reviewed studies considered attacks such as spoofing, interference,
and sensor manipulation.

### 2.2 Mobile App Attacks

This category covers vulnerabilities and attacks involving mobile applications
and smartphones connected to vehicle systems.

Such attacks may provide a path from an external mobile device to internal
vehicle systems and networks.

## 3. V2X Communication

Vehicle-to-Everything (V2X) communication introduces external communication
interfaces that can become attack surfaces.

### 3.1 VANET Attacks

Vehicular Ad Hoc Network (VANET) research includes attacks such as:

- Man-in-the-middle attacks
- Denial-of-Service attacks
- Replay attacks
- Spoofing
- Malicious code
- Location tracking
- Bogus information attacks

### 3.2 Infotainment and Bluetooth Attacks

This category includes attacks targeting vehicle infotainment systems,
Bluetooth interfaces, telematics systems, and other externally connected
vehicle services.

Research reviewed in the study demonstrated that such systems can provide
attack paths into internal vehicle networks.

## 4. Risk Assessment and Review

A separate group of studies analysed autonomous vehicle cybersecurity
from a systematic risk and threat-modelling perspective.

### 4.1 Risk Assessment

These studies evaluated:

- Security threats
- Attack likelihood
- Potential impact
- Security requirements
- Risk prioritisation

### 4.2 Attack Trees and Methodologies

Research in this category used structured approaches such as:

- Attack trees
- Threat modelling
- STRIDE
- Security testing methodologies
- Attack surface analysis

### 4.3 Review and Survey Studies

This category includes prior surveys and reviews examining:

- Automotive attack surfaces
- In-vehicle network vulnerabilities
- Connected vehicle threats
- Security testing
- Automotive cybersecurity lifecycle issues

## Taxonomy Structure

```text
Attacks on Autonomous Vehicles
├── Automotive Control System
│   ├── ECU
│   ├── In-vehicle Network
│   └── Automotive Key
├── Autonomous Driving System Components
│   ├── Sensor
│   └── Mobile App
├── V2X Communication
│   ├── VANET
│   └── Infotainment
└── Risk Assessment & Review
    ├── Risk Assessment
    ├── Attack Tree
    └── Review / Survey
