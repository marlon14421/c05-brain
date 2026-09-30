---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0533"
target_object: "T1036.004"
stix_relationship_id: "relationship--5c039dbf-c443-4f9b-b036-fcabaed74a3b"
---
# Relationship 3209: S0533 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0533 - SLOTHFULMEDIA|S0533: SLOTHFULMEDIA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) has named a service it establishes on victim machines as "TaskFrame" to hide its malicious purpose.(Citation: CISA MAR SLOTHFULMEDIA October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c039dbf-c443-4f9b-b036-fcabaed74a3b`.
