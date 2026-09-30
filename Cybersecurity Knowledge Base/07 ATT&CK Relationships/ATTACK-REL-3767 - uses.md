---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0261"
target_object: "T1112"
stix_relationship_id: "relationship--0dd74596-509c-4669-9d29-e1fb501c9c70"
---
# Relationship 3767: S0261 — uses → T1112

**Source object:** [[01 ATT&CK/S0261 - Catchamas|S0261: Catchamas]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Catchamas](https://attack.mitre.org/software/S0261) creates three Registry keys to establish persistence by adding a [Windows Service](https://attack.mitre.org/techniques/T1543/003).(Citation: Symantec Catchamas April 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dd74596-509c-4669-9d29-e1fb501c9c70`.
