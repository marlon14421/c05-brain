---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1114"
target_object: "T1090"
stix_relationship_id: "relationship--096d97b6-57d0-4722-a204-685fb48ed5ca"
---
# Relationship 8132: S1114 — uses → T1090

**Source object:** [[01 ATT&CK/S1114 - ZIPLINE|S1114: ZIPLINE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZIPLINE](https://attack.mitre.org/software/S1114) can create a proxy server on compromised hosts.(Citation: Mandiant Cutting Edge January 2024)(Citation: Mandiant Cutting Edge Part 2 January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--096d97b6-57d0-4722-a204-685fb48ed5ca`.
