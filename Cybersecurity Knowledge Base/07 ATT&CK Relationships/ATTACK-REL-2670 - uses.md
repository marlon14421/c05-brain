---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0342"
target_object: "T1056.001"
stix_relationship_id: "relationship--ce4bf5bc-4935-429b-843e-3232fb810e90"
---
# Relationship 2670: S0342 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0342 - GreyEnergy|S0342: GreyEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GreyEnergy](https://attack.mitre.org/software/S0342) has a module to harvest pressed keystrokes.(Citation: ESET GreyEnergy Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce4bf5bc-4935-429b-843e-3232fb810e90`.
