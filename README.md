INCS870 – Mobile Threat Defense (MTD) & Integrated IT Management Project

Team: INCS870-FA25-Team02

Members: Nancy Niu, Daniel Gao, Ray Xian
Instructor: Dr. Zhida Li
Industry Partner: TGT Solutions
Semester: Fall 2025

1. Project Overview

This repository contains all deliverables, analyses, trial findings, governance documents, and presentation materials for the INCS870 Capstone Project in collaboration with TGT Solutions.

The project evaluates Mobile Threat Defense (MTD) technologies and integrated IT management solutions (RMM + MDM). It identifies service gaps for TGT and proposes a technical and business strategy for launching a new MTD offering.

2. Repository Contents
2.1 Market & Platform Analysis

Located in: /01_Market_Analysis/

A Comparative Analysis of Mobile MTD Service Offerings
Evaluation of major platforms including Intune, Cisco Meraki, NinjaOne, and market trends.

Why Clients Need MTD and IT Management
Analysis of enterprise needs: device security, compliance, unified operations, and risk reduction.

2.2 Business Case

Located in: /02_Business_Case/

Business Case for TGT Solutions to Offer Mobile Threat Defense (MTD) Services
Includes:

Market opportunity

Target clients

Revenue model (Basic / Standard / Advanced tiers)

TGT strategic advantages

Long-term business value

2.3 Technical Deliverables

Located in: /03_Technical_Deliverables/

Deliverable D – NinjaOne MDM Configuration & Agent Deployment
Step-by-step onboarding, configuration policies, and automation workflows.

Deliverable E – NinjaOne MDM Demonstration
Screenshots and explanations of key MDM functionalities.

NinjaOne Trial Findings (Excel)
Hands-on evaluation of NinjaOne’s strengths, limitations, and improvement opportunities.

2.4 Governance Framework

Located in: /04_Governance/

Deliverable F – Governance Process V2
Governance model for MTD & IT management operations:

Security roles and responsibilities

Policies and operational standards

Risk monitoring and compliance

Continuous improvement

2.5 Final Presentation

Located in: /05_Presentation/

INCS870 Project Final Presentation
Covers:

Market landscape

Service platform comparison

Governance structure

NinjaOne trial summary

Proposed architecture

Strategic recommendations for TGT

3. Key Project Findings
3.1 Market & Threat Landscape

Rapid increase in mobile cyberattacks due to BYOD and remote work.

Over 60% of enterprises rely on mobile-enabled workflows.

Mobile malware and phishing attacks grow annually.

Mobile-related security incidents have multi-million-dollar impacts.

3.2 Platform Evaluation Summary
Platform	Strengths	Weaknesses
Microsoft Intune	Strong compliance; excellent integration	Complex setup; higher cost
Cisco Meraki	Unified visibility across network + devices	Limited MTD security capabilities
NinjaOne MDM	Automation-focused; easy deployment	No mobile threat detection
CrowdStrike Falcon	Strong enterprise-grade protection	High pricing; not ideal for SMBs
3.3 Opportunity for TGT

TGT currently lacks:

Mobile security visibility

Automated compliance & patching

Unified device management

Mobile threat detection

→ An integrated RMM + MDM + MTD service directly fills this gap and significantly enhances TGT’s offerings.

3.4 Proposed Open-Source MTD Architecture

A lightweight, affordable, and customizable MTD solution based on:

FreeRASP Android agent
Detects root/jailbreak, MITM, tampering, hooking frameworks (e.g., Frida).

Secure Event Pipeline
HTTPS ingestion + Python backend processing.

Server-side analytics (Wazuh / ELK Stack)
Correlation, dashboards, alerts, threat scoring.

Designed for SMB clients who require security transparency and cost efficiency.

4. Recommendations for TGT
Strategic Recommendations

Adopt open-source MTD as core offering for SMBs.

Maintain NinjaOne for RMM + MDM operational capability.

Avoid high-cost, enterprise-oriented providers (e.g., CrowdStrike Falcon).

Operational Recommendations

Begin PoC with Android-based devices.

Build internal analytics and detection expertise.

Prepare SOPs, governance policies, and documentation for managed operations.

5. Repository Structure
INCS870-FA25-Team02/
│── README.md
│
│── 01_Market_Analysis/
│     ├── A Comparative Analysis of Mobile MTD Service Offerings.pdf
│     ├── Why Clients Need MTD and IT Management, and Why Choose TGT.pdf
│
│── 02_Business_Case/
│     ├── Business Case for TGT Solutions to Offer Mobile Threat Defense (MTD) Services.pdf
│
│── 03_Technical_Deliverables/
│     ├── Deliverable D - NinjaOne MDM Configuration and Agent Deployment.pdf
│     ├── Deliverable E - NinjaOne MDM Demonstration.pdf
│
│── 04_Governance/
│     ├── Deliverable F - Governance Process V2.pdf
│
│── 05_Presentation/
│     ├── INCS870 project report.pptx
│
│── 06_Trial_Findings/
│     ├── trial findings.xlsx
│
│── 07_References/
│     ├── (place external reports, citations, datasets here)
