---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0079"
target_object: "T1041"
stix_relationship_id: "relationship--4ffcf69a-c7ef-46dc-add7-9093e454a67e"
---
# Relationship 7692: S0079 — uses → T1041

**Source object:** [[01 ATT&CK/S0079 - MobileOrder|S0079: MobileOrder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MobileOrder](https://attack.mitre.org/software/S0079) exfiltrates data to its C2 server over the same protocol as C2 communications.(Citation: Scarlet Mimic Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ffcf69a-c7ef-46dc-add7-9093e454a67e`.
