---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1181"
target_object: "T1489"
stix_relationship_id: "relationship--9a7835e3-5d9a-440c-84c2-5a1f60fef646"
---
# Relationship 9975: S1181 — uses → T1489

**Source object:** [[01 ATT&CK/S1181 - BlackByte 2.0 Ransomware|S1181: BlackByte 2.0 Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) can terminate running services.(Citation: Microsoft BlackByte 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9a7835e3-5d9a-440c-84c2-5a1f60fef646`.
