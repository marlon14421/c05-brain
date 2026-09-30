---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0130"
target_object: "T1566.001"
stix_relationship_id: "relationship--4b98c580-7907-487c-a5b1-202663762c47"
---
# Relationship 3857: G0130 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0130 - Ajax Security Team|G0130: Ajax Security Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ajax Security Team](https://attack.mitre.org/groups/G0130) has used personalized spearphishing attachments.(Citation: Check Point Rocket Kitten)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b98c580-7907-487c-a5b1-202663762c47`.
