---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0380"
target_object: "T1047"
stix_relationship_id: "relationship--80c90e89-2519-40cb-8757-06471e47d0fb"
---
# Relationship 3949: S0380 — uses → T1047

**Source object:** [[01 ATT&CK/S0380 - StoneDrill|S0380: StoneDrill]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StoneDrill](https://attack.mitre.org/software/S0380) has used the WMI command-line (WMIC) utility to run tasks.(Citation: Kaspersky StoneDrill 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80c90e89-2519-40cb-8757-06471e47d0fb`.
