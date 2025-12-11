🔍 Vulnerability Scanning Project

Performed on Kali Linux using OpenVAS & Nessus Essentials

📌 Overview

This repository documents the setup, execution, and findings of a vulnerability scanning project performed on Kali Linux.
The goal of this project is to understand how vulnerability scanners work, how to configure them, and how to analyze scan results to strengthen network security.


---

🧰 Tools Used

1. Kali Linux

Main operating system used for scanning and analysis.

2. OpenVAS (Greenbone Vulnerability Manager)

Open-source vulnerability scanner

Used to update NVTs (Network Vulnerability Tests)

Performed full network scans

🚀 What Was Done in This Project

1. Installed and Configured OpenVAS

Updated Greenbone Feed (NVT, SCAP, CERT)

Fixed update issues caused by low network speed (5 Mbps)

Resolved login/logout & session timeout issues

Verified gsad and gvmd services

Created:

Target

Scan Config

Task

Report

2. Performed Network Vulnerability Scan

Scanned full subnet:
192.168.1.0/24

Detected:

Open ports

Weak configurations

Outdated services

High/medium/low vulnerabilities

🧠 Learning Outcomes

Understanding vulnerability scanning lifecycle

Configuring OpenVAS and Nessus properly

Troubleshooting update and feed errors

Creating scan tasks and profiles

Reading and interpreting vulnerability reports

Identifying false positives and true positives

