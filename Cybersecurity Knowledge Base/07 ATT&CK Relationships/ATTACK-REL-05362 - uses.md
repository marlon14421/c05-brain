---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1037"
target_object: "T1204.002"
stix_relationship_id: "relationship--8cfc4444-a2bd-4553-8a26-9018cb561705"
---
# Relationship 5362: S1037 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1037 - STARWHALE|S1037: STARWHALE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STARWHALE](https://attack.mitre.org/software/S1037) has relied on victims opening a malicious Excel file for execution.(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8cfc4444-a2bd-4553-8a26-9018cb561705`.
