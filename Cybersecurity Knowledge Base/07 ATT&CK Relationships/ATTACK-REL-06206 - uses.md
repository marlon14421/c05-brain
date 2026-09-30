---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0543"
target_object: "T1033"
stix_relationship_id: "relationship--98f55ec9-3170-41ad-9bac-c921fa4a29ea"
---
# Relationship 6206: S0543 — uses → T1033

**Source object:** [[01 ATT&CK/S0543 - Spark|S0543: Spark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Spark](https://attack.mitre.org/software/S0543) has run the whoami command and has a built-in command to identify the user logged in.(Citation: Unit42 Molerat Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98f55ec9-3170-41ad-9bac-c921fa4a29ea`.
