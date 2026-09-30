---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0642"
target_object: "T1204.002"
stix_relationship_id: "relationship--9bce879f-ffe8-425b-81d6-10408902c397"
---
# Relationship 7708: S0642 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0642 - BADFLICK|S0642: BADFLICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADFLICK](https://attack.mitre.org/software/S0642) has relied upon users clicking on a malicious attachment delivered through spearphishing.(Citation: Accenture MUDCARP March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9bce879f-ffe8-425b-81d6-10408902c397`.
