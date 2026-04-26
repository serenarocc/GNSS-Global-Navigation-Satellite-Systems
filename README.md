# GNSS Vulnerability and Performance Analysis

This project is a study conducted at the **Politecnico di Torino** regarding the vulnerabilities of Global Navigation Satellite Systems (GNSS) and their management in real-world scenarios.

---

## Project Overview
The report explores how modern receivers calculate Position, Velocity, and Time (PVT) and their susceptibility to intentional attacks and environmental interference.

### Analyzed Scenarios:
* **Static**: Data collection performed under clear sky conditions.
* **Dynamic**: Measurements taken on board a train.
* **Spoofing**: Simulated attacks targeting a skyscraper.
* **Interference**: Tests conducted in the presence of DVB-T/FM antennas (Colle della Maddalena) and VOR-DME systems (Poirino).

---

## Main Results

### 1. Spoofing Vulnerabilities
The spoofing attack was successful in diverting the position reported by the device.
* **Detectability**: Without delay, the attack is detectable through sudden spikes in the satellites' relative velocity.
* **Delay Injection (1 ms)**: Injecting a common-mode delay causes an instantaneous jump in the receiver's clock bias of approximately 1 ms, which is equivalent to a 300 km pseudorange error.
* **Silent Desynchronization**: This mechanism leads to a silent desynchronization with respect to UTC time.

### 2. Electromagnetic Interference (EMI)
* **DVB-T/FM**: Intense electromagnetic fields (12 V/m) cause signal degradation and instability in the device's internal oscillators.
* **VOR-DME**: Intermittent transmissions from aeronautical systems cause sudden drops in the carrier-to-noise ratio ($C/N_0$).

---

##  Conclusions
The study highlights how spoofing represents a severe threat, especially for infrastructures that rely on high-precision GNSS timing. 

---

*Politecnico di Torino*.
