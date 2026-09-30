---
type: "Technique"
source: MITRE ATT&CK
id: "T1667"
source_url: "https://attack.mitre.org/techniques/T1667"
created: "2025-01-31"
modified: "2025-04-15"
---
# T1667: Email Bombing

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1667  
**Platforms:** Linux, Office Suite, Windows, macOS  
**Tactics:** impact

## Source description

Adversaries may flood targeted email addresses with an overwhelming volume of messages. This may bury legitimate emails in a flood of spam and disrupt business operations.(Citation: sophos-bombing)(Citation: krebs-email-bombing) An adversary may accomplish email bombing by leveraging an automated bot to register a targeted address for e-mail lists that do not validate new signups, such as online newsletters. The result can be a wave of thousands of e-mails that effectively overloads the victim’s inbox.(Citation: krebs-email-bombing)(Citation: hhs-email-bombing) By sending hundreds or thousands of e-mails in quick succession, adversaries may successfully divert attention away from and bury legitimate messages including security alerts, daily business processes like help desk tickets and client correspondence, or ongoing scams.(Citation: hhs-email-bombing) This behavior can also be used as a tool of harassment.(Citation: krebs-email-bombing) This behavior may be a precursor for [Spearphishing Voice](https://attack.mitre.org/techniques/T1566/004). For example, an adversary may email bomb a target and then follow up with a phone call to fraudulently offer assistance. This social engineering may lead to the use of [Remote Access Software](https://attack.mitre.org/techniques/T1663) to steal credentials, deploy ransomware, conduct [Financial Theft](https://attack.mitre.org/techniques/T1657)(Citation: sophos-bombing), or engage in other malicious activity.(Citation: rapid7-email-bombing)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1667](https://attack.mitre.org/techniques/T1667)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
