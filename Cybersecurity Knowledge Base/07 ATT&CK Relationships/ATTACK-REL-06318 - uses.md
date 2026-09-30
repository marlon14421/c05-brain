---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1109"
target_object: "T1074.001"
stix_relationship_id: "relationship--fc9b992b-d38d-46f5-84b5-13c0e116a717"
---
# Relationship 6318: S1109 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1109 - PACEMAKER|S1109: PACEMAKER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PACEMAKER](https://attack.mitre.org/software/S1109) has written extracted data to `tmp/dsserver-check.statementcounters`.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc9b992b-d38d-46f5-84b5-13c0e116a717`.
