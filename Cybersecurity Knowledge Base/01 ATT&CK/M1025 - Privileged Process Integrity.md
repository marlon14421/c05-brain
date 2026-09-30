---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1025"
source_url: "https://attack.mitre.org/mitigations/M1025"
created: "2019-06-06"
modified: "2024-12-18"
---
# M1025: Privileged Process Integrity

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1025  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Privileged Process Integrity focuses on defending highly privileged processes (e.g., system services, antivirus, or authentication processes) from tampering, injection, or compromise by adversaries. These processes often interact with critical components, making them prime targets for techniques like code injection, privilege escalation, and process manipulation. This mitigation can be implemented through the following measures: Protected Process Mechanisms: - Enable RunAsPPL on Windows systems to protect LSASS and other critical processes. - Use registry modifications to enforce protected process settings: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa\RunAsPPL` Anti-Injection and Memory Protection: - Enable Control Flow Guard (CFG), DEP, and ASLR to protect against process memory tampering. - Deploy endpoint protection tools that actively block process injection attempts. Code Signing Validation: - Implement policies for Windows Defender Application Control (WDAC) or AppLocker to enforce execution of signed binaries. - Ensure critical processes are signed with valid certificates. Access Controls: - Use DACLs and MIC to limit which users and processes can interact with privileged processes. - Disable unnecessary debugging capabilities for high-privileged processes. Kernel-Level Protections: - Ensure Kernel Patch Protection (PatchGuard) is enabled on Windows systems. - Leverage SELinux or AppArmor on Linux to enforce kernel-level security policies. *Tools for Implementation* Protected Process Light (PPL): - RunAsPPL (Windows) - Windows Defender Credential Guard Code Integrity and Signing: - Windows Defender Application Control (WDAC) - AppLocker - SELinux/AppArmor (Linux) Memory Protection: - Control Flow Guard (CFG), Data Execution Prevention (DEP), ASLR Process Isolation/Sandboxing: - Firejail (Linux Sandbox) - Windows Sandbox - QEMU/KVM-based isolation Kernel Protection: - PatchGuard (Windows Kernel Patch Protection) - SELinux (Mandatory Access Control for Linux) - AppArmor

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1025](https://attack.mitre.org/mitigations/M1025)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
