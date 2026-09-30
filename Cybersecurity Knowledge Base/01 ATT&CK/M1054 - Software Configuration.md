---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1054"
source_url: "https://attack.mitre.org/mitigations/M1054"
created: "2019-07-19"
modified: "2024-12-24"
---
# M1054: Software Configuration

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1054  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Software configuration refers to making security-focused adjustments to the settings of applications, middleware, databases, or other software to mitigate potential threats. These changes help reduce the attack surface, enforce best practices, and protect sensitive data. This mitigation can be implemented through the following measures: Conduct a Security Review of Application Settings: - Review the software documentation to identify recommended security configurations. - Compare default settings against organizational policies and compliance requirements. Implement Access Controls and Permissions: - Restrict access to sensitive features or data within the software. - Enforce least privilege principles for all roles and accounts interacting with the software. Enable Logging and Monitoring: - Configure detailed logging for key application events such as authentication failures, configuration changes, or unusual activity. - Integrate logs with a centralized monitoring solution, such as a SIEM. Update and Patch Software Regularly: - Ensure the software is kept up-to-date with the latest security patches to address known vulnerabilities. - Use automated patch management tools to streamline the update process. Disable Unnecessary Features or Services: - Turn off unused functionality or components that could introduce vulnerabilities, such as debugging interfaces or deprecated APIs. Test Configuration Changes: - Perform configuration changes in a staging environment before applying them in production. - Conduct regular audits to ensure that settings remain aligned with security policies. *Tools for Implementation* Configuration Management Tools: - Ansible: Automates configuration changes across multiple applications and environments. - Chef: Ensures consistent application settings through code-based configuration management. - Puppet: Automates software configurations and audits changes for compliance. Security Benchmarking Tools: - CIS-CAT: Provides benchmarks and audits for secure software configurations. - Aqua Security Trivy: Scans containerized applications for configuration issues. Vulnerability Management Solutions: - Nessus: Identifies misconfigurations and suggests corrective actions. Logging and Monitoring Tools: - Splunk: Aggregates and analyzes application logs to detect suspicious activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1054](https://attack.mitre.org/mitigations/M1054)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
