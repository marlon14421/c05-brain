---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1012"
target_object: "T1048.002"
stix_relationship_id: "relationship--6aef256e-e914-42d3-af4a-3be735cf3fe3"
---
# Relationship 4285: G1012 — uses → T1048.002

**Source object:** [[01 ATT&CK/G1012 - CURIUM|G1012: CURIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.002 - Exfiltration Over Asymmetric Encrypted Non-C2 Protocol|T1048.002: Exfiltration Over Asymmetric Encrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CURIUM](https://attack.mitre.org/groups/G1012) has used SMTPS to exfiltrate collected data from victims.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6aef256e-e914-42d3-af4a-3be735cf3fe3`.
