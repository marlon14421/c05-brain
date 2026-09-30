---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1050"
target_object: "T1486"
stix_relationship_id: "relationship--b9080073-c6c8-4220-894b-26153cc04f61"
---
# Relationship 3357: G1050 — uses → T1486

**Source object:** [[01 ATT&CK/G1050 - Water Galura|G1050: Water Galura]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Water Galura](https://attack.mitre.org/groups/G1050) has encrypted files on victim networks through the generation of [Qilin](https://attack.mitre.org/software/S1242) ransomware payloads.(Citation: BushidoToken Qilin RaaS JUN 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9080073-c6c8-4220-894b-26153cc04f61`.
