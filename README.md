# Wazuh SOC Monitoring Lab

## Overview

Wazuh SOC Monitoring Lab is a home lab project focused on security monitoring, alert triage, and incident investigation using Wazuh SIEM/XDR and Sysmon.

The objective of this project is to simulate common security events in a controlled Windows environment, collect telemetry through Sysmon, monitor alerts with Wazuh, and perform investigations using a SOC Analyst workflow.

This repository documents the complete setup process, investigation methodology, evidence collection, and MITRE ATT&CK mapping for each scenario.

---

## Objectives

* Learn Wazuh SIEM/XDR fundamentals
* Monitor Windows security events
* Collect endpoint telemetry with Sysmon
* Investigate security alerts
* Practice SOC Tier 1 workflows
* Map attacker behavior to MITRE ATT&CK
* Build a practical Blue Team portfolio

---

## Lab Architecture

Windows Endpoint

↓

Sysmon

↓

Wazuh Agent

↓

Wazuh Manager

↓

Wazuh Dashboard

↓

Alert Investigation

---

## Technologies Used

* Wazuh
* Sysmon
* Docker
* Windows
* Git
* GitHub
* MITRE ATT&CK

---

## Investigation Scenarios

### Scenario 01 – PowerShell Obfuscation

Status: Planned

Focus:

* PowerShell execution monitoring
* Sysmon Event Analysis
* Wazuh alert investigation

### Scenario 02 – Brute Force Authentication Failures

Status: Planned

Focus:

* Windows Event ID 4625
* Authentication monitoring
* Alert triage

### Scenario 03 – Scheduled Task Persistence

Status: Planned

Focus:

* Persistence detection
* Windows Scheduled Tasks
* MITRE ATT&CK mapping

### Scenario 04 – SMB Authentication Failures

Status: Planned

Focus:

* SMB monitoring
* Authentication analysis
* Security investigation

---

## Repository Structure

```text
docs/
scenarios/
scripts/
```

---

## Current Progress

* [x] Repository created
* [x] Documentation structure created
* [ ] Wazuh deployment
* [ ] Sysmon deployment
* [ ] Endpoint enrollment
* [ ] Scenario 01
* [ ] Scenario 02
* [ ] Scenario 03
* [ ] Scenario 04

---

## Disclaimer

This project is intended exclusively for educational purposes, defensive security training, and cybersecurity portfolio development within controlled lab environments.
