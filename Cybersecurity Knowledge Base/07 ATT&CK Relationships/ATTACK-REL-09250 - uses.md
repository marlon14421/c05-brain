---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1168"
target_object: "T1071.001"
stix_relationship_id: "relationship--863c918a-fc3e-431f-a948-1b70f724acc9"
---
# Relationship 9250: S1168 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1168 - SampleCheck5000|S1168: SampleCheck5000]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SampleCheck5000](https://attack.mitre.org/software/S1168) can use the Exchange Web Services API for C2 communication.(Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--863c918a-fc3e-431f-a948-1b70f724acc9`.
