---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0608"
target_object: "T1091"
stix_relationship_id: "relationship--f308adef-2601-41b2-9da8-b785a7adf06c"
---
# Relationship 5299: S0608 — uses → T1091

**Source object:** [[01 ATT&CK/S0608 - Conficker|S0608: Conficker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conficker](https://attack.mitre.org/software/S0608) variants used the Windows AUTORUN feature to spread through USB propagation.(Citation: SANS Conficker)(Citation: Trend Micro Conficker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f308adef-2601-41b2-9da8-b785a7adf06c`.
