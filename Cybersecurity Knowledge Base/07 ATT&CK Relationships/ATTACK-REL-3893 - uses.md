---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1158"
target_object: "T1140"
stix_relationship_id: "relationship--92bab2d2-bb5a-4102-a9ec-7630153cac50"
---
# Relationship 3893: S1158 — uses → T1140

**Source object:** [[01 ATT&CK/S1158 - DUSTPAN|S1158: DUSTPAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) decodes and decrypts embedded payloads.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92bab2d2-bb5a-4102-a9ec-7630153cac50`.
