---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1083"
stix_relationship_id: "relationship--6189bf91-d755-47e6-9f3c-dd621e3f64fd"
---
# Relationship 4505: S0559 — uses → T1083

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) had commands to enumerate files and directories.(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: Microsoft Analyzing Solorigate Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6189bf91-d755-47e6-9f3c-dd621e3f64fd`.
