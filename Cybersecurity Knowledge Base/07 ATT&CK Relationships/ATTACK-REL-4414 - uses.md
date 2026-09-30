---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0136"
target_object: "T1586.002"
stix_relationship_id: "relationship--c291a0b4-31b5-4075-9672-b10b0e7bd4cc"
---
# Relationship 4414: G0136 — uses → T1586.002

**Source object:** [[01 ATT&CK/G0136 - IndigoZebra|G0136: IndigoZebra]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1586.002 - Email Accounts|T1586.002: Email Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IndigoZebra](https://attack.mitre.org/groups/G0136) has compromised legitimate email accounts to use in their spearphishing operations.(Citation: Checkpoint IndigoZebra July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c291a0b4-31b5-4075-9672-b10b0e7bd4cc`.
