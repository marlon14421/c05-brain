---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1573.002"
stix_relationship_id: "relationship--cfb7e335-e7a3-4dc3-91b8-70381a888222"
---
# Relationship 3247: G0080 — uses → T1573.002

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) has used the Plink utility to create SSH tunnels.(Citation: Group IB Cobalt Aug 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfb7e335-e7a3-4dc3-91b8-70381a888222`.
