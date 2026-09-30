---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1056.001"
stix_relationship_id: "relationship--2d450e2f-25c9-49af-b83f-6c91029ed28a"
---
# Relationship 8192: G0007 — uses → T1056.001

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used tools to perform keylogging.(Citation: Microsoft SIR Vol 19)(Citation: DOJ GRU Indictment Jul 2018)(Citation: TrendMicro Pawn Storm Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d450e2f-25c9-49af-b83f-6c91029ed28a`.
