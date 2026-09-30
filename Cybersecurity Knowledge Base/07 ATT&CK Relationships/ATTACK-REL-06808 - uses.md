---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1115"
target_object: "T1071.001"
stix_relationship_id: "relationship--dcae1ba7-5181-440e-9bb2-c03d09ad7377"
---
# Relationship 6808: S1115 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1115 - WIREFIRE|S1115: WIREFIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WIREFIRE](https://attack.mitre.org/software/S1115) can respond to specific HTTP `POST` requests to `/api/v1/cav/client/visits`.(Citation: Mandiant Cutting Edge January 2024)(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dcae1ba7-5181-440e-9bb2-c03d09ad7377`.
