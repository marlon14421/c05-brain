---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1008"
target_object: "T1598.002"
stix_relationship_id: "relationship--cfdd9ee1-119f-4071-8498-02bb568fc778"
---
# Relationship 2751: G1008 — uses → T1598.002

**Source object:** [[01 ATT&CK/G1008 - SideCopy|G1008: SideCopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.002 - Spearphishing Attachment|T1598.002: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SideCopy](https://attack.mitre.org/groups/G1008) has crafted generic lures for spam campaigns to collect emails and credentials for targeting efforts.(Citation: MalwareBytes SideCopy Dec 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfdd9ee1-119f-4071-8498-02bb568fc778`.
