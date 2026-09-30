---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1142"
target_object: "T1095"
stix_relationship_id: "relationship--b832110a-0610-4489-9729-a89064b8d61b"
---
# Relationship 4229: S1142 — uses → T1095

**Source object:** [[01 ATT&CK/S1142 - LunarMail|S1142: LunarMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LunarMail](https://attack.mitre.org/software/S1142) can ping a specific C2 URL with the ID of a victim machine in the subdomain.(Citation: ESET Turla Lunar toolset May 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b832110a-0610-4489-9729-a89064b8d61b`.
