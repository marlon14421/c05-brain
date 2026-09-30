---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0184"
target_object: "T1012"
stix_relationship_id: "relationship--d078f862-c090-4e79-808b-ff69887a920c"
---
# Relationship 9925: S0184 — uses → T1012

**Source object:** [[01 ATT&CK/S0184 - POWRUNER|S0184: POWRUNER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWRUNER](https://attack.mitre.org/software/S0184) may query the Registry by running reg query on a victim.(Citation: FireEye APT34 Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d078f862-c090-4e79-808b-ff69887a920c`.
