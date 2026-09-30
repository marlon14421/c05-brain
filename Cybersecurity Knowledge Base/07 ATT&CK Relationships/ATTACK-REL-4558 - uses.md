---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9021"
target_object: "T1106"
stix_relationship_id: "relationship--fa6f51f8-218b-41ce-bdd9-4e15df864667"
---
# Relationship 4558: S9021 — uses → T1106

**Source object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) can use the `URLDownloadToFileA()` API to download from remote resources.(Citation: Kaspersky LODEINFO OCT 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa6f51f8-218b-41ce-bdd9-4e15df864667`.
