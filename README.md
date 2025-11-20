# QualiemErp
![Status](https://img.shields.io/badge/Status-Phase%200%20(Initialization)-blue?style=for-the-badge&logo=github)
![Python](https://img.shields.io/badge/Python-3.12+-yellowgreen?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-MacOS%20%7C%20Windows-lightgrey?style=for-the-badge&logo=apple)
> **Next-gen Desktop ERP for manufacturing excellence.**  
> Bridging the gap between Quality Engineering, Shop Floor Operations, and Strategic Management.

---
##  Table of Contents
- [About The Project](#-about-the-project)
- [Core Philosophy](#-core-philosophy)
- [Key Modules (Planned)](#key-modules-planned)
  - [Quality Engineering](#1-quality-engineering-primary-module)
  - [Operations & Manufacturing](#2-operations--manufacturing)
  - [Human Resources](#3-human-resources-industrial)
  - [Purchasing / Service](#4-purchasing--service-future-extensions)
- [Architecture & Tech Stack](#-architecture--tech-stack)
- [Roadmap & Milestones](#roadmap--milestones)
  - [Phase 0: Foundation](#phase-0-foundation)
  - [Phase 1: The Core Engine](#phase-1-the-core-engine)
  - [Phase 2: Quality Engineering Module](#phase-2-quality-engineering-module)
  - [Phase 3: Desktop User Interface](#phase-3-desktop-user-interface)
  - [Phase 4: Operations & HR Expansion](#phase-4-operations--hr-expansion)
  - [Phase 5 – Release Prep](#phase-5--release-prep)
  - [Long-Term Vision](#long-term-vision)


## � About The Project

**QualiemErp** is a modular ERP ecosystem designed specifically for **electronics manufacturing**, **quality engineering**, and **industrial operations**.

Unlike traditional bloated ERP tools, Qualiem focuses on:

- **Operational Excellence**
- **Quality-First Architecture (Six Sigma, Root-Cause Thinking)**
- **Scalable Modular Systems**


---

## 🧭 Core Philosophy

- **Precision**  
  Data integrity and traceability from shop floor to management.
  
- **Modularity**  
  Enable only the modules needed. Keep the system lean.

- **Industrial Speed**  
  Native desktop performance for operators and engineers.

---

##  Key Modules (Planned)

### **1. Quality Engineering (Primary Module)**
- Real-time **OEE Calculation**  
- **Defect Tracking** with Pareto Analysis  
- **Inspection Records** (PCB, assemblies, final goods)  
- Root-Cause tools (5Why, 8D planned)  
- Calibration & Equipment Tracking
- 5S Tracking 

---

### **2. Operations & Manufacturing**
- Work Order System  
- Bill of Materials (BOM) linking  
- Routing / Workcenter definitions  
- Inventory tracking 

---

### **3. Human Resources (Industrial)**
- Employee Records  
- Certifications & Training Tracking  
- Shift Planning  
- Operator Performance  

---

### **4. Purchasing / Service (Future Extensions)**
- Supplier Records  
- Purchase Orders  
- RMA / Field Service Logging  

---

## 🛠 Architecture & Tech Stack

| Layer | Technology |
|------|------------|
| **Language** | Python 3.12+ |
| **Backend** | Modular Python Services |
| **ORM** | SQLAlchemy |
| **Database** | SQLite → PostgreSQL (Production ready) |
| **Desktop UI** | PySide6 / PyQt6 (planned) |
| **Data Analysis** | NumPy, Pandas |
| **Packaging** | PyInstaller (planned) |

---
---

##  Roadmap & Milestones


###  Phase 0: Foundation 

- [x] **Repository Initialization:** Git setup, License, README.
- [ ] **Project Architecture:** Setting up the folder structure .
- [ ] **Environment Setup:** Virtual environment (venv), Vasic documentation.
- [ ] **Database Design:** Initial ER Diagram for Core & Quality modules.

###  Phase 1: The Core Engine 

- [ ] **Database Implementation:** SQLite setup with SQLAlchemy ORM.
- [ ] **Core Models:** User System, role permission model
- [ ] **Base Services:** Authentication service
- [ ] **User System:** Authentication logic (Admin, Engineer, Operator roles).
- [ ] **Logging System:** Traceability for every action (Audit Log).

###  Phase 2: Quality Engineering Module 

- [ ] **OEE Logic:** Backend algorithms for Availability, Performance, Quality calculation.
- [ ] **Defect Tracking:** Standardization of defect codes (IPC standards).
- [ ] **Inspection Logs:** Input forms for daily production checks.
- [ ] **Pareto Analysis:** Data aggregation for root-cause analysis.
- [ ] **Calibration Management** Equipment Tracking, Calibration cycle management 

###  Phase 3: Desktop User Interface 

- [ ] **UI Framework:** PySide6 / PyQt6 integration.
- [ ] **Dashboard:** Modern, widget-based main screen with real-time OEE gauges.
- [ ] **Data Visualization:** Matplotlib/PyQtGraph integration for quality charts.
- [ ] **Dark/Light Mode:** Theme support for factory environments.

###  Phase 4: Operations & HR Expansion

- [ ] **HR Module:**
    - [ ] Shift Planning & Rotations.
    - [ ] Operator Certification Tracking (Skills Matrix).
- [ ] **Inventory Module:**
    - [ ] Raw material tracking (Electronic Components).
    - [ ] BOM (Bill of Materials) linking.
    - [ ] Low-stock Alerts.

### Phase 5:  Release Prep

- [ ] **Packaging:** Creating `.exe` and `.dmg` installers (PyInstaller).
- [ ] **Documentation:** User manuals and technical API docs.
- [ ] **Optimization:** Query optimization and load testing.

 ### Long-Term Vision
 
- AI-driven defect prediction
- Advanced Analytics Suite
- Certification Compliance Layer
- Automatic Reporting Engine
- Security & Authentication Enhancements

## 📞 Contact

- Ahmet Elindağ - [LinkedIn Profile](https://www.linkedin.com/in/ahmetelindag)
  
**Developed by Ahmet Elindağ**

