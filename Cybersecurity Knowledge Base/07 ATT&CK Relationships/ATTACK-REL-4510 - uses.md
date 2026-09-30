---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0255"
target_object: "T1083"
stix_relationship_id: "relationship--992c7f74-c6d8-43e9-98e7-5818ca9524e3"
---
# Relationship 4510: S0255 — uses → T1083

**Source object:** [[01 ATT&CK/S0255 - DDKONG|S0255: DDKONG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DDKONG](https://attack.mitre.org/software/S0255) lists files on the victim’s machine.(Citation: Rancor Unit42 June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--992c7f74-c6d8-43e9-98e7-5818ca9524e3`.
