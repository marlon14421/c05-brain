---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0093"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0093: Certificate Registration — Defensive Application

## Source record

- [[01 ATT&CK/DC0093 - Certificate Registration|DC0093 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Certificate Registration refers to the collection and analysis of information about digital certificates, including current, revoked, and expired certificates. Sources such as Certificate Transparency logs and other public resources provide visibility into certificates issued for specific domains or organizations. Monitoring certificate registrations can help identify potential misuse, such as unauthorized certificates or signs of adversary reconnaissance. Examples: - Certificate Transparency Logs: These logs record the issuance of SSL/TLS certificates by trusted Certificate Authorities (CAs). - Revoked Certificates: Information about certificates that have been invalidated before their expiration date. - Expired Certificates: Reports of expired certificates for a domain, which may indicate lax security practices or opportunities for adversaries to exploit expired credentials. - Domain Monitoring for Certificates: Maps SSL/TLS certificates to domains and subdomains, helping to identify any rogue certificates. - Public Certificate Directories: Services providing APIs to query issued certificates for analysis. This data component can be collected through the following measures: Use Certificate Transparency Monitors - Tools like crt.sh, CertStream, or APIs provided by certificate authorities (CAs) allow you to monitor issued certificates in real-time. - Example: Use CertStream to stream certificate issuance logs and filter for domains of interest. Analyze Certificate Revocation Sources - Monitor CRLs or query OCSP responders to detect revoked certificates. - Configure tools like OpenSSL or browsers to validate certificate revocation status automatically. Leverage Public Scanning Tools - Use tools such as SSL Labs, Censys, or Shodan to scan for certificate details related to your domain or network. Automate Certificate Monitoring - Set up automated scripts or services to parse Certificate Transparency logs for anomalies. - Example: Automate searches on crt.sh to identify certificates issued for typo-squatted domains. Integrate with Threat Intelligence - Enrich certificate data with threat intelligence feeds to detect connections to known adversary-controlled infrastructure. - Tools like VirusTotal can identify malicious certificates based on associated indicators.

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
