---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1027.009"
stix_relationship_id: "relationship--f5e601f7-5f7a-4888-9e90-e7f815d5013c"
---
# Relationship 8680: C0021 — uses → T1027.009

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.009 - Embedded Payloads|T1027.009: Embedded Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors embedded a base64-encoded payload within a LNK file.(Citation: Microsoft Unidentified Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5e601f7-5f7a-4888-9e90-e7f815d5013c`.
