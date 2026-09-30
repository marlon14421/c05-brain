---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9025"
target_object: "T1027"
stix_relationship_id: "relationship--9e35b5e0-dfac-4c0d-a257-415e091a7344"
---
# Relationship 7968: S9025 — uses → T1027

**Source object:** [[01 ATT&CK/S9025 - NOOPLDR|S9025: NOOPLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOOPLDR](https://attack.mitre.org/software/S9025) can use control flow flattening to help hide malicious code.(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e35b5e0-dfac-4c0d-a257-415e091a7344`.
