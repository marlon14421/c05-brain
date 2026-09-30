---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1568.001"
stix_relationship_id: "relationship--53356453-2cf1-46d9-ac8f-77fc3a2274d9"
---
# Relationship 5995: G0092 — uses → T1568.001

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.001 - Fast Flux DNS|T1568.001: Fast Flux DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has used fast flux to mask botnets by distributing payloads across multiple IPs.(Citation: Trend Micro TA505 June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53356453-2cf1-46d9-ac8f-77fc3a2274d9`.
