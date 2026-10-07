---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1649"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1649: Steal or Forge Authentication Certificates — Defensive Application

## Source record

- [[01 ATT&CK/T1649 - Steal or Forge Authentication Certificates|T1649 source record]]
- ATT&CK class: Technique
- Platforms: Windows, Linux, macOS, Identity Provider
- Tactics: credential-access

## Source context

Adversaries may steal or forge certificates used for authentication to access remote systems or resources. Digital certificates are often used to sign and encrypt messages and/or files. Certificates are also used as authentication material. For example, Entra ID device certificates and Active Directory Certificate Services (AD CS) certificates bind to an identity and can be used as credentials for domain accounts.(Citation: O365 Blog Azure AD Device IDs)(Citation: Microsoft AD CS Overview) Authentication certificates can be both stolen and forged. For example, AD CS certificates can be stolen from encrypted storage (in the Registry or files)(Citation: APT29 Deep Look at Credential Roaming), misplaced certificate files (i.e. [Unsecured Credentials](https://attack.mitre.org/techniques/T1552)), or directly from the Windows certificate store via various crypto APIs.(Citation: SpecterOps Certified Pre Owned)(Citation: GitHub CertStealer)(Citation: GitHub GhostPack Certificates) With appropriate enrollment rights, users and/or machines within a domain can also request and/or manually renew certificates from enterprise certificate authorities (CA). This enrollment process defines various settings and permissions associated with the certificate. Of note, the certificate’s extended key usage (EKU) values define signing, encryption, and authentication use cases, while the certificate’s subject alternative name (SAN) values define the certificate owner’s alternate names.(Citation: Medium Certified Pre Owned) Abusing certificates for authentication credentials may enable other behaviors such as [Lateral Movement](https://attack.mitre.org/tactics/TA0008). Certificate-related misconfigurations may also enable opportunities for [Privilege Escalation](https://attack.mitre.org/tactics/TA0004), by way of allowing users to impersonate or assume privileged accounts or permissions via the identities (SANs) associated with a certificate. These abuses may also enable [Persistence](https://attack.mitre.org/tactics/TA0003) via stealing or forging certificates that can be used as [Valid Accounts](https://attack.mitre.org/techniques/T1078) for the duration of the certificate's validity, despite user password resets. Authentication certificates can also be stolen and forged for machine accounts. Adversaries who have access to root (or subordinate) CA certificate private keys (or mechanisms protecting/managing these keys) may also establish [Persistence](https://attack.mitre.org/tactics/TA0003) by forging arbitrary authentication certificates for the victim domain (known as “golden” certificates).(Citation: Medium Certified Pre Owned) Adversaries may also target certificates and related services in order to access other forms of credentials, such as [Golden Ticket](https://attack.mitre.org/techniques/T1558/001) ticket-granting tickets (TGT) or NTLM plaintext.(Citation: Medium Certified Pre Owned)

## Defensive focus

Map the recorded behavior or objective to assets, trust boundaries, identities, and defensive controls in the local environment. ATT&CK classification alone does not establish activity or compromise.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets, roles, platforms, and business services are actually exposed to this behavior?
- What prevention or hardening control applies, and which owner maintains it?
- Which telemetry source can support or refute the behavior, and what blind spots remain?
- What legitimate administrative or software behavior could look similar?
- What containment or recovery decision is authorized if evidence is confirmed?

## Safe validation

Use an isolated lab, benign simulation, or sanitized historical data. Test only owned or explicitly authorized systems; do not reproduce harmful behavior against production targets. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
