---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1027.016"
stix_relationship_id: "relationship--b10b7d66-3bee-4ebc-98c2-2eec2259e19e"
---
# Relationship 2781: S0182 — uses → T1027.016

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) contains junk code in its functions in an effort to confuse disassembly programs.(Citation: FinFisher Citation)(Citation: Microsoft FinFisher March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b10b7d66-3bee-4ebc-98c2-2eec2259e19e`.
