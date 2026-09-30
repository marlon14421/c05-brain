---
type: "Technique"
source: MITRE ATT&CK
id: "T1684"
source_url: "https://attack.mitre.org/techniques/T1684"
created: "2026-04-14"
modified: "2026-05-12"
---
# T1684: Social Engineering

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1684  
**Platforms:** Linux, macOS, Office Suite, SaaS, Windows  
**Tactics:** stealth

## Source description

Adversaries may use social engineering techniques to influence users to take actions that result in unauthorized access, approval of changes, disclosure of sensitive information, or execution of adversary-supplied instructions (i.e., introduction of malicious payloads or software), while minimizing technical indicators. Adversaries may leverage trust-building methods across multiple channels (e.g., executive, vendor, or help desk scenarios, including AI-enabled voice interactions) to prompt user-authorized actions such as password resets, MFA changes, financial approvals, or the disclosure of sensitive information. Adversaries may also leverage common business communications and workflows such as email, collaboration platforms, voice communications, recruiting processes, help desk interactions, and SaaS consent mechanisms to make malicious requests appear routine and legitimate.(Citation: Proofpoint TA427 April 2024)(Citation: SE SentinelOne 2)(Citation: SE - Hackers Target Workday) Additionally, adversaries have persuaded victims to take actions through references of current events, harnessing relevant themes to the work role or the organizations mission. For example, adversaries may use scare tactics (i.e., threaten repercussions for non-compliance) or otherwise incite victims’ emotions in order to generate a sense of urgency to take action.(Citation: SE Proofpoint)(Citation: SE SentinelOne) This technique may include common social engineering patterns such as [Phishing](https://attack.mitre.org/techniques/T1566) and [Spearphishing Voice](https://attack.mitre.org/techniques/T1566/004), often supported by convincing and targeted narratives.(Citation: SE SentinelOne 2)(Citation: Fortinet Trends 25-26)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1684](https://attack.mitre.org/techniques/T1684)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
