---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1034"
target_object: "T1204.001"
stix_relationship_id: "relationship--8fd50d9a-0d3e-4433-a2b9-b9e0ae3621f7"
---
# Relationship 9994: G1034 — uses → T1204.001

**Source object:** [[01 ATT&CK/G1034 - Daggerfly|G1034: Daggerfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Daggerfly](https://attack.mitre.org/groups/G1034) has used strategic website compromise to deliver a malicious link requiring user interaction.(Citation: ESET EvasivePanda 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8fd50d9a-0d3e-4433-a2b9-b9e0ae3621f7`.
