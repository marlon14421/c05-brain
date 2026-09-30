---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1042"
source_url: "https://attack.mitre.org/mitigations/M1042"
created: "2019-06-11"
modified: "2026-05-12"
---
# M1042: Disable or Remove Feature or Program

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1042  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Disable or remove unnecessary and potentially vulnerable software, features, or services to reduce the attack surface and prevent abuse by adversaries. This involves identifying software or features that are no longer needed or that could be exploited and ensuring they are either removed or properly disabled. This mitigation can be implemented through the following measures: Remove Legacy Software: - Use Case: Disable or remove older versions of software that no longer receive updates or security patches (e.g., legacy Java, Adobe Flash). - Implementation: A company removes Flash Player from all employee systems after it has reached its end-of-life date. Disable Unused Features: - Use Case: Turn off unnecessary operating system features like SMBv1, Telnet, or RDP if they are not required. - Implementation: Disable SMBv1 in a Windows environment to mitigate vulnerabilities like EternalBlue. Control Applications Installed by Users: - Use Case: Prevent users from installing unauthorized software via group policies or other management tools. - Implementation: Block user installations of unauthorized file-sharing applications (e.g., BitTorrent clients) in an enterprise environment. Remove Unnecessary Services: - Use Case: Identify and disable unnecessary default services running on endpoints, servers, or network devices. - Implementation: Disable unused administrative shares (e.g., C$, ADMIN$) on workstations. Restrict Add-ons and Plugins: - Use Case: Remove or disable browser plugins and add-ons that are not needed for business purposes. - Implementation: Disable Java and ActiveX plugins in web browsers to prevent drive-by attacks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1042](https://attack.mitre.org/mitigations/M1042)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
