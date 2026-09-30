---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0226"
target_object: "T1140"
stix_relationship_id: "relationship--0c4af99b-e82d-422f-86da-ccc94e55d763"
---
# Relationship 4045: S0226 — uses → T1140

**Source object:** [[01 ATT&CK/S0226 - Smoke Loader|S0226: Smoke Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) deobfuscates its code.(Citation: Talos Smoke Loader July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c4af99b-e82d-422f-86da-ccc94e55d763`.
