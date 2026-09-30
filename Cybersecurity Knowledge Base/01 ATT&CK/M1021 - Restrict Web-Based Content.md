---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1021"
source_url: "https://attack.mitre.org/mitigations/M1021"
created: "2019-06-06"
modified: "2024-12-24"
---
# M1021: Restrict Web-Based Content

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1021  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Restricting web-based content involves enforcing policies and technologies that limit access to potentially malicious websites, unsafe downloads, and unauthorized browser behaviors. This can include URL filtering, download restrictions, script blocking, and extension control to protect against exploitation, phishing, and malware delivery. This mitigation can be implemented through the following measures: Deploy Web Proxy Filtering: - Use solutions to filter web traffic based on categories, reputation, and content types. - Enforce policies that block unsafe websites or file types at the gateway level. Enable DNS-Based Filtering: - Implement tools to restrict access to domains associated with malware or phishing campaigns. - Use public DNS filtering services to enhance protection. Enforce Content Security Policies (CSP): - Configure CSP headers on internal and external web applications to restrict script execution, iframe embedding, and cross-origin requests. Control Browser Features: - Disable unapproved browser features like automatic downloads, developer tools, or unsafe scripting. - Enforce policies through tools like Group Policy Management to control browser settings. Monitor and Alert on Web-Based Threats: - Use SIEM tools to collect and analyze web proxy logs for signs of anomalous or malicious activity. - Configure alerts for access attempts to blocked domains or repeated file download failures.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1021](https://attack.mitre.org/mitigations/M1021)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
