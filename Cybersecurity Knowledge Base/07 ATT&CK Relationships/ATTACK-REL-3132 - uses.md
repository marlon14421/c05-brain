---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0009"
target_object: "T1005"
stix_relationship_id: "relationship--dd82187a-7a40-45c3-a1d2-66d37bc6146e"
---
# Relationship 3132: S0009 — uses → T1005

**Source object:** [[01 ATT&CK/S0009 - Hikit|S0009: Hikit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hikit](https://attack.mitre.org/software/S0009) can upload files from compromised machines.(Citation: Novetta-Axiom)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd82187a-7a40-45c3-a1d2-66d37bc6146e`.
