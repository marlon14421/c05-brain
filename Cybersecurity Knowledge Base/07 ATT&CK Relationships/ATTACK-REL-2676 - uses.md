---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1027.005"
stix_relationship_id: "relationship--fb6ffb5c-5405-4515-a120-7a34414933ea"
---
# Relationship 2676: G0049 — uses → T1027.005

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has tested malware samples to determine AV detection and subsequently modified the samples to ensure AV evasion.(Citation: Palo Alto OilRig April 2017)(Citation: Unit42 OilRig Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb6ffb5c-5405-4515-a120-7a34414933ea`.
