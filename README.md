# SOC-Analyst-Home-Lab-
Splunk-Based SOC Analyst Home Lab: A hands-on enterprise security monitoring lab built with Splunk Enterprise and Universal Forwarders. Ingests Windows and Ubuntu telemetry, features custom SPL detection rules, and applies MITRE ATT&amp;CK mapping for threat investigation.
Splunk-Based SOC Analyst Home Lab

Project Description
The Splunk-Based SOC Analyst Home Lab is a hands-on, enterprise-grade Security Operations Center (SOC) simulation designed to build, configure, and operate a centralized security monitoring infrastructure. This project mimics real-world Blue Team operations by ingesting, parsing, and analyzing security telemetry from multi-platform endpoints (Windows and Ubuntu Linux) using Splunk Enterprise and the Splunk Universal Forwarder.

Throughout this project, security events are actively monitored, custom threat-detection queries are written using Splunk Processing Language (SPL), alerts are mapped to the MITRE ATT&CK framework, and full incident response investigations are conducted and documented.

Key Objectives
Centralized Log Ingestion: Deploy and configure a central Splunk SIEM server on Ubuntu Linux alongside Universal Forwarders to securely aggregate endpoint telemetry.

Endpoint Telemetry & Monitoring: Capture crucial Windows security logs and Ubuntu system/authentication events to establish complete visibility across the environment.

Threat Detection & SPL Querying: Develop custom detection rules and advanced SPL queries to isolate malicious behaviors, unauthorized access attempts, and system anomalies.

Incident Response & Triage: Investigate simulated security incidents, analyze indicators of compromise (IoCs), map findings to the MITRE ATT&CK adversary tactics matrix, and author formal incident reports.

SOC Visualization: Design centralized dashboards to monitor real-time security events, log source health, and alert triggers.

Technology Stack
SIEM / Log Management: Splunk Enterprise (Hosted on Ubuntu Linux)

Endpoint Agents: Splunk Universal Forwarder

Monitored Endpoints: Windows PC / Server & Ubuntu Linux

Query Language: Splunk Processing Language (SPL)

Threat Framework: MITRE ATT&CK

Project Architecture & Workflow
Data Generation: Endpoints generate native operating system logs (e.g., Windows Security logs, PowerShell activity, Linux authentication logs).

Data Forwarding: The Splunk Universal Forwarder securely streams logs to the central Ubuntu SIEM server over designated network ports (9997).

Indexing & Parsing: Splunk ingests, indexes, and normalizes the log data for fast, searchable structuring.

Analysis & Detection: Analysts write targeted SPL queries to spot suspicious activities, run threat hunting tasks, and validate security alerts.

Reporting & Documentation: Findings are classified using MITRE ATT&CK and formatted into professional incident response write-ups.
