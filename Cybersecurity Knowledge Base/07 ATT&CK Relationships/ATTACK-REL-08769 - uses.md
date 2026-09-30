---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0349"
target_object: "T1003.005"
stix_relationship_id: "relationship--9399157f-4443-447f-b2e1-2227582af6e6"
---
# Relationship 8769: S0349 — uses → T1003.005

**Source object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.005 - Cached Domain Credentials|T1003.005: Cached Domain Credentials]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LaZagne](https://attack.mitre.org/software/S0349) can perform credential dumping from MSCache to obtain account and password information.(Citation: GitHub LaZagne Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9399157f-4443-447f-b2e1-2227582af6e6`.
