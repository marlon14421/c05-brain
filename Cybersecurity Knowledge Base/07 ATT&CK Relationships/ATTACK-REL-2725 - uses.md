---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0257"
target_object: "T1115"
stix_relationship_id: "relationship--5070c502-1f3b-4e8c-8eb5-2ea5379fd8f4"
---
# Relationship 2725: S0257 — uses → T1115

**Source object:** [[01 ATT&CK/S0257 - VERMIN|S0257: VERMIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VERMIN](https://attack.mitre.org/software/S0257) collects data stored in the clipboard.(Citation: Unit 42 VERMIN Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5070c502-1f3b-4e8c-8eb5-2ea5379fd8f4`.
