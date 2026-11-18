# Windows Failed Login Monitoring & Investigation

## Project Overview
This project demonstrates a hands-on investigation of Windows Security Logs to understand failed authentication attempts using Windows Event Viewer.

The investigation focuses on Windows Security Event ID 4625 and examines authentication-related information to understand how failed logon events can be analyzed during security monitoring.

## Objectives
- Understand Windows failed logon events.
- Analyze Event ID 4625.
- Examine authentication and process-related information.
- Identify relevant event fields and potential indicators.
- Document investigation findings and limitations.

## Tools & Technologies
- Windows 11
- Windows Event Viewer
- Windows Security Logs
- Windows Event XML

## Investigation Details

**Event ID:** 4625  
**Event Type:** Failed Logon  
**Logon Type:** 2 – Interactive  
**Authentication Package:** Negotiate  
**Source IP:** 127.0.0.1 (Loopback)

## Key Findings
- Examined a Windows Security Event ID 4625.
- Identified a failed local interactive logon event.
- Observed that the target account was not identified in the event.
- Analyzed the recorded logon process and associated process name.
- Reviewed the authentication failure status and substatus.
- Documented findings without assuming malicious activity.

## Evidence
Screenshots of the Event Viewer General tab and XML View are included in this repository.

## Project Structure
- `Investigation_01.txt` – Investigation report
- `Evidence_01_Event_Overview.png` – Event overview
- `Evidence_02_Event_XML.png` – XML event details

## Key Learning Outcomes
- Windows Security Event Analysis
- Authentication Monitoring
- Log Analysis
- Basic Incident Investigation
- Security Documentation

## Conclusion
This project provided practical exposure to Windows Security Event analysis and the investigation of failed authentication attempts. It demonstrates the importance of examining event evidence, identifying relevant fields and documenting findings before drawing security conclusions.

*This is a beginner-level, independently performed cybersecurity investigation project.*
