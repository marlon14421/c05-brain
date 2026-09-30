---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0066"
target_object: "T1070.006"
stix_relationship_id: "relationship--d43315b0-d708-4197-b3ed-0a0b1199e434"
---
# Relationship 4708: S0066 — uses → T1070.006

**Source object:** [[01 ATT&CK/S0066 - 3PARA RAT|S0066: 3PARA RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[3PARA RAT](https://attack.mitre.org/software/S0066) has a command to set certain attributes such as creation/modification timestamps on files.(Citation: CrowdStrike Putter Panda)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d43315b0-d708-4197-b3ed-0a0b1199e434`.
