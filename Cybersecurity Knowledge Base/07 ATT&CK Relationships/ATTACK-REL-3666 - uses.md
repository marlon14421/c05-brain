---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "S1035"
stix_relationship_id: "relationship--8911df73-17ac-430b-b1d5-3a021bc64998"
---
# Relationship 3666: G0069 — uses → S1035

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: NCSC GCHQ Small Sieve Jan 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8911df73-17ac-430b-b1d5-3a021bc64998`.
