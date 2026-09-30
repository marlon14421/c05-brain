---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0672"
target_object: "T1057"
stix_relationship_id: "relationship--ae05ae0a-7806-491a-8350-33600df44d2a"
---
# Relationship 4457: S0672 — uses → T1057

**Source object:** [[01 ATT&CK/S0672 - Zox|S0672: Zox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zox](https://attack.mitre.org/software/S0672) has the ability to list processes.(Citation: Novetta-Axiom)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae05ae0a-7806-491a-8350-33600df44d2a`.
