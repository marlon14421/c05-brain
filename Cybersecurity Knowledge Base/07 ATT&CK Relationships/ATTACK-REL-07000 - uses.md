---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1547.001"
stix_relationship_id: "relationship--c28ef21a-d62b-45de-8cda-e80f0cb3accf"
---
# Relationship 7000: S9020 — uses → T1547.001

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) has used Registry run keys to set persistence.(Citation: ESET MirrorFace DEC 2022)(Citation: Trend Micro Earth Kasha NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c28ef21a-d62b-45de-8cda-e80f0cb3accf`.
