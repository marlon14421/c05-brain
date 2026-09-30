---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0640"
target_object: "T1547.001"
stix_relationship_id: "relationship--cfda1087-90e8-46f3-9751-06e2140f2f2c"
---
# Relationship 9592: S0640 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0640 - Avaddon|S0640: Avaddon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Avaddon](https://attack.mitre.org/software/S0640) uses registry run keys for persistence.(Citation: Arxiv Avaddon Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfda1087-90e8-46f3-9751-06e2140f2f2c`.
