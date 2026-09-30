---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1161"
target_object: "T1480.002"
stix_relationship_id: "relationship--19ac2479-ffef-40dc-9dbb-02c11ba49908"
---
# Relationship 4415: S1161 — uses → T1480.002

**Source object:** [[01 ATT&CK/S1161 - BPFDoor|S1161: BPFDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

When executed, [BPFDoor](https://attack.mitre.org/software/S1161) attempts to create and lock a runtime file, `/var/run/initd.lock`, and exits if it fails using the specified file, resulting in a makeshift mutex.(Citation: Deep Instinct BPFDoor 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19ac2479-ffef-40dc-9dbb-02c11ba49908`.
