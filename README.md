# GNSS Vulnerability and Performance Analysis

[cite_start]This project is a study conducted at the **Politecnico di Torino** regarding the vulnerabilities of Global Navigation Satellite Systems (GNSS) and their management in real-world scenarios[cite: 8, 9].

---

## 📋 Project Overview
[cite_start]The report explores how modern receivers calculate Position, Velocity, and Time (PVT) and their susceptibility to intentional attacks and environmental interference[cite: 16].

### Analyzed Scenarios:
* [cite_start]**Static**: Data collection performed under clear sky conditions[cite: 45].
* [cite_start]**Dynamic**: Measurements taken on board a train[cite: 81].
* [cite_start]**Spoofing**: Simulated attacks targeting a skyscraper[cite: 83].
* [cite_start]**Interference**: Tests conducted in the presence of DVB-T/FM antennas (Colle della Maddalena) and VOR-DME systems (Poirino)[cite: 87, 88].

---

## 🔍 Main Results

### 1. Spoofing Vulnerabilities
[cite_start]The spoofing attack was successful in diverting the position reported by the device[cite: 119].
* [cite_start]**Detectability**: Without delay, the attack is detectable through sudden spikes in the satellites' relative velocity[cite: 120, 128].
* [cite_start]**Delay Injection (1 ms)**: Injecting a common-mode delay causes an instantaneous jump in the receiver's clock bias of approximately 1 ms, which is equivalent to a 300 km pseudorange error[cite: 153, 155].
* [cite_start]**Silent Desynchronization**: This mechanism leads to a silent desynchronization with respect to UTC time[cite: 184].

### 2. Electromagnetic Interference (EMI)
* [cite_start]**DVB-T/FM**: Intense electromagnetic fields (12 V/m) cause signal degradation and instability in the device's internal oscillators[cite: 87, 251, 253].
* [cite_start]**VOR-DME**: Intermittent transmissions from aeronautical systems cause sudden drops in the carrier-to-noise ratio ($C/N_0$)[cite: 255].

---

## 📈 Conclusions
[cite_start]The study highlights how spoofing represents a severe threat, especially for infrastructures that rely on high-precision GNSS timing[cite: 219, 280]. 

---

[cite_start]*Politecnico di Torino*[cite: 8, 49].
