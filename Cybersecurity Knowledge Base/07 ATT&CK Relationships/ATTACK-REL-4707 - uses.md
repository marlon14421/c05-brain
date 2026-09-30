---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "S0393"
stix_relationship_id: "relationship--76428147-d359-4568-a1a2-7cc3da632da4"
---
# Relationship 4707: G0010 — uses → S0393

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0393 - PowerStallion|S0393: PowerStallion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: ESET Turla PowerShell May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76428147-d359-4568-a1a2-7cc3da632da4`.
