---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1050"
target_object: "T1657"
stix_relationship_id: "relationship--e2029939-dcf2-4211-8485-1065bf6a4c4f"
---
# Relationship 3478: G1050 — uses → T1657

**Source object:** [[01 ATT&CK/G1050 - Water Galura|G1050: Water Galura]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Water Galura](https://attack.mitre.org/groups/G1050) has extorted victims for ransomware decryption keys and to prevent publication of data exfiltrated to their [Tor](https://attack.mitre.org/software/S0183) data leak site.(Citation: BushidoToken Qilin RaaS JUN 2024)(Citation: HC3 Qilin Threat Profile JUN 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2029939-dcf2-4211-8485-1065bf6a4c4f`.
