---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1027.009"
stix_relationship_id: "relationship--ce1ef7d9-497c-4aeb-8e6d-a828499ed940"
---
# Relationship 7678: S9042 — uses → T1027.009

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.009 - Embedded Payloads|T1027.009: Embedded Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has used embedded second stage Base64-encoded payloads.(Citation: Aikido TeamPCP Trivy MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce1ef7d9-497c-4aeb-8e6d-a828499ed940`.
