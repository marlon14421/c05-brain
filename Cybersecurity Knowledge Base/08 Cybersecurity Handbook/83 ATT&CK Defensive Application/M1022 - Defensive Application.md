---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1022"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1022: Restrict File and Directory Permissions — Defensive Application

## Source record

- [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Restricting file and directory permissions involves setting access controls at the file system level to limit which users, groups, or processes can read, write, or execute files. By configuring permissions appropriately, organizations can reduce the attack surface for adversaries seeking to access sensitive data, plant malicious code, or tamper with system files. Enforce Least Privilege Permissions: - Remove unnecessary write permissions on sensitive files and directories. - Use file ownership and groups to control access for specific roles. Example (Windows): Right-click the shared folder → Properties → Security tab → Adjust permissions for NTFS ACLs. Harden File Shares: - Disable anonymous access to shared folders. - Enforce NTFS permissions for shared folders on Windows. Example: Set permissions to restrict write access to critical files, such as system executables (e.g., `/bin` or `/sbin` on Linux). Use tools like `chown` and `chmod` to assign file ownership and limit access. On Linux, apply: `chmod 750 /etc/sensitive.conf` `chown root:admin /etc/sensitive.conf` File Integrity Monitoring (FIM): - Use tools like Tripwire, Wazuh, or OSSEC to monitor changes to critical file permissions. Audit File System Access: - Enable auditing to track permission changes or unauthorized access attempts. - Use auditd (Linux) or Event Viewer (Windows) to log activities. Restrict Startup Directories: - Configure permissions to prevent unauthorized writes to directories like `C:\ProgramData\Microsoft\Windows\Start Menu`. Example: Restrict write access to critical directories like `/etc/`, `/usr/local/`, and Windows directories such as `C:\Windows\System32`. - On Windows, use icacls to modify permissions: `icacls "C:\Windows\System32" /inheritance:r /grant:r SYSTEM:(OI)(CI)F` - On Linux, monitor permissions using tools like `lsattr` or `auditd`.

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
