---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0556"
target_object: "T1489"
stix_relationship_id: "relationship--287368b4-d3ed-489d-9fe2-288168763ac4"
---
# Relationship 7265: S0556 — uses → T1489

**Source object:** [[01 ATT&CK/S0556 - Pay2Key|S0556: Pay2Key]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pay2Key](https://attack.mitre.org/software/S0556) can stop the MS SQL service at the end of the encryption process to release files locked by the service.(Citation: Check Point Pay2Key November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--287368b4-d3ed-489d-9fe2-288168763ac4`.
