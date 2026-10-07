---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1213"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1213: Data from Information Repositories — Defensive Application

## Source record

- [[01 ATT&CK/T1213 - Data from Information Repositories|T1213 source record]]
- ATT&CK class: Technique
- Platforms: Linux, Windows, macOS, SaaS, IaaS, Office Suite
- Tactics: collection

## Source context

Adversaries may leverage information repositories to mine valuable information. Information repositories are tools that allow for storage of information, typically to facilitate collaboration or information sharing between users, and can store a wide variety of data that may aid adversaries in further objectives, such as Credential Access, Lateral Movement, or Defense Evasion, or direct access to the target information. Adversaries may also abuse external sharing features to share sensitive documents with recipients outside of the organization (i.e., [Transfer Data to Cloud Account](https://attack.mitre.org/techniques/T1537)). The following is a brief list of example information that may hold potential value to an adversary and may also be found on an information repository: * Policies, procedures, and standards * Physical / logical network diagrams * System architecture diagrams * Technical system documentation * Testing / development credentials (i.e., [Unsecured Credentials](https://attack.mitre.org/techniques/T1552)) * Work / project schedules * Source code snippets * Links to network shares and other internal resources * Contact or other sensitive information about business partners and customers, including personally identifiable information (PII) Information stored in a repository may vary based on the specific instance or environment. Specific common information repositories include the following: * Storage services such as IaaS databases, enterprise databases, and more specialized platforms such as customer relationship management (CRM) databases * Collaboration platforms such as SharePoint, Confluence, and code repositories * Messaging platforms such as Slack and Microsoft Teams In some cases, information repositories have been improperly secured, typically by unintentionally allowing for overly-broad access by all users or even public access to unauthenticated users. This is particularly common with cloud-native or cloud-hosted services, such as AWS Relational Database Service (RDS), Redis, or ElasticSearch.(Citation: Mitiga)(Citation: TrendMicro Exposed Redis 2020)(Citation: Cybernews Reuters Leak 2022)

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
