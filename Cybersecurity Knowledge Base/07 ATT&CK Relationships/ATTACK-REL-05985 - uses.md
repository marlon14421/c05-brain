---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0252"
target_object: "T1012"
stix_relationship_id: "relationship--ab08048c-4d1f-4214-9f53-1e87f6a20988"
---
# Relationship 5985: S0252 — uses → T1012

**Source object:** [[01 ATT&CK/S0252 - Brave Prince|S0252: Brave Prince]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Brave Prince](https://attack.mitre.org/software/S0252) gathers information about the Registry.(Citation: McAfee Gold Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab08048c-4d1f-4214-9f53-1e87f6a20988`.
