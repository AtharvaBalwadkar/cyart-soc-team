Week 1 Reports

This project demonstrates the implementation of a basic Security Operations Center (SOC) using open-source tools. A virtual lab environment was created to simulate real-world cybersecurity operations, including log collection, monitoring, alert generation, and incident response.

Key activities included analyzing system logs, detecting suspicious activities such as brute-force attacks, configuring custom alert rules, and visualizing security data through dashboards. The project follows industry-standard frameworks like MITRE ATT&CK and NIST Incident Response, ensuring a structured and practical approach to threat detection and handling.

Overall, this project provides hands-on experience in SOC operations, security monitoring, and incident management, making it a strong foundation for real-world cybersecurity roles.


1. Requirement Analysis & Planning
Understood SOC objectives such as threat detection, monitoring, and incident response
Identified key areas:
1.Log analysis
2.Security monitoring
3.Incident response workflow
Selected frameworks like MITRE ATT&CK and NIST IR Model

2. Lab Environment Setup
Created a virtual SOC lab environment
Tools used:
Wazuh (SIEM + XDR),
Elastic Stack (Kibana, Logstash),
Windows VM (as agent),
Configured log collection from endpoints,

3. Log Collection & Normalization
Implemented log pipeline:
Collected logs using Logstash / Fluentd,
Normalized logs into structured format (JSON),
Types of logs analyzed:
Windows Event Logs,
Syslog,
Web server logs,

4. Security Monitoring & Detection
Monitored logs for:
Failed login attempts (Event ID 4625)
Suspicious activities
Created dashboards in Kibana:
Top source IPs
Alert frequency

5.. Alert Rule Configuration
Developed detection rules such as:
Multiple failed login attempts within a time window,
Tested rules by simulating attacks:
Brute-force login attempts,
Validated alerts in Wazuh dashboard,

6. Incident Detection & Analysis
Followed SOC workflow:
Detection → Triage → Investigation → Response,
Correlated logs to identify attack patterns,
Used threat intelligence mapping (MITRE ATT&CK),

7. Incident Response Implementation
Applied IR lifecycle:
Preparation,
Identification,
Containment,
Eradication,
Recovery,
Simulated real-world scenarios (e.g., brute-force attack),

8. Documentation & Reporting
Documented events using structured format:
Timestamp,
Source IP,
Event ID,
Action taken,
Created:,
Incident reports
Dashboards screenshots
Findings summary
