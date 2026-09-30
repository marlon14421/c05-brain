---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1213.006"
stix_relationship_id: "relationship--04d9eeb2-158d-49d4-a100-555f6cf341ea"
---
# Relationship 3888: S9010 — uses → T1213.006

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.006 - Databases|T1213.006: Databases]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has collected data from macOS devices through the gathering of Apple Notes related files by targeting `/Library/Group Containers/group.com.apple.notes/NoteStore.sqlite`, `/Library/Group Containers/group.com.apple.notes/NoteStore.sqlite-wal`, and `/Library/Group Containers/group.com.apple.notes/NoteStore.sqlite-shm`.(Citation: Socket GlassWorm January 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04d9eeb2-158d-49d4-a100-555f6cf341ea`.
