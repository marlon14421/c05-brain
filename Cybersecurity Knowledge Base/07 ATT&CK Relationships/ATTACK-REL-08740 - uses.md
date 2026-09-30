---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1598.003"
stix_relationship_id: "relationship--5f8667b5-b957-4f45-9c58-07321db8f62a"
---
# Relationship 8740: G1057 — uses → T1598.003

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.003 - Spearphishing Link|T1598.003: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has used spearphishing emails with malicious links to gain initial access and credentials.(Citation: SOCRadar_ShinyHunters_Mar2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f8667b5-b957-4f45-9c58-07321db8f62a`.
