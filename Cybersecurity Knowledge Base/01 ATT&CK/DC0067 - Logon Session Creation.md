---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0067"
source_url: "https://attack.mitre.org/datacomponents/DC0067"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0067: Logon Session Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0067  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The successful establishment of a new user session following a successful authentication attempt. This typically signifies that a user has provided valid credentials or authentication tokens, and the system has initiated a session associated with that user account. This data is crucial for tracking authentication events and identifying potential unauthorized access. Examples: - Windows Systems - Event ID: 4624 - Logon Type: 2 (Interactive) or 10 (Remote Interactive via RDP). - Account Name: JohnDoe - Source Network Address: 192.168.1.100 - Authentication Package: NTLM - Linux Systems - /var/log/utmp or /var/log/wtmp: - Log format: login user [tty] from [source_ip] - User: jane - IP: 10.0.0.5 - Timestamp: 2024-12-28 08:30:00 - macOS Systems - /var/log/asl.log or unified logging framework: - Log: com.apple.securityd: Authentication succeeded for user 'admin' - Cloud Environments - Azure Sign-In Logs: - Activity: Sign-in successful - Client App: Browser - Location: Unknown (Country: X) - Google Workspace - Activity: Login - Event Type: successful_login - Source IP: 203.0.113.55

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0067](https://attack.mitre.org/datacomponents/DC0067)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
