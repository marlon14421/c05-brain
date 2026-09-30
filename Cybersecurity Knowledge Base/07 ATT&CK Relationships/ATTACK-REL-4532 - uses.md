---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0126"
target_object: "T1016"
stix_relationship_id: "relationship--d374ab1b-4ff8-4ee8-92d2-466581cf58c8"
---
# Relationship 4532: G0126 — uses → T1016

**Source object:** [[01 ATT&CK/G0126 - Higaisa|G0126: Higaisa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Higaisa](https://attack.mitre.org/groups/G0126) used ipconfig to gather network configuration information.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d374ab1b-4ff8-4ee8-92d2-466581cf58c8`.
