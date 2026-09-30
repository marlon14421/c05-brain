---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1203"
stix_relationship_id: "relationship--6236226c-b950-4baf-a1f6-1c956ae04613"
---
# Relationship 7039: S1207 — uses → T1203

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) has exploited Office vulnerabilities during local execution such as CVE-2017-11882 and CVE-2018-0798.(Citation: Netskope XLoader 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6236226c-b950-4baf-a1f6-1c956ae04613`.
