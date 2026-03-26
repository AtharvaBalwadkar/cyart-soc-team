SOC Advanced Operations Assignment (Threat Hunting, SOAR, Incident Response)

This project demonstrates a complete Security Operations Center (SOC) incident response workflow by simulating a real-world cyberattack and handling it using industry-standard tools and methodologies.

The attack was performed using Metasploit on a vulnerable Metasploitable2 machine and further validated using adversary emulation techniques. Detection was achieved through Wazuh SIEM with alerts mapped to the MITRE ATT&CK framework. The incident was triaged, contained by isolating the system, and mitigated by blocking the attacker’s IP using CrowdSec.

Due to compatibility limitations, TheHive was not deployed; however, escalation and SOAR processes were implemented manually following standard procedures. Post-incident analysis was conducted using Root Cause Analysis (RCA), and performance metrics such as MTTD and MTTR were evaluated using Elastic Security.

This project highlights practical SOC skills including threat detection, incident response, adversary emulation, and security analysis, aligning with real-world cybersecurity operations.

1. SOC Incident Response Lifecycle Methodology

The project follows a structured SOC workflow lifecycle, ensuring a systematic approach to handling security incidents:

Preparation: Setting up tools (Wazuh, CrowdSec, Metasploit, Caldera)
Identification: Detecting suspicious activity using SIEM alerts
Triage: Validating alerts and determining severity
Containment: Isolating affected systems and blocking attacker IP
Eradication: Removing vulnerabilities and stopping attack vectors
Recovery: Restoring system functionality securely
Lessons Learned: Conducting RCA and improving defenses

2. MITRE ATT&CK Framework Mapping

The project uses the MITRE ATT&CK Framework to map attacker behavior.

Technique used: T1210 – Exploitation of Remote Services
Helps in:
Understanding attacker tactics
Standardizing detection rules
Improving threat hunting

3. Threat Detection Methodology (SIEM-Based)

Detection is performed using Wazuh SIEM through:

Log collection from endpoints
Rule-based detection (Sigma rules)
Alert correlation
Mapping alerts to MITRE techniques

This ensures real-time visibility into suspicious activities.

4. Adversary Emulation Methodology

Attack simulation and adversary behavior replication were performed using:

Metasploit → Real vulnerability exploitation
MITRE Caldera → Emulation of attacker TTPs

This methodology validates detection and response capabilities against realistic attack scenarios.

5. Incident Response & Containment Methodology

A structured response approach was followed:

Identify affected system
Isolate compromised machine
Block malicious IP using CrowdSec
Verify containment via network testing

This minimizes damage and prevents lateral movement.

6. SOAR (Security Automation) Methodology

Although full automation via TheHive was not possible, the logic was implemented manually:

Alert → Analysis → Action workflow
Playbook-based response steps
Simulated automation for IP blocking

This demonstrates understanding of Security Orchestration, Automation, and Response (SOAR).

7. Root Cause Analysis (RCA) Methodology

The incident was analyzed using:

5 Whys Technique → Identify root cause step-by-step
Fishbone Diagram → Categorize contributing factors

This helps in preventing future incidents.

8. Security Metrics & Performance Measurement

Performance was evaluated using:

MTTD (Mean Time to Detect)
MTTR (Mean Time to Respond)
Dwell Time

Metrics were visualized using Elastic Security dashboards to measure SOC efficiency.

9. SANS Reporting Methodology

The final report follows SANS Incident Response format, including:

Executive Summary
Timeline
Root Cause Analysis
Recommendations

This ensures professional and industry-standard documentation.
