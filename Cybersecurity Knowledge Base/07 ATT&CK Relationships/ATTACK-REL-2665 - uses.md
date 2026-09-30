---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0637"
target_object: "T1036"
stix_relationship_id: "relationship--bc2fe4e7-cb7c-4707-b28b-a709c2ac017d"
---
# Relationship 2665: S0637 — uses → T1036

**Source object:** [[01 ATT&CK/S0637 - NativeZone|S0637: NativeZone]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NativeZone](https://attack.mitre.org/software/S0637) has, upon execution, displayed a message box that appears to be related to a Ukrainian electronic document management system.(Citation: SentinelOne NobleBaron June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc2fe4e7-cb7c-4707-b28b-a709c2ac017d`.
