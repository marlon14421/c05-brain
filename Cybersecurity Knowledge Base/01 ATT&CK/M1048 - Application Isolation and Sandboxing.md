---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1048"
source_url: "https://attack.mitre.org/mitigations/M1048"
created: "2019-06-11"
modified: "2025-05-09"
---
# M1048: Application Isolation and Sandboxing

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1048  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Application Isolation and Sandboxing refers to the technique of restricting the execution of code to a controlled and isolated environment (e.g., a virtual environment, container, or sandbox). This method prevents potentially malicious code from affecting the rest of the system or network by limiting access to sensitive resources and critical operations. The goal is to contain threats and minimize their impact. This mitigation can be implemented through the following measures: Browser Sandboxing: - Use Case: Implement browser sandboxing to isolate untrusted web content and prevent malicious web pages or scripts from accessing sensitive system resources or initiating unauthorized downloads. - Implementation: Use browsers with built-in sandboxing features (e.g., Google Chrome, Microsoft Edge) or deploy enhanced browser security frameworks that limit the execution scope of active content. Consider controls that monitor or restrict script-based file generation and downloads commonly abused in evasion techniques like HTML smuggling. Application Virtualization: - Use Case: Deploy critical or high-risk applications in a virtualized environment to ensure any compromise does not affect the host system. - Implementation: Use application virtualization platforms to run applications in isolated environments. Email Attachment Sandboxing: - Use Case: Route email attachments to a sandbox environment to detect and block malware before delivering emails to end-users. - Implementation: Integrate security solutions with sandbox capabilities to analyze email attachments. Endpoint Sandboxing: - Use Case: Run all downloaded files and applications in a restricted environment to monitor their behavior for malicious activity. - Implementation: Use endpoint protection tools for sandboxing at the endpoint level.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1048](https://attack.mitre.org/mitigations/M1048)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
