---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0064"
source_url: "https://attack.mitre.org/datacomponents/DC0064"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0064: Command Execution

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0064  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Command Execution involves monitoring and capturing the execution of textual commands (including shell commands, cmdlets, and scripts) within an operating system or application. These commands may include arguments or parameters and are typically executed through interpreters such as `cmd.exe`, `bash`, `zsh`, `PowerShell`, or programmatic execution. Examples: - Windows Command Prompt - dir – Lists directory contents. - net user – Queries or manipulates user accounts. - tasklist – Lists running processes. - PowerShell - Get-Process – Retrieves processes running on a system. - Set-ExecutionPolicy – Changes PowerShell script execution policies. - Invoke-WebRequest – Downloads remote resources. - Linux Shell - ls – Lists files in a directory. - cat /etc/passwd – Reads the user accounts file. - curl http://malicious-site.com – Retrieves content from a malicious URL. - Container Environments - docker exec – Executes a command inside a running container. - kubectl exec – Runs commands in Kubernetes pods. - macOS Terminal - open – Opens files or URLs. - dscl . -list /Users – Lists all users on the system. - osascript -e – Executes AppleScript commands.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0064](https://attack.mitre.org/datacomponents/DC0064)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
