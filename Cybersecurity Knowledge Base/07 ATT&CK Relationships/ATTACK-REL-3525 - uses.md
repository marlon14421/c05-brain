---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1199"
stix_relationship_id: "relationship--ef3683c7-1514-4fa3-9c2d-477fb945982a"
---
# Relationship 3525: G1041 — uses → T1199

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) targeted third-party entities in trusted relationships with primary targets to ultimately achieve access at primary targets. Entities targeted included DNS registrars, telecommunication companies, and internet service providers.(Citation: Talos Sea Turtle 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef3683c7-1514-4fa3-9c2d-477fb945982a`.
