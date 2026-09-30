---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9021"
target_object: "T1140"
stix_relationship_id: "relationship--66c646e5-2364-4d26-bd03-56e5544553d3"
---
# Relationship 4485: S9021 — uses → T1140

**Source object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) can decode strings prior to execution.(Citation: Kaspersky LODEINFO OCT 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66c646e5-2364-4d26-bd03-56e5544553d3`.
