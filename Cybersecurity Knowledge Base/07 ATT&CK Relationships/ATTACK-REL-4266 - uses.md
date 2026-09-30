---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0015"
target_object: "T1083"
stix_relationship_id: "relationship--135fb6c4-1f42-42ce-b323-22e57ae4fbc6"
---
# Relationship 4266: C0015 — uses → T1083

**Source object:** [[01 ATT&CK/C0015 - C0015|C0015: C0015]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0015](https://attack.mitre.org/campaigns/C0015), the threat actors conducted a file listing discovery against multiple hosts to ensure locker encryption was successful.(Citation: DFIR Conti Bazar Nov 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--135fb6c4-1f42-42ce-b323-22e57ae4fbc6`.
