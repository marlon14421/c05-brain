---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0471"
target_object: "T1036.004"
stix_relationship_id: "relationship--506ed241-ba1e-47da-901a-d1943510d4b5"
---
# Relationship 3684: S0471 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0471 - build_downer|S0471: build_downer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[build_downer](https://attack.mitre.org/software/S0471) has added itself to the Registry Run key as "NVIDIA" to appear legitimate.(Citation: Trend Micro Tick November 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--506ed241-ba1e-47da-901a-d1943510d4b5`.
