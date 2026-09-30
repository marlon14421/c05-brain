---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0201"
target_object: "T1197"
stix_relationship_id: "relationship--45d8c4f2-27e4-4063-9eec-d8023c61c74b"
---
# Relationship 5580: S0201 — uses → T1197

**Source object:** [[01 ATT&CK/S0201 - JPIN|S0201: JPIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1197 - BITS Jobs|T1197: BITS Jobs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [JPIN](https://attack.mitre.org/software/S0201) variant downloads the backdoor payload via the BITS service.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45d8c4f2-27e4-4063-9eec-d8023c61c74b`.
