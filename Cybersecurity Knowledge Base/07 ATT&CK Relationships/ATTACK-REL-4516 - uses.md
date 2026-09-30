---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1021"
target_object: "T1190"
stix_relationship_id: "relationship--7bf7f711-823d-41b8-8e88-801f7fa98591"
---
# Relationship 4516: G1021 — uses → T1190

**Source object:** [[01 ATT&CK/G1021 - Cinnamon Tempest|G1021: Cinnamon Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cinnamon Tempest](https://attack.mitre.org/groups/G1021) has exploited multiple unpatched vulnerabilities for initial access including vulnerabilities in Microsoft Exchange, Manage Engine AdSelfService Plus, Confluence, and Log4j.(Citation: Microsoft Ransomware as a Service)(Citation: Microsoft Log4j Vulnerability Exploitation December 2021)(Citation: Sygnia Emperor Dragonfly October 2022)(Citation: SecureWorks BRONZE STARLIGHT Ransomware Operations June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7bf7f711-823d-41b8-8e88-801f7fa98591`.
