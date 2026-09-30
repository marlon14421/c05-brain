---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1019"
target_object: "T1036.005"
stix_relationship_id: "relationship--9b2a6cfa-3b05-4809-b778-3752bb152c2d"
---
# Relationship 4343: S1019 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1019 - Shark|S1019: Shark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shark](https://attack.mitre.org/software/S1019) binaries have been named `audioddg.pdb` and `Winlangdb.pdb` in order to appear legitimate.(Citation: ClearSky Siamesekitten August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b2a6cfa-3b05-4809-b778-3752bb152c2d`.
