---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0103"
target_object: "T1027.015"
stix_relationship_id: "relationship--c67a1234-2bb9-429f-8605-793ac03bd3bf"
---
# Relationship 6021: G0103 — uses → T1027.015

**Source object:** [[01 ATT&CK/G0103 - Mofang|G0103: Mofang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mofang](https://attack.mitre.org/groups/G0103) has compressed the [ShimRat](https://attack.mitre.org/software/S0444) executable within malicious email attachments.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c67a1234-2bb9-429f-8605-793ac03bd3bf`.
