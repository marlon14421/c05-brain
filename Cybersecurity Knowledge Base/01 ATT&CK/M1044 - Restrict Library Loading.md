---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1044"
source_url: "https://attack.mitre.org/mitigations/M1044"
created: "2019-06-11"
modified: "2024-12-18"
---
# M1044: Restrict Library Loading

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1044  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Restricting library loading involves implementing security controls to ensure that only trusted and verified libraries (DLLs, shared objects, etc.) are loaded into processes. Adversaries often abuse Dynamic-Link Library (DLL) Injection, DLL Search Order Hijacking, or LD_PRELOAD mechanisms to execute malicious code by forcing the operating system to load untrusted libraries. This mitigation can be implemented through the following measures: Enforce Safe Library Loading Practices: - Enable `SafeDLLSearchMode` on Windows. - Restrict `LD_PRELOAD` and `LD_LIBRARY_PATH` usage on Linux systems. Code Signing Enforcement: - Require digital signatures for all libraries loaded into processes. - Use tools like Signtool, and WDAC to enforce signed DLL execution. Environment Hardening: - Secure library paths and directories to prevent adversaries from placing rogue libraries. - Monitor user-writable directories and system configurations for unauthorized changes. Audit and Monitor Library Loading: - Enable `Sysmon` on Windows to monitor for suspicious library loads. - Use `auditd` on Linux to monitor shared library paths and configuration file changes. Use Application Control Solutions: - Implement AppLocker, WDAC, or SELinux to allow only trusted libraries. *Tools for Implementation* Windows-Specific Tools: - AppLocker: Application whitelisting for DLLs. - Windows Defender Application Control (WDAC): Restrict unauthorized library execution. - Signtool: Verify and enforce code signing. - Sysmon: Monitor DLL load events (Event ID 7). Linux-Specific Tools: - auditd: Monitor changes to library paths and critical files. - SELinux/AppArmor: Define policies to restrict library loading. - ldconfig and chattr: Secure LD configuration files and prevent unauthorized modifications. Cross-Platform Solutions: - Wazuh or OSSEC: File integrity monitoring for library changes. - Tripwire: Detect and alert on unauthorized library modifications.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1044](https://attack.mitre.org/mitigations/M1044)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
