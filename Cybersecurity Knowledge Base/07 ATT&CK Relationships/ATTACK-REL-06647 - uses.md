---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1105"
stix_relationship_id: "relationship--ea4871e2-8754-4002-9e76-a2c1c0ed7e2f"
---
# Relationship 6647: S0595 — uses → T1105

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) can download and execute payloads in-memory or from disk.(Citation: wardle evilquest partii)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea4871e2-8754-4002-9e76-a2c1c0ed7e2f`.
