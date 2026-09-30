---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1683.001"
stix_relationship_id: "relationship--91a6e21c-2119-47ff-b0b8-0f1cd08e3487"
---
# Relationship 3277: G1056 — uses → T1683.001

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1683.001 - Written Content|T1683.001: Written Content]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has created Dune-themed GitHub repositories using stolen tokens.(Citation: Wiz Mini Shai-Hulud MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91a6e21c-2119-47ff-b0b8-0f1cd08e3487`.
