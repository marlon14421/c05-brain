---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9023"
target_object: "T1008"
stix_relationship_id: "relationship--52ce2f48-1bb7-48f9-8ac6-56002d93672f"
---
# Relationship 7239: S9023 — uses → T1008

**Source object:** [[01 ATT&CK/S9023 - HiddenFace|S9023: HiddenFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) can use active and passive C2 modes that use different encryption algorithms and backdoor commands.(Citation: Trend Micro Earth Kasha NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52ce2f48-1bb7-48f9-8ac6-56002d93672f`.
