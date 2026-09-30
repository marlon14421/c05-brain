---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1505.003"
stix_relationship_id: "relationship--60ac5ce0-46ef-4448-8d8d-f0efd7d9a691"
---
# Relationship 6850: G0129 — uses → T1505.003

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used [China Chopper](https://attack.mitre.org/software/S0020) web shells to maintain access to victims’ environments.(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60ac5ce0-46ef-4448-8d8d-f0efd7d9a691`.
