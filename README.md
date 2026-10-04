# Network Traffic Analysis & PCAP Investigation — Wireshark

## Project Overview

This project demonstrates a hands-on Security Operations Center (SOC) investigation of network traffic using Wireshark.

The investigation focuses on analyzing a real-world PCAP capture to identify suspicious network communication, investigate DNS activity, correlate domains with IP addresses, analyze HTTP traffic, examine HTTP POST requests, identify network indicators, and map observed behavior to the MITRE ATT&CK framework.

The investigation follows a practical Blue Team workflow:

PCAP  
↓  
Protocol Analysis  
↓  
Internal Host Identification  
↓  
DNS Investigation  
↓  
Domain/IP Correlation  
↓  
HTTP Investigation  
↓  
POST Payload Analysis  
↓  
IOC Identification  
↓  
MITRE ATT&CK Mapping  
↓  
SOC Assessment  
↓  
Investigation Report

---

## Objectives

The main objectives of this project were:

- Analyze a real-world PCAP file using Wireshark.
- Identify the primary internal host involved in suspicious activity.
- Investigate DNS queries and responses.
- Correlate suspicious domains with external IP addresses.
- Analyze HTTP GET and POST requests.
- Investigate suspicious HTTP hosts and URIs.
- Examine binary data transmitted through HTTP POST requests.
- Identify relevant network indicators.
- Build a timeline of observed network activity.
- Map supported activity to MITRE ATT&CK techniques.
- Produce a professional SOC investigation report.
- Demonstrate practical network investigation skills applicable to a SOC Analyst L1 role.

---

## Investigation Environment

### Operating System

Windows

### Analysis Tool

Wireshark

### Security Environment

The investigation was performed in a controlled environment.

The PCAP was analyzed without executing any malware or payloads contained in the training materials.

### PCAP File

```text
2026-09-11-traffic-analysis-exercise.pcap
