---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1220"
stix_relationship_id: "relationship--8c13ef6b-5274-4de0-9fad-531b9c87309e"
---
# Relationship 6173: G0080 — uses → T1220

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1220 - XSL Script Processing|T1220: XSL Script Processing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) used msxsl.exe to bypass AppLocker and to invoke Jscript code from an XSL file.(Citation: Talos Cobalt Group July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c13ef6b-5274-4de0-9fad-531b9c87309e`.
