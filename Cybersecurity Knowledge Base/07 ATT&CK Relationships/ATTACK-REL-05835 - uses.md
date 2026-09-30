---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0009"
target_object: "T1505.003"
stix_relationship_id: "relationship--44f230bb-b59a-4f30-8203-5e5ffd9796f5"
---
# Relationship 5835: G0009 — uses → T1505.003

**Source object:** [[01 ATT&CK/G0009 - Deep Panda|G0009: Deep Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Deep Panda](https://attack.mitre.org/groups/G0009) uses Web shells on publicly accessible Web servers to access victim networks.(Citation: CrowdStrike Deep Panda Web Shells)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44f230bb-b59a-4f30-8203-5e5ffd9796f5`.
