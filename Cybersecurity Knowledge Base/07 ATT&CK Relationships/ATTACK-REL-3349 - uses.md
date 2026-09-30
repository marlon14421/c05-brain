---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1685"
stix_relationship_id: "relationship--cc536085-c3d8-4a94-8db4-bdd942dfecfc"
---
# Relationship 3349: S0455 — uses → T1685

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has a function to kill processes associated with defenses and can prevent certain processes from launching.(Citation: Medium Metamorfo Apr 2020)(Citation: FireEye Metamorfo Apr 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc536085-c3d8-4a94-8db4-bdd942dfecfc`.
