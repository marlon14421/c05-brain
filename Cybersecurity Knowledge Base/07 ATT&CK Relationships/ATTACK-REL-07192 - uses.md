---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0461"
target_object: "T1083"
stix_relationship_id: "relationship--03b12a66-789a-4480-8903-deab828d08b6"
---
# Relationship 7192: S0461 — uses → T1083

**Source object:** [[01 ATT&CK/S0461 - SDBbot|S0461: SDBbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SDBbot](https://attack.mitre.org/software/S0461) has the ability to get directory listings or drive information on a compromised host.(Citation: Proofpoint TA505 October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03b12a66-789a-4480-8903-deab828d08b6`.
