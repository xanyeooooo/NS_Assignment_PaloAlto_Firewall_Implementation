# NS_Assignment_PaloAlto_Firewall_Implementation  
**Network Security Academic Assignment**

> ⚠️ **Disclaimer**  
> This project is an **academic assignment conducted in a controlled lab environment** for a Network Security module.  
> All network designs, IP addresses, systems, and scenarios are **simulated and authorised for educational purposes only**.  
> This repository does **not** represent or target any real-world organisation or production network.

---

## 📘 Project Overview

This repository documents a **network security implementation and assessment** focused on the deployment and configuration of a **Palo Alto Next-Generation Firewall (NGFW)** within a simulated enterprise network.

The assignment evaluates how perimeter and internal network security controls can be designed to protect organisational assets, enforce access control, and detect malicious activity. Emphasis is placed on **defensive security**, proper firewall policy design, and secure network architecture.

---

## 🎯 Objectives

- Design a secure enterprise network using a Palo Alto NGFW  
- Implement firewall policies based on least privilege  
- Control and monitor traffic between internal network zones  
- Demonstrate how misconfigurations may expose the network  
- Propose mitigation strategies to strengthen security posture  

---

## 🖥️ Simulated Network Environment

- **Network Type**: Internal enterprise LAN (private IP addressing)  
- **Core Components**:
  - Palo Alto Next-Generation Firewall
  - Internal user network
  - Server network segment
  - External/Internet-facing zone
- **Addressing**:
  - All IP addresses fall within **RFC 1918 private address space**
- **Environment**:
  - Fully virtualised lab setup
  - No connection to real production systems

---

## 🔐 Palo Alto Firewall Implementation

The Palo Alto firewall was configured to provide layered security through:

- **Zone-Based Security Policies**
  - Segmentation between user, server, and external zones
- **Security Rules**
  - Allow and deny rules based on application, user, and service
- **Application Awareness (App-ID)**
  - Traffic inspection beyond port-based filtering
- **Threat Prevention**
  - Protection against known exploits and malicious traffic
- **Logging and Monitoring**
  - Traffic logs for visibility and incident detection

---

## 🔍 Security Evaluation Areas

### Network Segmentation
- Enforcement of trust boundaries
- Reduced lateral movement risk

### Access Control
- Restrictive inbound and outbound policies
- Principle of Least Privilege (PoLP)

### Traffic Visibility
- Application-based traffic inspection
- Detection of unauthorised or suspicious activity

### Monitoring & Detection
- Log analysis for anomaly detection
- Auditability of security events

---

## 🛡️ Key Findings (High-Level)

The assessment highlighted:
- The effectiveness of NGFWs in enforcing granular security policies  
- The importance of proper zone segmentation  
- Risks introduced by overly permissive firewall rules  
- The need for continuous monitoring and policy review  

No live vulnerabilities or sensitive configurations are disclosed.

---

## 🔐 Defensive Recommendations

- Enforce strict zone-based firewall policies  
- Regularly review and audit firewall rules  
- Enable full logging for critical traffic flows  
- Apply least privilege to all network access  
- Perform periodic security assessments and updates  

---

## 📂 Repository Contents

- 📄 Assignment documentation and explanations  
- 📊 Network architecture diagrams  
- 🔐 Firewall policy descriptions  
- 🛡️ Security analysis and recommendations  

---

## 📜 Ethical Statement

This work adheres to ethical cybersecurity principles:
- Conducted only on authorised lab systems  
- Intended solely for education and defence  
- Demonstrates secure design rather than offensive exploitation  

---

## 📌 Key Learning Outcomes

- Practical experience with Palo Alto NGFW concepts  
- Understanding of enterprise firewall policy design  
- Network segmentation and access control strategies  
- Defensive mindset in network security implementation  

---
