---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1010"
stix_relationship_id: "relationship--ac0b0f1f-a9c8-4890-aa2f-6012b75a9c52"
---
# Relationship 4867: S0198 — uses → T1010

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) can discover and close windows on controlled systems.(Citation: Red Canary NETWIRE January 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac0b0f1f-a9c8-4890-aa2f-6012b75a9c52`.
