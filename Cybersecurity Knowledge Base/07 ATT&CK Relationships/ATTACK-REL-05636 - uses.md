---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0332"
target_object: "T1010"
stix_relationship_id: "relationship--e678f070-2fb7-41dc-b63f-8dba148a5f97"
---
# Relationship 5636: S0332 — uses → T1010

**Source object:** [[01 ATT&CK/S0332 - Remcos|S0332: Remcos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remcos](https://attack.mitre.org/software/S0332) can list all windows on victim systems.(Citation: Fortinet Remcos Campaign NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e678f070-2fb7-41dc-b63f-8dba148a5f97`.
