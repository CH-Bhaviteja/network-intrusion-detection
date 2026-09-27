# Network Intrusion Detection System (IDS)

A Python-based Network Intrusion Detection System that analyzes PCAP network traffic and detects suspicious network activity using rule-based detection.

## Project Overview

This project demonstrates a basic Intrusion Detection System that analyzes captured network packets and identifies indicators of suspicious behavior.

The system processes PCAP traffic, analyzes IP communication and destination ports, and generates security alerts when predefined detection thresholds are reached.

## Objectives

- Analyze network traffic from PCAP files
- Identify IP communication patterns
- Detect possible port scanning activity
- Detect unusually high packet volume
- Generate security alerts
- Produce a security analysis report

## Technologies Used

- Python
- Scapy
- TCP/IP
- PCAP
- Linux / Kali Linux

## How It Works

```text
PCAP Traffic
     ↓
Packet Analysis
     ↓
IP & Port Analysis
     ↓
Detection Rules
     ↓
Security Alerts
     ↓
Security Report
