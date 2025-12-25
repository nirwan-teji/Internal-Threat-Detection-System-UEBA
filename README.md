# 🛡️ Internal Threat Detection System (UEBA)

**User & Entity Behavior Analytics (UEBA) for Insider Threat Detection**

This repository implements an end-to-end **Internal Threat Detection System** using **User and Entity Behavior Analytics (UEBA)** principles. The system ingests authentication and activity logs, extracts behavioral features, applies anomaly detection models, and exposes results through APIs and a web-based UI for investigation.

The goal of this project is to identify **insider threats, compromised accounts, and anomalous internal behavior** that traditional rule-based or signature-based security systems often miss.

---

## 📌 Motivation

Organizations face increasing risks from:
- Compromised internal accounts  
- Privilege misuse  
- Impossible travel and geo anomalies  
- Abnormal login behavior  
- New device or location usage  

UEBA focuses on **learning normal behavior patterns** and flagging deviations, enabling **early detection of internal threats**.

---

## 🚀 Features

- **User & Entity Profiling**
  - Behavioral baselining for users and devices
- **Anomaly Detection**
  - Statistical / ML-based scoring of suspicious behavior
- **Feature Engineering**
  - Time-based, geo-based, and device-based derived features
- **REST APIs**
  - Ingest logs, query scores, and retrieve alerts
- **Interactive Dashboard**
  - Visualize activity, alerts, and timelines
- **Modular Design**
  - Easy to extend with new features or detection models

---

## 🏗️ High-Level Architecture

