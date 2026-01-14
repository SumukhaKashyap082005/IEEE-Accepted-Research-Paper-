# Simulated Quantum Entangled Firewall for Preventing Insider Data Leakage

##  Overview
This repository contains the research paper **“Simulated Quantum Entangled Firewall for Preventing Insider Data Leakage”**, which proposes a hybrid cybersecurity framework that integrates simulated quantum entanglement with endpoint monitoring and human-in-the-loop approval mechanisms to mitigate insider threats.

The work focuses on preventing unauthorized data exfiltration—particularly via email—by combining deterministic quantum-inspired identity verification with real-time behavioral monitoring.



## Publication & Presentation
**Status:** Accepted for **Oral Presentation**

**Conference:**  
IEEE Sponsored **3rd International Conference on Advancements and Key Challenges in Green Energy and Computing (AKGEC 2026)**

**Venue:**  
Ajay Kumar Garg Engineering College, Ghaziabad, India

**Dates:**  
**26th February – 28th February 2026**



##  Abstract 
Insider data leakage remains a significant cybersecurity challenge that traditional firewalls struggle to detect. This paper presents a multi-layered firewall system that simulates quantum entanglement for email recipient verification, combined with endpoint activity monitoring and WhatsApp-based administrative approval.

Using Qiskit-based two-qubit quantum circuit simulations, the system generates deterministic entangled amplitude fingerprints derived from cryptographic hashes. Any deviation in sender–receiver identity results in immediate blocking. Additional safeguards include USB detection, screen capture monitoring, clipboard tracking, and cloud folder surveillance.

The proposed approach demonstrates strong spoof-resistance, deterministic verification, and low detection latency, making it suitable for enterprise and environmentally sensitive infrastructures.



##  System Highlights
- **Simulated Quantum Entanglement:**  
  Deterministic identity fingerprints using two-qubit entangled states with parameterized RY rotations.

- **Cryptographic Security:**  
  SHA-512 hashing and Fernet encryption ensure collision resistance and secure storage.

- **Endpoint Monitoring:**  
  Real-time detection of USB insertion, screenshot tools, clipboard usage, and cloud folder access.

- **Human-in-the-loop Approval:**  
  WhatsApp-based supervisory approval before sensitive data transmission.

- **Zero Trust Architecture:**  
  No user or process is trusted implicitly; every action is validated.



##  Technologies Used
- Python  
- Qiskit (Quantum Circuit Simulation)  
- Firebase Realtime Database  
- Tkinter (GUI)  
- psutil, watchdog (Endpoint Monitoring)  
- Vonage / WhatsApp API  
- SHA-512, Fernet Encryption  



##  Key Results
- Mean Time to Detect (MTTD): **100–200 microseconds**
- Strong spoof-resistance even for single-character email changes
- Deterministic, recipient-specific verification
- Near-zero collision probability for identity fingerprints

These results validate the feasibility of quantum-inspired security mechanisms without requiring physical quantum hardware.



## 🌍 Applications
- **Enterprise & Industrial Systems:**  
  IT, Telecom, Manufacturing, Healthcare, Government Data Centers

- **Environment & Energy Domains:**  
  Renewable Energy Enterprises, Climate Research Institutions, Space Agencies, Environmental Monitoring Systems

The system is particularly relevant where data leaks can impact environmental sustainability and energy efficiency.



##  Paper Access
The full paper is available in this repository as a PDF:

📘 *Simulated Quantum Entangled Firewall for Preventing Insider Data Leakage*  
(See uploaded PDF) 



## Future Work
- Extension to messaging platforms such as Slack, Telegram, and WhatsApp
- Webcam-based detection of physical data leakage
- Dynamic UI for managing entangled identities
- Integration with AI-based CCTV monitoring for external data leakage detection



##  Citation
If you reference this work, please cite it as:

> *Simulated Quantum Entangled Firewall for Preventing Insider Data Leakage*,  
> Accepted for Oral Presentation, IEEE AKGEC 2026.
