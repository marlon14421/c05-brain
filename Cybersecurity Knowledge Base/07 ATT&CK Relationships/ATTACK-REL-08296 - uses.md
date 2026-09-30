---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9025"
target_object: "T1574.001"
stix_relationship_id: "relationship--d4812772-93e3-4148-9a5f-b62c02cfa8cb"
---
# Relationship 8296: S9025 — uses → T1574.001

**Source object:** [[01 ATT&CK/S9025 - NOOPLDR|S9025: NOOPLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOOPLDR](https://attack.mitre.org/software/S9025) can be executed via sideloading.(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4812772-93e3-4148-9a5f-b62c02cfa8cb`.
