---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0133"
target_object: "T1204.002"
stix_relationship_id: "relationship--9ef511b5-ecdb-4f11-97f6-0046ec25af84"
---
# Relationship 3812: G0133 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0133 - Nomadic Octopus|G0133: Nomadic Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Nomadic Octopus](https://attack.mitre.org/groups/G0133) as attempted to lure victims into clicking on malicious attachments within spearphishing emails.(Citation: Securelist Octopus Oct 2018)(Citation: ESET Nomadic Octopus 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ef511b5-ecdb-4f11-97f6-0046ec25af84`.
