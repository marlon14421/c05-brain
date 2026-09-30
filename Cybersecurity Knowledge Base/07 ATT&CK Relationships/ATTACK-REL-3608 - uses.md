---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0625"
target_object: "T1083"
stix_relationship_id: "relationship--61a3d7e0-3663-4fb7-9bb3-20a73257f27d"
---
# Relationship 3608: S0625 — uses → T1083

**Source object:** [[01 ATT&CK/S0625 - Cuba|S0625: Cuba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cuba](https://attack.mitre.org/software/S0625) can enumerate files by using a variety of functions.(Citation: McAfee Cuba April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61a3d7e0-3663-4fb7-9bb3-20a73257f27d`.
