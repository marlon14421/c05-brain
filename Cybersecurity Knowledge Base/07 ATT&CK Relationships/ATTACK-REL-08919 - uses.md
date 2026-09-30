---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0657"
target_object: "T1033"
stix_relationship_id: "relationship--0efb0490-9935-4d51-8b2f-974e090bbc10"
---
# Relationship 8919: S0657 — uses → T1033

**Source object:** [[01 ATT&CK/S0657 - BLUELIGHT|S0657: BLUELIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLUELIGHT](https://attack.mitre.org/software/S0657) can collect the username on a compromised host.(Citation: Volexity InkySquid BLUELIGHT August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0efb0490-9935-4d51-8b2f-974e090bbc10`.
