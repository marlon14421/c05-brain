---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0064"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0064: Command Execution — Defensive Application

## Source record

- [[01 ATT&CK/DC0064 - Command Execution|DC0064 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Command Execution involves monitoring and capturing the execution of textual commands (including shell commands, cmdlets, and scripts) within an operating system or application. These commands may include arguments or parameters and are typically executed through interpreters such as `cmd.exe`, `bash`, `zsh`, `PowerShell`, or programmatic execution. Examples: - Windows Command Prompt - dir – Lists directory contents. - net user – Queries or manipulates user accounts. - tasklist – Lists running processes. - PowerShell - Get-Process – Retrieves processes running on a system. - Set-ExecutionPolicy – Changes PowerShell script execution policies. - Invoke-WebRequest – Downloads remote resources. - Linux Shell - ls – Lists files in a directory. - cat /etc/passwd – Reads the user accounts file. - curl http://malicious-site.com – Retrieves content from a malicious URL. - Container Environments - docker exec – Executes a command inside a running container. - kubectl exec – Runs commands in Kubernetes pods. - macOS Terminal - open – Opens files or URLs. - dscl . -list /Users – Lists all users on the system. - osascript -e – Executes AppleScript commands.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
