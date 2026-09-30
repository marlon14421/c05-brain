---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0384"
target_object: "T1219"
stix_relationship_id: "relationship--11d5cf7f-7b0c-49b3-b8d0-9906f440d2d0"
---
# Relationship 9350: S0384 — uses → T1219

**Source object:** [[01 ATT&CK/S0384 - Dridex|S0384: Dridex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dridex](https://attack.mitre.org/software/S0384) contains a module for VNC.(Citation: Dell Dridex Oct 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11d5cf7f-7b0c-49b3-b8d0-9906f440d2d0`.
