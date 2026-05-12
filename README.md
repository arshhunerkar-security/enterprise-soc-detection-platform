# Enterprise SOC Detection Platform

## Executive Summary

This project simulates an enterprise-grade Security Operations Center (SOC) environment designed to detect, investigate, and triage large-scale security events across authentication, endpoint, and system telemetry sources.

The platform ingests high-volume simulated security logs and applies correlation-based detection logic to identify brute-force authentication attempts, privilege escalation events, encoded PowerShell execution, suspicious process behavior, and attacker lateral movement.

---

## Objectives

- Simulate enterprise-scale security telemetry ingestion
- Detect malicious behavioral indicators
- Investigate suspicious activity using SIEM correlation searches
- Generate incident timelines
- Produce analyst investigation reports

---

## Technologies Used

- Splunk Enterprise
- Python
- Sysmon
- Sigma Detection Rules
- Security Event Correlation
