---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1075"
target_object: "T1680"
stix_relationship_id: "relationship--b3bc70ea-4f9e-4933-81e7-eb8b19f89a3b"
---
# Relationship 9255: S1075 — uses → T1680

**Source object:** [[01 ATT&CK/S1075 - KOPILUWAK|S1075: KOPILUWAK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOPILUWAK](https://attack.mitre.org/software/S1075) can discover logical drive information on compromised hosts.(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3bc70ea-4f9e-4933-81e7-eb8b19f89a3b`.
