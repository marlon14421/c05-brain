---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1142"
target_object: "T1113"
stix_relationship_id: "relationship--c4f4e2ba-5ad8-4787-8d69-cc6720619ac9"
---
# Relationship 5594: S1142 — uses → T1113

**Source object:** [[01 ATT&CK/S1142 - LunarMail|S1142: LunarMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarMail](https://attack.mitre.org/software/S1142) can capture screenshots from compromised hosts.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4f4e2ba-5ad8-4787-8d69-cc6720619ac9`.
