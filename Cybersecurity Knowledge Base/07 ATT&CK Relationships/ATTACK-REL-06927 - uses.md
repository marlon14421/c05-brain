---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0052"
target_object: "T1499"
stix_relationship_id: "relationship--5e5b108b-fec6-4d44-ad9a-9302d4f6e368"
---
# Relationship 6927: S0052 — uses → T1499

**Source object:** [[01 ATT&CK/S0052 - OnionDuke|S0052: OnionDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1499 - Endpoint Denial of Service|T1499: Endpoint Denial of Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OnionDuke](https://attack.mitre.org/software/S0052) has the capability to use a Denial of Service module.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e5b108b-fec6-4d44-ad9a-9302d4f6e368`.
