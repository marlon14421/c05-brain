---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0013"
target_object: "S0036"
stix_relationship_id: "relationship--a18071ad-fe4f-4014-ad9a-1b0a66df3eab"
---
# Relationship 4777: G0013 — uses → S0036

**Source object:** [[01 ATT&CK/G0013 - APT30|G0013: APT30]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0036 - FLASHFLOOD|S0036: FLASHFLOOD]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: FireEye APT30)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a18071ad-fe4f-4014-ad9a-1b0a66df3eab`.
