# Sentinel Security

**Real time network monitoring with plain English, AI powered alerts for small businesses.**

---

## The Problem

51% of small businesses have zero cybersecurity. No monitoring. No alerts. No visibility into their own network. Most business owners have no idea what devices are connected, who is accessing their data, or whether their systems are compromised right now.

The tools that exist are built for enterprises with massive budgets and dedicated IT teams. Nothing exists for the barber shop, the restaurant, the local contractor, or the family business that has never had anyone look at their security before.

## What Sentinel Does

Sentinel Security sits on a small business network and does three things:

**Detects** — Watches network traffic in real time and identifies threats including unauthorized devices, port scanning, ARP spoofing, suspicious DNS queries, brute force attempts, and unusual data transfers.

**Explains** — Translates every detection into a plain English alert that any business owner can understand. No jargon. No technical dashboards. Just clear explanations of what happened and why it matters.

**Guides** — Provides AI powered, step by step remediation instructions specific to each alert. Tells the business owner exactly what to do, in the order they should do it, written so anyone can follow along regardless of technical background.

## Example Alert

```
ALERT — Unknown Device Connected to Your Network

WHAT HAPPENED:
A device we don't recognize just connected to your business Wi-Fi.
It is not on your approved device list.

WHY THIS MATTERS:
Unauthorized devices can intercept customer data, install malware,
or access your business files. This is how most small business
breaches begin.

WHAT TO DO RIGHT NOW:
1. Open your router admin page (usually 192.168.1.1 in your browser)
2. Look for the device at address 192.168.1.47
3. If you don't recognize it, block it immediately
4. Change your Wi-Fi password today
5. Reply to this alert if you need help

RISK LEVEL: HIGH
TIME TO FIX: 10 minutes
```

## Tech Stack

- Python
- Scapy (network packet capture and analysis)
- Flask (web dashboard)
- AI powered alert generation (plain English translation layer)
- Email and SMS alert delivery

## Detection Capabilities

- Unknown device detection and tracking
- Port scan identification
- ARP spoofing detection
- Suspicious DNS query monitoring
- Brute force attempt identification
- Unusual outbound data transfer alerts
- Network baseline anomaly detection

## Current Status

Actively in development. Currently building the core monitoring engine and plain English alert system. Onboarding pilot customers in Northern Virginia and the Greater Toronto Area.

## Free Network Assessment

If you run a small business and want to see what is actually on your network, we offer free security assessments. Reach out to get started.

## About

Sentinel Security was founded in 2026 with a simple mission: make cybersecurity accessible to every small business regardless of size or budget. Built by a cybersecurity competitor ranked in the top 0.5% globally in PicoCTF (Carnegie Mellon's international cybersecurity competition).

## Contact

For inquiries, partnerships, or free assessments reach out at oxajamal@gmail.com

## License

Proprietary. All rights reserved.
