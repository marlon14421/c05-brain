---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1056"
source_url: "https://attack.mitre.org/mitigations/M1056"
created: "2020-10-19"
modified: "2026-05-12"
---
# M1056: Pre-compromise

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1056  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Pre-compromise mitigations involve proactive measures and defenses implemented to prevent adversaries from successfully identifying and exploiting weaknesses during the Reconnaissance and Resource Development phases of an attack. These activities focus on reducing an organization's attack surface, identify adversarial preparation efforts, and increase the difficulty for attackers to conduct successful operations. This mitigation can be implemented through the following measures: Limit Information Exposure: - Regularly audit and sanitize publicly available data, including job posts, websites, and social media. - Use tools like OSINT monitoring platforms (e.g., SpiderFoot, Recon-ng) to identify leaked information. Protect Domain and DNS Infrastructure: - Enable DNSSEC and use WHOIS privacy protection. - Monitor for domain hijacking or lookalike domains using services like RiskIQ or DomainTools. External Monitoring: - Use tools like Shodan, Censys to monitor your external attack surface. - Deploy external vulnerability scanners to proactively address weaknesses. Threat Intelligence: - Leverage platforms like MISP, Recorded Future, or Anomali to track adversarial infrastructure, tools, and activity. Content and Email Protections: - Use email security solutions like Proofpoint, Microsoft Defender for Office 365, or Mimecast. - Enforce SPF/DKIM/DMARC policies to protect against email spoofing. Training and Awareness: - Educate employees on identifying phishing attempts, securing their social media, and avoiding information leaks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1056](https://attack.mitre.org/mitigations/M1056)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
