---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1052"
source_url: "https://attack.mitre.org/mitigations/M1052"
created: "2019-06-11"
modified: "2024-12-24"
---
# M1052: User Account Control

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1052  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

User Account Control (UAC) is a security feature in Microsoft Windows that prevents unauthorized changes to the operating system. UAC prompts users to confirm or provide administrator credentials when an action requires elevated privileges. Proper configuration of UAC reduces the risk of privilege escalation attacks. This mitigation can be implemented through the following measures: Enable UAC Globally: - Ensure UAC is enabled through Group Policy by setting `User Account Control: Run all administrators in Admin Approval Mode` to `Enabled`. Require Credential Prompt: - Use Group Policy to configure UAC to prompt for administrative credentials instead of just confirmation (`User Account Control: Behavior of the elevation prompt`). Restrict Built-in Administrator Account: Set `Admin Approval Mode` for the built-in Administrator account to `Enabled` in Group Policy. Secure the UAC Prompt: - Configure UAC prompts to display on the secure desktop (`User Account Control: Switch to the secure desktop when prompting for elevation`). Prevent UAC Bypass: - Block untrusted applications from triggering UAC prompts by configuring `User Account Control: Only elevate executables that are signed and validated`. - Use EDR tools to detect and block known UAC bypass techniques. Monitor UAC-Related Events: - Use Windows Event Viewer to monitor for event ID 4688 (process creation) and look for suspicious processes attempting to invoke UAC elevation. *Tools for Implementation* Built-in Windows Tools: - Group Policy Editor: Configure UAC settings centrally for enterprise environments. - Registry Editor: Modify UAC-related settings directly, such as `EnableLUA` and `ConsentPromptBehaviorAdmin`. Endpoint Security Solutions: - Microsoft Defender for Endpoint: Detects and blocks UAC bypass techniques. - Sysmon: Logs process creations and monitors UAC elevation attempts for suspicious activity. Third-Party Security Tools: - Process Monitor (Sysinternals): Tracks real-time processes interacting with UAC. - EventSentry: Monitors Windows Event Logs for UAC-related alerts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1052](https://attack.mitre.org/mitigations/M1052)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
