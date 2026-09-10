# Defense Taxonomy for Autonomous Vehicles

This document summarises the defense taxonomy presented in the study:

Cybersecurity for Autonomous Vehicles: Review of Attacks and Defense  
Computers & Security, Volume 103, 2021, Article 102150.

The defense taxonomy was developed through a review of research on autonomous vehicle cybersecurity published between 2008 and 2019.

## Overview

Defense research was organised into three major categories:

1. Security Architectures for Autonomous Defense
2. Intrusion Detection Systems
3. Artificial Intelligence with Big Data

## 1. Security Architectures for Autonomous Defense

This category covers security mechanisms, architectures, and frameworks designed to protect autonomous vehicle systems and communications.

### 1.1 CAN/ECU Security

Research in this category focuses on protecting Electronic Control Units (ECUs) and Controller Area Network (CAN) communications.

The reviewed studies include approaches such as:

- Authentication mechanisms
- Message authentication codes
- Secure communication protocols
- ECU authentication
- CAN message protection
- Moving target defense
- Hardware security mechanisms

### 1.2 VANET Security

This category covers security mechanisms for Vehicular Ad Hoc Networks (VANETs) and vehicle-to-vehicle or vehicle-to-infrastructure communications.

The reviewed studies include:

- Secure session mechanisms
- Authentication protocols
- Group-key agreement
- Trust management
- Privacy-preserving communication
- Blockchain-based approaches

### 1.3 Security Design, Process and Framework

This category includes broader approaches to secure vehicle design and cybersecurity management.

Research reviewed in the study considered:

- Security-by-design
- Security frameworks
- Cross-layer security models
- Secure connected-car architectures
- Security management systems
- Automotive security processes

## 2. Intrusion Detection Systems

Intrusion Detection Systems (IDS) were identified as a major defense research area for autonomous and connected vehicles.

### 2.1 IDS for CAN

Research in this category focuses on detecting attacks within in-vehicle CAN networks.

The reviewed approaches include:

- Anomaly-based detection
- Timing-based detection
- Entropy-based detection
- Message-frequency analysis
- ECU fingerprinting
- Signal-characteristic analysis
- Firewall-assisted detection
- Message-sequence analysis

### 2.2 IDS for VANET

This category focuses on intrusion detection in vehicular communication networks.

The reviewed studies include:

- Distributed IDS architectures
- Collaborative IDS
- Sensor-based detection
- Regression-based approaches
- Hybrid detection models
- Intrusion response mechanisms

## 3. Artificial Intelligence with Big Data

The study identified an increasing use of artificial intelligence, machine learning, and big-data technologies for autonomous vehicle cybersecurity.

### 3.1 Machine Learning and Deep Learning

Research in this category applies data-driven methods to detect abnormal or malicious vehicle behaviour.

Approaches reviewed in the study include:

- Support Vector Machines
- Deep Neural Networks
- Long Short-Term Memory networks
- Hidden Markov Models
- Bayesian estimation
- Generative Adversarial Networks
- Deep Convolutional Neural Networks
- Statistical anomaly detection

### 3.2 Cloud and Big Data

This category includes cloud-assisted and large-scale data-driven security approaches.

The reviewed studies considered:

- Cloud-assisted malware detection
- Cloud-supported vehicular security
- Big-data-based security analysis
- Cloud-based authorization frameworks

## Taxonomy Structure

```text
Defense for Autonomous Vehicles
├── Security Architectures for Autonomous Defense
│   ├── CAN/ECU Security
│   ├── VANET Security
│   └── Security Design, Process and Framework
├── Intrusion Detection System
│   ├── IDS for CAN
│   └── IDS for VANET
└── Artificial Intelligence with Big Data
    ├── Machine Learning / Deep Learning
    └── Cloud / Big Data
