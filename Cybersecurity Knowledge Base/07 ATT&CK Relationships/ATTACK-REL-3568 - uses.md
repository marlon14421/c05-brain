---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1598.002"
stix_relationship_id: "relationship--6385d0af-765c-44f9-afab-ed3852f6a22f"
---
# Relationship 3568: G0035 — uses → T1598.002

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.002 - Spearphishing Attachment|T1598.002: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has used spearphishing with Microsoft Office attachments to enable harvesting of user credentials.(Citation: US-CERT TA18-074A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6385d0af-765c-44f9-afab-ed3852f6a22f`.
