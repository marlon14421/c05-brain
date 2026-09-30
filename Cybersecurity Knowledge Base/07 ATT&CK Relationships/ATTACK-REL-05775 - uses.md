---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0137"
target_object: "T1583.001"
stix_relationship_id: "relationship--e9375a8c-4574-40a9-a3c2-a9fe036928a6"
---
# Relationship 5775: G0137 — uses → T1583.001

**Source object:** [[01 ATT&CK/G0137 - Ferocious Kitten|G0137: Ferocious Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ferocious Kitten](https://attack.mitre.org/groups/G0137) has acquired domains imitating legitimate sites.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9375a8c-4574-40a9-a3c2-a9fe036928a6`.
