---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1115"
target_object: "T1140"
stix_relationship_id: "relationship--2329e6c4-5462-4d14-9a50-2d9272f83a09"
---
# Relationship 2863: S1115 — uses → T1140

**Source object:** [[01 ATT&CK/S1115 - WIREFIRE|S1115: WIREFIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WIREFIRE](https://attack.mitre.org/software/S1115) can decode, decrypt, and decompress data received in C2 HTTP `POST` requests.(Citation: Mandiant Cutting Edge January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2329e6c4-5462-4d14-9a50-2d9272f83a09`.
