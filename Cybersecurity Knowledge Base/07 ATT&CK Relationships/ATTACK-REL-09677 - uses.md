---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1186"
target_object: "T1071.001"
stix_relationship_id: "relationship--91730e03-6601-4203-8c00-3f595cce7d7d"
---
# Relationship 9677: S1186 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1186 - Line Dancer|S1186: Line Dancer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Line Dancer](https://attack.mitre.org/software/S1186) uses HTTP POST requests to interact with compromised devices.(Citation: Cisco ArcaneDoor 2024)(Citation: CCCS ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91730e03-6601-4203-8c00-3f595cce7d7d`.
