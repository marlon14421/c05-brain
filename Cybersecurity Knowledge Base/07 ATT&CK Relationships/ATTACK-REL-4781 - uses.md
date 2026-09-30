---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0067"
target_object: "T1070.004"
stix_relationship_id: "relationship--7985b09e-9241-489c-a0f2-45a6f5c782f1"
---
# Relationship 4781: S0067 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0067 - pngdowner|S0067: pngdowner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[pngdowner](https://attack.mitre.org/software/S0067) deletes content from C2 communications that was saved to the user's temporary directory.(Citation: CrowdStrike Putter Panda)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7985b09e-9241-489c-a0f2-45a6f5c782f1`.
