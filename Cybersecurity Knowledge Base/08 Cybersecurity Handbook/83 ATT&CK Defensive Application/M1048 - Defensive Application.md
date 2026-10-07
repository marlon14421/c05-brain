---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1048"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1048: Application Isolation and Sandboxing — Defensive Application

## Source record

- [[01 ATT&CK/M1048 - Application Isolation and Sandboxing|M1048 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Application Isolation and Sandboxing refers to the technique of restricting the execution of code to a controlled and isolated environment (e.g., a virtual environment, container, or sandbox). This method prevents potentially malicious code from affecting the rest of the system or network by limiting access to sensitive resources and critical operations. The goal is to contain threats and minimize their impact. This mitigation can be implemented through the following measures: Browser Sandboxing: - Use Case: Implement browser sandboxing to isolate untrusted web content and prevent malicious web pages or scripts from accessing sensitive system resources or initiating unauthorized downloads. - Implementation: Use browsers with built-in sandboxing features (e.g., Google Chrome, Microsoft Edge) or deploy enhanced browser security frameworks that limit the execution scope of active content. Consider controls that monitor or restrict script-based file generation and downloads commonly abused in evasion techniques like HTML smuggling. Application Virtualization: - Use Case: Deploy critical or high-risk applications in a virtualized environment to ensure any compromise does not affect the host system. - Implementation: Use application virtualization platforms to run applications in isolated environments. Email Attachment Sandboxing: - Use Case: Route email attachments to a sandbox environment to detect and block malware before delivering emails to end-users. - Implementation: Integrate security solutions with sandbox capabilities to analyze email attachments. Endpoint Sandboxing: - Use Case: Run all downloaded files and applications in a restricted environment to monitor their behavior for malicious activity. - Implementation: Use endpoint protection tools for sandboxing at the endpoint level.

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
