---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0533"
target_object: "T1082"
stix_relationship_id: "relationship--f8a9e39a-0038-437c-96ad-4408d028dd86"
---
# Relationship 3632: S0533 — uses → T1082

**Source object:** [[01 ATT&CK/S0533 - SLOTHFULMEDIA|S0533: SLOTHFULMEDIA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) has collected system name, OS version, adapter information, and memory usage from a victim machine.(Citation: CISA MAR SLOTHFULMEDIA October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8a9e39a-0038-437c-96ad-4408d028dd86`.
