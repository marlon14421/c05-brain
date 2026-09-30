---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1084"
target_object: "T1008"
stix_relationship_id: "relationship--550d2a38-7dd8-497d-b65d-43b65a3ec49e"
---
# Relationship 8524: S1084 — uses → T1008

**Source object:** [[01 ATT&CK/S1084 - QUIETEXIT|S1084: QUIETEXIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QUIETEXIT](https://attack.mitre.org/software/S1084) can attempt to connect to a second hard-coded C2 if the first hard-coded C2 address fails.(Citation: Mandiant APT29 Eye Spy Email Nov 22)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--550d2a38-7dd8-497d-b65d-43b65a3ec49e`.
