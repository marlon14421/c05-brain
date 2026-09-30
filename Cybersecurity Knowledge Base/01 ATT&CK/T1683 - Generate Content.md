---
type: "Technique"
source: MITRE ATT&CK
id: "T1683"
source_url: "https://attack.mitre.org/techniques/T1683"
created: "2026-03-25"
modified: "2026-05-12"
---
# T1683: Generate Content

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1683  
**Platforms:** PRE  
**Tactics:** resource-development

## Source description

Adversaries may create or generate content to support targeting and operations. This content may be used to establish personas, impersonate known individuals or organizations, and support [Social Engineering](https://attack.mitre.org/techniques/T1684), fraud, or influence activities. Written materials, audio, images, video, or other media may be developed and tailored to the target and objective.(Citation: IBM AI-Generated Content) Content development may occur prior to or during an operation. Adversaries may develop or generate content in-house, source it through third parties, or produce it using AI-assisted tools. Adversaries may use AI to research targets, develop pretexts, and better understand the organizations and individuals they intend to target or deceive prior to generating content (i.e., [Query Public AI Services](https://attack.mitre.org/techniques/T1682)); for obtaining access to AI tools used in content generation, see [Artificial Intelligence](https://attack.mitre.org/techniques/T1588/007). Content may be leveraged in support of techniques such as [Phishing](https://attack.mitre.org/techniques/T1566), [Phishing for Information](https://attack.mitre.org/techniques/T1598), [Social Engineering](https://attack.mitre.org/techniques/T1684), [Financial Theft](https://attack.mitre.org/techniques/T1657), or [Establish Accounts](https://attack.mitre.org/techniques/T1585). Generated or developed content does not include malicious code or scripts (i.e., [Develop Capabilities](https://attack.mitre.org/techniques/T1587) and [Artificial Intelligence](https://attack.mitre.org/techniques/T1588/007)).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1683](https://attack.mitre.org/techniques/T1683)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
