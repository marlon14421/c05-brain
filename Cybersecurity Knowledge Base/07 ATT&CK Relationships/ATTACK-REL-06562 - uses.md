---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0517"
target_object: "T1546.011"
stix_relationship_id: "relationship--09896887-98ee-4e8a-9cc2-4203b3b561c8"
---
# Relationship 6562: S0517 — uses → T1546.011

**Source object:** [[01 ATT&CK/S0517 - Pillowmint|S0517: Pillowmint]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.011 - Application Shimming|T1546.011: Application Shimming]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pillowmint](https://attack.mitre.org/software/S0517) has used a malicious shim database to maintain persistence.(Citation: Trustwave Pillowmint June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--09896887-98ee-4e8a-9cc2-4203b3b561c8`.
