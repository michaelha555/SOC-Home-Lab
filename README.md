# SOC Home Lab

A hands-on cybersecurity portfolio focused on SOC fundamentals, Windows security monitoring, log analysis, and incident investigation.

## About This Lab

This repository documents practical cybersecurity exercises completed in a personal virtual lab environment.

The goal is to develop hands-on skills in identifying, investigating, and documenting security events.

## Project 01 — Windows Authentication Log Analysis

**Environment:** Windows 10 Virtual Machine (Oracle VirtualBox)

**Tools:** Windows Event Viewer, Windows Security Logs, XML/XPath Filtering

### Objective

Investigate failed Windows authentication attempts and determine whether they were followed by a successful logon.

### Investigation

- Enabled Windows logon auditing.
- Generated controlled failed and successful authentication attempts.
- Analyzed Event ID 4625 (Failed Logon) and Event ID 4624 (Successful Logon).
- Identified Logon Type 2 (Interactive Logon).
- Investigated Status 0xC000006D and Sub Status 0xC000006A.
- Documented the authentication sequence with supporting screenshots.

### Findings

Two failed logon events were observed at 12:08:01 and 12:08:03, followed by a successful logon at 12:08:05.

The failed attempts were associated with incorrect passwords. The activity was intentionally generated in an authorized lab environment and was not classified as a confirmed brute-force attack.

### Skills Practiced

- Windows Security Event Log analysis
- Authentication event investigation
- XML/XPath event filtering
- Security incident documentation
- Evidence-based investigation

## Disclaimer

All activities were performed in a controlled, authorized personal lab environment. Screenshots are redacted to protect identifying information.
