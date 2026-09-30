---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1204.001"
stix_relationship_id: "relationship--3ff580a6-1323-4587-8f64-137e02f148e6"
---
# Relationship 5741: S1160 — uses → T1204.001

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) has been executed through malicious links distributed in email campaigns.(Citation: Latrodectus APR 2024)(Citation: Bleeping Computer Latrodectus April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ff580a6-1323-4587-8f64-137e02f148e6`.
