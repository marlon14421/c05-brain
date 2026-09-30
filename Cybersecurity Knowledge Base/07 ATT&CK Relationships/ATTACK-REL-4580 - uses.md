---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0032"
target_object: "T1133"
stix_relationship_id: "relationship--c5a19163-a5b3-4b14-bf9d-d23d95d218d4"
---
# Relationship 4580: C0032 — uses → T1133

**Source object:** [[01 ATT&CK/C0032 - C0032|C0032: C0032]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [C0032](https://attack.mitre.org/campaigns/C0032) campaign, [TEMP.Veles](https://attack.mitre.org/groups/G0088) used VPN access to persist in the victim environment.(Citation: FireEye TRITON 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5a19163-a5b3-4b14-bf9d-d23d95d218d4`.
