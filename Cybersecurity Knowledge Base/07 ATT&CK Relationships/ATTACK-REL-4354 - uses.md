---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1566.002"
stix_relationship_id: "relationship--0f7756fb-ea96-4d3a-9a23-a0f0a326de63"
---
# Relationship 4354: G0094 — uses → T1566.002

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has sent spearphishing emails containing a link to a document that contained malicious macros or took the victim to an actor-controlled domain.(Citation: EST Kimsuky April 2019)(Citation: Netscout Stolen Pencil Dec 2018)(Citation: KISA Operation Muzabi)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f7756fb-ea96-4d3a-9a23-a0f0a326de63`.
