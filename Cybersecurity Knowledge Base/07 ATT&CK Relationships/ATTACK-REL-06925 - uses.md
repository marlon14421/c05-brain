---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1129"
stix_relationship_id: "relationship--5cf3da17-8c0a-4a4d-8926-3fc251085ddf"
---
# Relationship 6925: S1185 — uses → T1129

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightSpy](https://attack.mitre.org/software/S1185)'s main executable and module `.dylib` binaries are loaded using a combination of `dlopen()` to load the library, `_objc_getClass()` to retrieve the class definition, and `_objec_msgSend()` to invoke/execute the specified method in the loaded class.(Citation: Huntress LightSpy macOS 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cf3da17-8c0a-4a4d-8926-3fc251085ddf`.
