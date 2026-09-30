---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "S1137"
stix_relationship_id: "relationship--49257f1f-6ef2-4688-bca0-9f2cd86c9d39"
---
# Relationship 3922: G1030 — uses → S1137

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1137 - Moneybird|S1137: Moneybird]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Moneybird](https://attack.mitre.org/software/S1137) is associated with ransomware operations launched by [Agrius](https://attack.mitre.org/groups/G1030).(Citation: CheckPoint Agrius 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49257f1f-6ef2-4688-bca0-9f2cd86c9d39`.
