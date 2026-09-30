---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0195"
target_object: "T1070.004"
stix_relationship_id: "relationship--35f3fba0-7deb-4436-87a2-503c96f69342"
---
# Relationship 3048: S0195 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0195 - SDelete|S0195: SDelete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SDelete](https://attack.mitre.org/software/S0195) deletes data in a way that makes it unrecoverable.(Citation: Microsoft SDelete July 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35f3fba0-7deb-4436-87a2-503c96f69342`.
