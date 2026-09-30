---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0623"
target_object: "T1071"
stix_relationship_id: "relationship--79fd974c-b51b-45d4-b220-6f532ec6bc63"
---
# Relationship 3670: S0623 — uses → T1071

**Source object:** [[01 ATT&CK/S0623 - Siloscape|S0623: Siloscape]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071 - Application Layer Protocol|T1071: Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Siloscape](https://attack.mitre.org/software/S0623) connects to an IRC server for C2.(Citation: Unit 42 Siloscape Jun 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79fd974c-b51b-45d4-b220-6f532ec6bc63`.
