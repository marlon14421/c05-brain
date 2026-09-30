---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0652"
target_object: "T1005"
stix_relationship_id: "relationship--41160796-9596-4a58-92a1-14dd3c9f4271"
---
# Relationship 6288: S0652 — uses → T1005

**Source object:** [[01 ATT&CK/S0652 - MarkiRAT|S0652: MarkiRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MarkiRAT](https://attack.mitre.org/software/S0652) can upload data from the victim's machine to the C2 server.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41160796-9596-4a58-92a1-14dd3c9f4271`.
