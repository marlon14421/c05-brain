---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1039"
source_url: "https://attack.mitre.org/mitigations/M1039"
created: "2019-06-11"
modified: "2024-12-11"
---
# M1039: Environment Variable Permissions

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1039  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Restrict the modification of environment variables to authorized users and processes by enforcing strict permissions and policies. This ensures the integrity of environment variables, preventing adversaries from abusing or altering them for malicious purposes. This mitigation can be implemented through the following measures: Restrict Write Access: - Use Case: Set file system-level permissions to restrict access to environment variable configuration files (e.g., `.bashrc`, `.bash_profile`, `.zshrc`, `systemd` service files). - Implementation: Configure `/etc/environment` or `/etc/profile` on Linux systems to only allow root or administrators to modify the file. Secure Access Controls: - Use Case: Limit access to environment variable settings in application deployment tools or CI/CD pipelines to authorized personnel. - Implementation: Use role-based access control (RBAC) in tools like Jenkins or GitLab to ensure only specific users can modify environment variables. Restrict Process Scope: - Use Case: Configure policies to ensure environment variables are only accessible to the processes they are explicitly intended for. - Implementation: Use containerized environments like Docker to isolate environment variables to specific containers and ensure they are not inherited by other processes. Audit Environment Variable Changes: - Use Case: Enable logging for changes to critical environment variables. - Implementation: Use `auditd` on Linux to monitor changes to files like `/etc/environment` or application-specific environment files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1039](https://attack.mitre.org/mitigations/M1039)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
