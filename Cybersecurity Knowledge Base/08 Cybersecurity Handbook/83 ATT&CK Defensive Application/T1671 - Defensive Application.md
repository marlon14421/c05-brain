---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1671"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1671: Cloud Application Integration — Defensive Application

## Source record

- [[01 ATT&CK/T1671 - Cloud Application Integration|T1671 source record]]
- ATT&CK class: Technique
- Platforms: Office Suite, SaaS
- Tactics: persistence

## Source context

Adversaries may achieve persistence by leveraging OAuth application integrations in a software-as-a-service environment. Adversaries may create a custom application, add a legitimate application into the environment, or even co-opt an existing integration to achieve malicious ends.(Citation: Push Security SaaS Persistence 2022)(Citation: SaaS Attacks GitHub Evil Twin Integrations) OAuth is an open standard that allows users to authorize applications to access their information on their behalf. In a SaaS environment such as Microsoft 365 or Google Workspace, users may integrate applications to improve their workflow and achieve tasks. Leveraging application integrations may allow adversaries to persist in an environment – for example, by granting consent to an application from a high-privileged adversary-controlled account in order to maintain access to its data, even in the event of losing access to the account.(Citation: Wiz Midnight Blizzard 2024)(Citation: Microsoft Malicious OAuth Applications 2022)(Citation: Huntress Persistence Microsoft 365 Compromise 2024) In some cases, integrations may remain valid even after the original consenting user account is disabled.(Citation: Push Security Slack Persistence 2023) Application integrations may also allow adversaries to bypass multi-factor authentication requirements through the use of [Application Access Token](https://attack.mitre.org/techniques/T1550/001)s. Finally, they may enable persistent [Automated Exfiltration](https://attack.mitre.org/techniques/T1020) over time.(Citation: Synes Cyber Corner Malicious Azure Application 2023) Creating or adding a new application may require the adversary to create a dedicated [Cloud Account](https://attack.mitre.org/techniques/T1136/003) for the application and assign it [Additional Cloud Roles](https://attack.mitre.org/techniques/T1098/003) – for example, in Microsoft 365 environments, an application can only access resources via an associated service principal.(Citation: Microsoft Entra ID Service Principals)

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
