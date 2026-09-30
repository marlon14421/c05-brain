---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0272"
target_object: "T1083"
stix_relationship_id: "relationship--b7226792-d4ae-472c-a407-853d56fc887d"
---
# Relationship 3317: S0272 — uses → T1083

**Source object:** [[01 ATT&CK/S0272 - NDiskMonitor|S0272: NDiskMonitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NDiskMonitor](https://attack.mitre.org/software/S0272) can obtain a list of all files and directories as well as logical drives.(Citation: TrendMicro Patchwork Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7226792-d4ae-472c-a407-853d56fc887d`.
