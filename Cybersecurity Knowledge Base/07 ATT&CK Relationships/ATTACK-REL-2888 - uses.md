---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1571"
stix_relationship_id: "relationship--800f3241-62f4-4eb4-b9a2-df62f67d27d6"
---
# Relationship 2888: G0032 — uses → T1571

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Some [Lazarus Group](https://attack.mitre.org/groups/G0032) malware uses a list of ordered port numbers to choose a port for C2 traffic, creating port-protocol mismatches.(Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster RATs)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--800f3241-62f4-4eb4-b9a2-df62f67d27d6`.
