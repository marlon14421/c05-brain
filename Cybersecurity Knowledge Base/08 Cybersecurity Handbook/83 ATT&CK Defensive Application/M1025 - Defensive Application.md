---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1025"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1025: Privileged Process Integrity — Defensive Application

## Source record

- [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Privileged Process Integrity focuses on defending highly privileged processes (e.g., system services, antivirus, or authentication processes) from tampering, injection, or compromise by adversaries. These processes often interact with critical components, making them prime targets for techniques like code injection, privilege escalation, and process manipulation. This mitigation can be implemented through the following measures: Protected Process Mechanisms: - Enable RunAsPPL on Windows systems to protect LSASS and other critical processes. - Use registry modifications to enforce protected process settings: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa\RunAsPPL` Anti-Injection and Memory Protection: - Enable Control Flow Guard (CFG), DEP, and ASLR to protect against process memory tampering. - Deploy endpoint protection tools that actively block process injection attempts. Code Signing Validation: - Implement policies for Windows Defender Application Control (WDAC) or AppLocker to enforce execution of signed binaries. - Ensure critical processes are signed with valid certificates. Access Controls: - Use DACLs and MIC to limit which users and processes can interact with privileged processes. - Disable unnecessary debugging capabilities for high-privileged processes. Kernel-Level Protections: - Ensure Kernel Patch Protection (PatchGuard) is enabled on Windows systems. - Leverage SELinux or AppArmor on Linux to enforce kernel-level security policies. *Tools for Implementation* Protected Process Light (PPL): - RunAsPPL (Windows) - Windows Defender Credential Guard Code Integrity and Signing: - Windows Defender Application Control (WDAC) - AppLocker - SELinux/AppArmor (Linux) Memory Protection: - Control Flow Guard (CFG), Data Execution Prevention (DEP), ASLR Process Isolation/Sandboxing: - Firejail (Linux Sandbox) - Windows Sandbox - QEMU/KVM-based isolation Kernel Protection: - PatchGuard (Windows Kernel Patch Protection) - SELinux (Mandatory Access Control for Linux) - AppArmor

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
