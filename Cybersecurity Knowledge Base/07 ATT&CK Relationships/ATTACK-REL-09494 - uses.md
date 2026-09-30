---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0500"
target_object: "T1070.009"
stix_relationship_id: "relationship--3c385d99-72c8-40b8-8eb5-f844c2b191c8"
---
# Relationship 9494: S0500 — uses → T1070.009

**Source object:** [[01 ATT&CK/S0500 - MCMD|S0500: MCMD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.009 - Clear Persistence|T1070.009: Clear Persistence]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MCMD](https://attack.mitre.org/software/S0500) has the ability to remove set Registry Keys, including those used for persistence.(Citation: Secureworks MCMD July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c385d99-72c8-40b8-8eb5-f844c2b191c8`.
