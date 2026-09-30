---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1085"
target_object: "T1057"
stix_relationship_id: "relationship--a570d430-29ea-4c89-b25d-1370b44b0e5a"
---
# Relationship 5454: S1085 — uses → T1057

**Source object:** [[01 ATT&CK/S1085 - Sardonic|S1085: Sardonic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sardonic](https://attack.mitre.org/software/S1085) has the ability to execute the `tasklist` command.(Citation: Bitdefender Sardonic Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a570d430-29ea-4c89-b25d-1370b44b0e5a`.
