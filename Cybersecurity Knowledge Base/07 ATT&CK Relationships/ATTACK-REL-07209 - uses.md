---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1027.015"
stix_relationship_id: "relationship--7c9d93d6-c50a-4f6c-8b1d-965ebbdcc268"
---
# Relationship 7209: S0559 — uses → T1027.015

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) strings were compressed and encoded in Base64.(Citation: Microsoft Analyzing Solorigate Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c9d93d6-c50a-4f6c-8b1d-965ebbdcc268`.
