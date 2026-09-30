---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0400"
target_object: "T1489"
stix_relationship_id: "relationship--3e4f8216-03ef-4e7a-8a4a-28905fb0f474"
---
# Relationship 8550: S0400 — uses → T1489

**Source object:** [[01 ATT&CK/S0400 - RobbinHood|S0400: RobbinHood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RobbinHood](https://attack.mitre.org/software/S0400) stops 181 Windows services on the system before beginning the encryption process.(Citation: CarbonBlack RobbinHood May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e4f8216-03ef-4e7a-8a4a-28905fb0f474`.
