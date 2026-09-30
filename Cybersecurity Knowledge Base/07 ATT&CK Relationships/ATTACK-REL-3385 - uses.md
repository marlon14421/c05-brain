---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0453"
target_object: "T1497.003"
stix_relationship_id: "relationship--8f5e9158-1abe-4ed7-8a0a-df07f629aac8"
---
# Relationship 3385: S0453 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0453 - Pony|S0453: Pony]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pony](https://attack.mitre.org/software/S0453) has delayed execution using a built-in function to avoid detection and analysis.(Citation: Malwarebytes Pony April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f5e9158-1abe-4ed7-8a0a-df07f629aac8`.
