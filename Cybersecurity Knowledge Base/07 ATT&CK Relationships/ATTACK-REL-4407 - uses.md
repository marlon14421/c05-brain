---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0339"
target_object: "T1047"
stix_relationship_id: "relationship--dd050277-bfac-41ba-a40f-7970f2d36189"
---
# Relationship 4407: S0339 — uses → T1047

**Source object:** [[01 ATT&CK/S0339 - Micropsia|S0339: Micropsia]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Micropsia](https://attack.mitre.org/software/S0339) searches for anti-virus software and firewall products installed on the victim’s machine using WMI.(Citation: Talos Micropsia June 2017)(Citation: Radware Micropsia July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd050277-bfac-41ba-a40f-7970f2d36189`.
