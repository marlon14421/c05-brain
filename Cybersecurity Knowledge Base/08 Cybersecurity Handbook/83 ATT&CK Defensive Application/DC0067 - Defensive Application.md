---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0067"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0067: Logon Session Creation — Defensive Application

## Source record

- [[01 ATT&CK/DC0067 - Logon Session Creation|DC0067 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The successful establishment of a new user session following a successful authentication attempt. This typically signifies that a user has provided valid credentials or authentication tokens, and the system has initiated a session associated with that user account. This data is crucial for tracking authentication events and identifying potential unauthorized access. Examples: - Windows Systems - Event ID: 4624 - Logon Type: 2 (Interactive) or 10 (Remote Interactive via RDP). - Account Name: JohnDoe - Source Network Address: 192.168.1.100 - Authentication Package: NTLM - Linux Systems - /var/log/utmp or /var/log/wtmp: - Log format: login user [tty] from [source_ip] - User: jane - IP: 10.0.0.5 - Timestamp: 2024-12-28 08:30:00 - macOS Systems - /var/log/asl.log or unified logging framework: - Log: com.apple.securityd: Authentication succeeded for user 'admin' - Cloud Environments - Azure Sign-In Logs: - Activity: Sign-in successful - Client App: Browser - Location: Unknown (Country: X) - Google Workspace - Activity: Login - Event Type: successful_login - Source IP: 203.0.113.55

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
