---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1222"
target_object: "T1059.004"
stix_relationship_id: "relationship--e108870b-ba34-4e53-afcc-67a3ab96f260"
---
# Relationship 9596: S1222 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1222 - RIFLESPINE|S1222: RIFLESPINE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RIFLESPINE](https://attack.mitre.org/software/S1222) can execute commands with `/bin/sh`.(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e108870b-ba34-4e53-afcc-67a3ab96f260`.
