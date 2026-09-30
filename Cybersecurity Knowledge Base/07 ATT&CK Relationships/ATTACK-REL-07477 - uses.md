---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1022"
target_object: "T1005"
stix_relationship_id: "relationship--2095d4fa-73b6-4a67-ac25-394f64d122d5"
---
# Relationship 7477: G1022 — uses → T1005

**Source object:** [[01 ATT&CK/G1022 - ToddyCat|G1022: ToddyCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ToddyCat](https://attack.mitre.org/groups/G1022) has run scripts to collect documents from targeted hosts.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2095d4fa-73b6-4a67-ac25-394f64d122d5`.
