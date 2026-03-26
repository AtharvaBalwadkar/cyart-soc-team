SOC Week 2 Assignment
Alert Management and Incident Response

This project demonstrates a complete Security Operations Center (SOC) workflow, covering alert management, incident classification, triage, and response.

The implementation combines theoretical knowledge with practical simulation, where real-world attack scenarios were generated and handled using industry-standard tools.

Key highlights:

1.Prioritized alerts using CVSS-based risk scoring
2.Classified incidents using MITRE ATT&CK framework
3.Followed NIST incident response lifecycle
4.Performed alert triage and IOC validation using threat intelligence platforms
5.Simulated attacks using Metasploit and monitored via Wazuh
6.Executed incident response actions including containment and remediation
7.Preserved forensic evidence with proper chain-of-custody procedures

This project provides a hands-on understanding of SOC operations, replicating how security teams detect, analyze, and respond to cyber threats in real time.

Methodologies Used (for Report)

1. Risk-Based Alert Prioritization

The report follows a risk-based methodology using:

1.CVSS (Common Vulnerability Scoring System) to evaluate severity
2.Asset criticality (production vs test systems)
3.Threat likelihood & business impact

This ensures alerts are prioritized as Critical, High, Medium, Low, enabling efficient SOC decision-making.

2. Standardized Incident Classification

Incidents were classified using globally recognized frameworks:

1.MITRE ATT&CK → Mapping tactics & techniques (e.g., T1566 – Phishing)
2.VERIS Framework → Event recording & sharing

This methodology improves consistency and investigation accuracy.

3. NIST-Based Incident Response Lifecycle

The project follows the National Institute of Standards and Technology (NIST SP 800-61) framework:

1.Preparation
2.Identification
3.Containment
4.Eradication
5.Recovery
6.Lessons Learned

This ensures a structured and industry-standard response process.

4. Alert Triage & Threat Intelligence Correlation

Alerts were analyzed using Wazuh SIEM
Indicators of Compromise (IOCs) validated via:
AlienVault OTX,
VirusTotal,
False positives were filtered using correlation techniques

5. Practical SOC Simulation Approach

A hands-on methodology was used:

1.Attack simulation via Metasploit
2.Detection using Wazuh
3.Response & blocking via CrowdSec

This replicates a real-world SOC workflow (Alert → Triage → Response).

6. Evidence Handling & Forensics Methodology

Evidence collected using:
Velociraptor,
FTK Imager,
Maintained chain of custody
Used hashing (SHA-256) to ensure integrity

7. Documentation & Reporting Standards

Incident reports structured using SANS templates
Included:
Executive Summary
Timeline
Impact Analysis
Recommendations

This ensures clear communication for both technical & non-technical stakeholders.
